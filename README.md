[![CircleCI](https://circleci.com/gh/nepgpn/devops-capstone-project/tree/main.svg?style=svg)](https://circleci.com/gh/nepgpn/devops-capstone-project/tree/main)

##Project Overview
<h1 >Cloud DevOps Engineer Nanodegree by Udacity: Capstone Project</h1>

## About The Project

This project is a capstone project for AWS UDACITY devops nano-degree program.
These are the main skills involved for the projects.
1. Worked with AWS
2. Used CircleCI for CI/CD pipeline
4. Used Ansible and CloudFormation to deploy clusters
5. Built Kubernetes clusters (AWS EKS)
6. Built Docker containers in pipelines (Dockerhub)
7. Pushed docker Image to ECR and use in deployment yaml


## Project Tasks
1. Test your project code using linting
2. Configure Kubernetes and create a Kubernetes cluster using EKSCTL
3. Upload a complete Github repo with CircleCI
4. Deploy application using Kubernetes test the application via CI/CD pipleline

-------------
#### Setup the environment variable

The following environment variablesz must be set for the project on CircleCI via the project settings page, before the project can be built successfully.

| Variable                 | Description                                                                                                                                                     |
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `AWS_ACCESS_KEY_ID`      | AWS access id  (get from aws console or awscli config file)                                                                                                     |
| `AWS_SECRET_ACCESS_KEY ` | AWS secrete key (get from aws console or awscli config file)                                                                                                    |
| `AWS_DEFAULT_REGION`     | Used by the AWS CLI. Project value: "us-east-2"                                                                                                                 |
| `AWS_ECR_URL`            | AWS ECR docker image registry URL in the format `AWS_ACCOUNT_ID`.dkr.ecr.`AWS_DEFAULT_REGION`.amazonaws.com                                                     |
| `DOCKER_LOGIN`           | Docker username                                                                                                                                                 | 
| `DOCKER_PASSWD`          | Docker password                                                                                                                                                 |


#### GITHUB

- [Github Repo](https://github.com/nepgpn/devops-capstone-project.git)


