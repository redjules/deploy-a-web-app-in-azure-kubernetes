# Deploy a web app in azure kubernetes

# Project Description

In this project we we will deploy a Web Application in Azure Kubernetes Services. We will do the following steps:

-Create an Azure Container Registry to store our container images, and set some identities configuration need for the project;

-Clone an application from Github, build a Docker image, run a container and push the image to Azure Container Registry;

-Create an Azure Kubernetes Cluster and set a Node Pool to host containers in a POD architecture;

-Deploy an application in Azure Kubernetes Cluster using an Image hosted in Azure Container Registry and increase and decrease Pods;

-Scale the Node Pool to support the increase of new pods in the Kubernetes cluster;

-Monitoring metrics and see the Azure Kubernetes Cluster health;

-Clean Up the environment

# Snapshots

![overview](/azure_aks.png)

![1](/1.png)

![2](/2.png)

![3](/3.png)

![4](/4.png)

![5](/5.png)

Here is the final result, a website deployed with Kubernets in Azure:
![6](/6.png)
