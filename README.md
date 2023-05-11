# minikube-commands
Commands useful when working with minikube.

```
brew install minikube
```
```
brew list
```
```
brew install kubectx
```
```
brew install kubectl
```
```
minikube version
```
```
minikube start
```
```
minikube profile list
```
```
kubectl get ns
```
```
kubectl get pods --show-labels -n <namespace>
```
```
kubectl create namespace skns
```
```
kubens <namespace>
```
```
minikube service list
```
```
minikube stop
```
```
minikube start
```
```
minikube start -p demo-cluster --memory 2048 --cpus 2
```
```
kubectl apply -f pod.yaml -n skns
```
```
kubectl get pods -o wide
```
```
minikube service list
```
```
kubectl get svc
```
```
kubectl expose pod/<podname> --type=LoadBalancer/clusterip/nodeport --name=<name of service --port=<port> --target-port=container-port
```
```
kubectl label pod <podname> env=<label>
```
```
kubectl delete pod <podname>
```
```
kubectl delete service <service-name>
```
```
kubectl get all
```
```
minikube start -p demo2
```
```
minikube delete -p demo2
```
```
minikube config view
```
```
kubectl config view
```
```
kubectl edit <servicename>
```
```
kubectl config get-contexts
```
```
kubectl get current-context
```
```
kubectl describe pod/<podname>
```
```
kubectl describe service/<service-name>
```
```
kubectx <clustername>
```

