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
### lists profiles in minkube
```
minikube profile list
```
### shows namespaces
```
kubectl get ns
```
### shows pods with labels
```
kubectl get pods --show-labels -n <namespace>
```
### creates namespace
```
kubectl create ns skns
```
### shifts to namespace
```
kubens <namespace>
```
### shows services running
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
### applies task definition configuration
```
kubectl apply -f pod.yaml -n skns
```
```
kubectl get pods -o wide
```
### shows services
```
kubectl get svc
```
### creating service
```
kubectl expose pod/<podname> --type=LoadBalancer/clusterip/nodeport --name=<name of service --port=<port> --target-port=container-port
```
### labels pod
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
### minikube creates profile and starts it
```
minikube start -p <profilename>
```
```
minikube delete -p <profilename>
```
### shows profile info
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

