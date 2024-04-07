
# Assignment 3

Ensure you're in the correct directory and have Minikube ready for action. Follow all steps: 

#### Step 1: Go to Assignment3 Directory
```bash
cd assignment3
```

#### Step 2: minikube start and enabling ingress
```bash
minikube start
minikube addons enable ingress
```

#### Step 3: Deploy Service, save files 
Use this to update all yaml files, use as a 'save' button

```bash
kubectl apply -f '*.yaml'
```

#### Step 4: Verify Deployment, curl command

```bash
curl http://$(minikube ip)/
```



