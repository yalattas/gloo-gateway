# Gloo Gateway

install *Gateway* CRDs
```
kubectl apply -f https://github.com/kubernetes-sigs/gateway-api/releases/download/v1.2.0/standard-install.yaml
```

Then, install Gloo Gateway with its dependencies by running `helmfile apply`
> You might need to disable Gloo Objects release before applying the first time