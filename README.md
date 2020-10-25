# KubernetesApplicationDevelopment
Files related to Kubernetes Application Development Course

## apiVersion

https://matthewpalmer.net/kubernetes-app-developer/articles/kubernetes-apiversion-definition-guide.html

## Get into a pod

Look at the pod
```
kubectl get pods | grep my-nginx
my-nginx                                 1/1     Running   0          10m
```
Start the bash session
```
kubectl exec -it my-nginx -- bash
```
