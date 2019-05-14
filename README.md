# sandbox-kustomize


## How to deploy

### Deploy service

``` sh
kubectl create -f service.yaml
```

### Generate manifest file

``` sh
kubectl kustomize ./staging
```

or 

``` sh
kubectl kustomize ./production
```


### Deploy manifest

``` sh
kubectl apply --kustomize ./staging
```

or 

``` sh
kubectl apply --kustomize ./production
```
