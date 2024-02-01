# Kubernetes challenge

Deploy this application to [Minikube](https://github.com/kubernetes/minikube) and customise the environment variable to display your name. See instructions [here](https://github.com/learnk8s/kubernetes-challenge).

```
$ curl $(minikube ip)
Hello Joy!
```
# Run application
- `minikube addons enable ingress`
- `kubectl apply -f manifests`
- `curl $(minikube ip)`
