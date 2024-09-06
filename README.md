## Cloud-Native DevOps Project (Part 4 of 5)

## Background
Our University Library is a cornerstone of academic resources, aims to enhance accessibility to educational materials through an advanced online platform. 
You has been asked to develop a cloud-native microservices architecture to support the library’s diverse user base and streamline deployment processes.

By end of this project, you will gain a comprehensive understanding of essential
DevOps practices and cloud-native application deployment techniques. More
specifically, you will be able to do following:

1. Create Dockerfiles to containerize application and define the runtime
environment.
2. Develop Kubernetes YAML files (deployment.yaml and service.yaml) to deploy
and manage their microservice on Azure managed Kubernetes cluster.
3. Write Terraform scripts (main.tf, variables.tf, outputs.tf, provider.tf) to
provision Azure infrastructure.
4. Deploy Azure Kubernetes Service (AKS) and integrate PostgreSQL for data
storage.
5. Configure GitHub Actions workflows to automate the CI/CD pipeline.
6. Apply theoretical knowledge to real-world scenarios, enhancing their
understanding of cloud computing and DevOps principles. 

## Tasks

In this assignment, you will implement Deployment Automation using Terraform. You will apply learnings from Week 6.

Steps

1. Downlaod code from the Task Resources and unzip.
2. Create a github repository named : <your-name-sit722-part4> .
3. Add given code to a github repository (local first then push to the remote
repo).
4. Write Dockerfiles for each microservice ( book_catalog and
inventory_management ).
5. Create deployment.yaml .
6. Create container-registry.tf , kubernetes-cluster.tf , providers.tf
resource-group.tf , and variables.tf files.
7. Create infrastructure via terraform.
8. Deploy Microservice.