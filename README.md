# hello-world-kube

## Prereq
Download [minikube](https://minikube.sigs.k8s.io/docs/start/) to get started locally

## Usage

- `kubectl apply -f mongo-config.yaml ` 
- `kubectl apply -f mongo-secrets.yaml  `
- `kubectl apply -f mongo.yaml`  
- `kubectl apply -f webapp.yaml  `


## Check usage
-  `kubectl get pods`
-  `kubectl get all`

# Other commands:
- `kubectl describe pods` <pod_name> or `kubectl describe service <service_name>`
- `kubectl logs <pod_name>`
- `kubectl get service` --> To get all the ports projected from the app
- `kubectl get node -o wide` --> Get the ip adress of the node, to start using the application
- `minikube ip` for the application setup locally, it will be the same id to get