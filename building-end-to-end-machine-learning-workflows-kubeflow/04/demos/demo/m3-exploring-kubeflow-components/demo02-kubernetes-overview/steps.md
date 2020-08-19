### create pod

```
kubectl apply -f pod.yaml
```

### Pod port-forwarding

```
kubectl port-forward pod my-nginx-single-pod 8080:80
```

Navigate to nginx using *localhost://8080/*.

### Check log of a pod 

```
kubectl logs -f my-nginx-single-pod
```

### create deployment 

```
kubectl apply -f deployment.yaml
```

### create service 

```
kubectl apply -f service.yaml
```

### Delete service

```
kubectl delete service nginx-service
kubectl delete -f service.yaml
```