# Dockerized-ML-Webapp-Deployed-on-GKE-Autopilot

This project shows how to deploy a machine learning web application on Google Kubernetes Engine (GKE) Autopilot.
 
The steps included for this project are, creating a docker image of our machine learning web app and saving it in Google Container Registry (GCR), 
creating a GKE-Autopilot cluster, creating a Kubernetes deployment and service, testing the web app running on 
GKE-Autopilot and finally, deleting the project to avoid incurring charges to our Google Cloud account.

## Project Pre-requisites:
1. Google Cloud Account.
2. Enabled Billing.
3. GKE and GCR enabled

## Project Tasks:

1. Creating Docker-Image in Google Container Registry.
2. Creating GKE-Autopilot Cluster.
3. Creating Deployment.
4. Exposing Service.
5. Testing the Web Application.
6. Deleting the Project.

** GKE-Autopilot Cluster Creation:**

<p align="center">
  <img src="images\gke1.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gke2.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gke3.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gke4.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gke5.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gkeconnect.png" alt="workflow"/>
</p>


** Image pushed to GCR:**

<p align="center">
  <img src="images\image pushed to gcr.png" alt="workflow"/>
</p>

** Creating Deployment:**

<p align="center">
  <img src="images\get deployments.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\get pods.png" alt="workflow"/>
</p>

<p align="center">
  <img src="images\gke workload.png" alt="workflow"/>
</p>

** Exposing Service:**

<p align="center">
  <img src="images\services.png" alt="workflow"/>
</p>

** Testing the Web Application:**

<p align="center">
  <img src="images\final out.png" alt="workflow"/>
</p>



## Dataset Used: 
- Beans is a dataset of images from tensorflow datasets. [link](https://www.tensorflow.org/datasets/catalog/beans)



