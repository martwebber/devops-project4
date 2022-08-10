[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 

# Operationalize a Machine Learning Microservice API

## Project Overview

The Operationalize a Machine Learning Microservice API contains a Machine Learning Microservice that predicts house prices in Boston according to based on different features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios.

## Tasks 
- Task 1: Complete the Dockerfile
- Task 2: Run a Container & Make a Prediction
- Task 3: Improve Logging & Save Output
- Task 4: Upload the Docker Image
- Task 5: Configure Kubernetes to Run Locally
- Task 6: Deploy with Kubernetes and Save Output Logs
- Task 7: CircleCI Integration


## Requirements
 - Python 3.7
 - Docker
 - Kubernetes
 - Hadolint

## Step 1: Clone repo 
```
git clone git@github.com:udacity/DevOps_Microservices.git

```
## Step 2: Install dependencies
- Set up the virtual environment by running ```make setup```.  
- Install dependencies by running ```make install```

## Step 3: Run Docker container  
- Run the application on docker by calling `./run_docker.sh`

## Step 4: Upload the docker image to Docker Hub
- Run `./upload_docker.sh` to upload the docker image to docker hub.

## Step 5: Kubernetes deployment
- Run `./run_kubernetes.sh` to deploy the ML model to a kubernetes cluster.

## Contacts    
If you have any question or feedback about the project, you can reach out to me via Email: mwangi.martin24@gmail.com or send me a message on
[LinkedIn](https://www.linkedin.com/in/martin-mwangi-46523483/)

## Resources and important links  
- [Kubernetes](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
- [Docker](https://www.docker.com/get-started/)

## License  

This project is licensed under the MIT Open Source license Copyright (c) 2022.
