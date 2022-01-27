## Kubernetes Deployment

### Explain What Kubernetes is Used for?

Kubernetes is a powerful and extensible open-source platform for managing, scaling, and deploying containerized applications and services. It’s a system designed to handle the scheduling and coordinating of a container on a cluster and manage the workloads to ensure they run reliably. 

Kubernetes allows us, the users, to define the way our applications run, and how our application interacts with other applications. 

Kubernetes is a tool that allows us to manage our cloud infrastructure, and the complexities of having to manage a virtual machine or network so that we can focus on developing and scaling our application. Kubernetes provides a flexible and reliable platform to manage and scale containers with a simple, easy interface.

### Deploy Application to Kubernetes

Step 1: Create a Kubernetes Cluster
First of all, I create a Kubernetes cluster in AWS EKS using terraform where I deploy a microservices application. The terraform manifest can be found [here](https://github.com/calvin-puram/AWS-Terraform-EKS-Automation)

```
kubectl get node
```

![eks-node](/img/eks1.png)

Step 2: Deploy Microservice application
I will deploy a sample microservice application to our newly created cluster. I have gone ahead to set up a deployment and service file for these microservice in thesame folder of this task. 

![eks-node](/img/eks2.png)

Using the below command to deploy the application to the Kubernetes cluster

```
helmfile sync #to apply the kubernetes manifests using helmfile or
kubectl apply -f workloads.yaml #to use the kubectl option
```

And to see all the running microservice

```
kubectl get pods
```

![eks-node](/img/eks3.png)

A new cloud-native load balancer is created and we can use the external IP to access our app in the browser. Use the command below to get the external IP of the frontend service to access the app in the browser.

```
kubectl get service
```
![eks-node](/img/eks4.png)

