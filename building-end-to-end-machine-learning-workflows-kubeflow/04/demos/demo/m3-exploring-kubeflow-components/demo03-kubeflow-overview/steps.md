
### Connect with the cluster
Use the google console kubenetes dashboard to identify the cluster. Click on the *Connect* and copy the command to execute on terminal. 

### Check context

```
kubectl config current-context 
```

### List available namespaces

```
kubectl get namespace
```

### List all pods in a kubeflow namespace

```
kubectl get pods -n kubeflow
```

### List all services in Kubeflow namespace

```
kubectl get service -n kubeflow
```

### Google kubernetes engine console overview

Navigate to different sections of GKE console.