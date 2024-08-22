```
minikube start --kubernetes-version=v1.28.12 --memory=6G --cpus=3 --disk-size=30000mb --cni=calico --network-plugin=cni
kubectl apply ./app.yaml
```