# minikube-k8-tutorial

## Step1: Install minikube and kubectl in Windows and start minikube
```
choco install minikube

```
```
minikube start 

```
## Step2: Create a Service
```
kubectl create -f service.yml

```
## Step3: Create a Deployment
```
kubectl create -f deployment.yml

```

## Step 4: Expose deployment  
```
kubectl expose deployment nginx-deployment --type=LoadBalancer --port=8080
``