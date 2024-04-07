
# Assignment 3
### Getting Started

Ensure you're positioned in the correct directory and have Minikube ready for action. Follow these steps meticulously:

####Step 1: Navigate to Assignment 3 Directory
Open your terminal and execute the following commands: 

####Step 1: Go to Assignment3 Directory
```bash
cd assignment3
```

#### Step 2: minikube start and enabling ingress
```bash
minikube start
minikube addons enable ingress
```

#### Step 3: Deploy Service, 
Use this to update, use as a 'save' button

```bash
kubectl apply -f '*.yaml'
```

#### Step 4: Verify Deployment, curl command

```bash
curl http://$(minikube ip)/
```



