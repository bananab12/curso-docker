# K8S

Una plataforma para automatizar el despliegue, escala y manejo de contenedores. En otras palabras es un Administrador de contenedores (Docker)

# Comandos útiles

```
minikube pause
```

```
minikube unpause
```

```
minikube stop
```

```
minikube delete --all
```

```
kubectl get pod

kubectl apply -f postgres-config.yml
kubectl apply -f postgres-secrets.yml
kubectl apply -f postgres.yml
```

```
kubectl get all

kubectl logs <nombre del deployment>
kubectl get events
```

```
minikube ip

minikube ssh -- docker images
```
