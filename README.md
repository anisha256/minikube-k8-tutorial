# minikube-k8-tutorial

## Step1: Install minikube and kubectl in Windows and start minikube
```
choco install minikube

```
```
minikube start 

```
## Step2: Create a Service and Deployment in yml file 

## Step 3: Open minikube tunnel  
Since the type is LoadBalancer so we need open the minikube tunnel
```
minikube tunnel
```

## Step4: Apply defination file
```
kubectl apply -f .\<yml-file-name>.yml 

```

