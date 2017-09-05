## Kubernetes Objects
Examples of k8s objects to achieve desired cluster states.

#### Useful commands
```kubectl get rs``` <br />
```kubectl get pods --show-labels```<br />
```kubectl rollout status NameOfYAML```<br />
```kubectl expose deployment NameOfDeployment --type=NodePort``` <br />
```kubectl describe service NameOfDeployment```<br />
```kubectl set image deployment```<br />
```kubectl rollout history deployment```

#### Create a deployment
```$ kubectl create -f deployment.yaml --record```
