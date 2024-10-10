# MERN Stack Application Deployment on Kubernetes

This repository contains deployment configurations for a MERN stack application using Kubernetes on a Minikube cluster.

## Prerequisites

Before deploying the application, you need to install **Minikube** and **kubectl** on your system. Follow the steps below for installation on **Red Hat** or **Amazon Linux**.

## Installation Steps

### 1. Install Minikube

Run the following commands to install Minikube:

```bash
# Download the Minikube RPM package
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-latest.x86_64.rpm
# Install the Minikube RPM
rpm -Uvh minikube-latest.x86_64.rpm
# Start Minikube (use --force to overwrite existing configurations if necessary)
minikube start --force
```

### 2. Install Kubectl
Next, install kubectl with the following commands:

```bash 
# Download the kubectl binary
curl -O https://s3.us-west-2.amazonaws.com/amazon-eks/1.28.3/2023-11-14/bin/linux/amd64/kubectl

# Make the binary executable
chmod +x ./kubectl

# Move kubectl to a directory in your PATH
cp ./kubectl /usr/bin/

```

- After installing Minikube and kubectl, you can proceed to deploy the MERN stack application. Please refer to the deployment instructions in this repository.

## Download the repository

```bash
git clone https://github.com/Vikas-Prince/K8s-FullStack-Deployment.git
cd K8s-FullStack-Deployment
```
