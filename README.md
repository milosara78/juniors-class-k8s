# juniors-class-k8s
simple Dockerized Nginx app deployed in k8s

This project includes :
Deployment ```(deployment.yaml)``` – Deploys 3 replicas of Nginx
Service ```(service.yaml)``` – Exposes the deployment within the cluster
Ingress (Optional) ```(ingress.yaml)``` – Routes traffic via an ingress controller

🚀🤩 deploy the manifest and start enjoying the magic of k8s🌟

```
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml  # Only if using Ingress

```



