# Commandes utiles

```docker
docker build -t mytest:latest .
docker compose up
docker compose down
```

```kubernetes
kubectl get pods
kubectl create -f namespace.yml
kubectl apply -f file.yml
kubectl apply -f file.yml -n namespace
kubectl logs pods/podsName
kubectl get namespace
```

```bash
minikube start
minikube addons enable ingress
minikube service -n ingress-nginx ingress-nginx-controller
```
