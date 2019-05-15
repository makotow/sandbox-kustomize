# sandbox-kustomize


## How to deploy

### Deploy service

``` sh
kubectl create -f service.yaml
```

### Generate manifest file

``` sh
kubectl kustomize ./v1
```

or 

``` sh
kubectl kustomize ./v2
```


### Deploy manifest

``` sh
kubectl apply --kustomize ./v2
```

or 

``` sh
kubectl apply --kustomize ./v2
```
