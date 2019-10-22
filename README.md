# ALC 4 Phase II Cloud Challenge
 The goal of the challenge is to Deploy React Application using Docker and Google Cloud Platform.

# How to Start
1.	Create a React App (Create React App)
2.	Package your app into a Docker image
3.	Run the container locally on your machine 
4.	Upload the image to a registry (Docker Hub)
5.	Create a container cluster (inside Kubernetes Engine in GCP)
6.	Deploy your app to the cluster
7.	Expose your app to the Internet

# Prerequisites:
1.	Install nodejs on your Windows machine (prefarably windows 10 with recent updates)
2.	Setup GCP Cloud SDK.
3.	Install docker desktop (or docker toolbox if you are on windows 8 and below) and enable the settings to use Linux containers.
4.	Set up google container credential helper in docker so you can push the created image to your google container registry
5. Using VSCode with the docker & git plugins will help greatly
6. Have a Dockerhub account with a repository already created.

# Special Thanks to George Udosen's Meduim Post. Use it as a guide. (https://medium.com/@udoyen_aba/alc-4-phase-ii-cloud-challenge-ffe4d00a23d3)

1. Once you have followed the steps on the post and uploaded your created container to either dockerhub or GCP directly, its time to create the cluster & workload on kubernetes.
2. What i found that worked for me was to chose the "Deploy Container option" as this will create an appropriate cluster and workload for your container which won't have any errors.
3. Expose the app and follow the public address to view your the running app on your browser.

# END
