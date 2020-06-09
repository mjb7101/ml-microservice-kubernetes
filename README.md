[![CircleCI](https://circleci.com/gh/mjb7101/ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/gh/mjb7101/ml-microservice-kubernetes)

## Operationalize a Machine Learning Microservice API.

Deploy a containerized flask (python) app which serves out predictions (inference) about housing prices through API calls to a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, etc.

### Project Tasks

* Test project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested

---

## Setup the Environment

* Create a virtualenv and activate it:
`
python3 -m venv <your environment name>
source <your environment name>/bin/activate
`

* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
