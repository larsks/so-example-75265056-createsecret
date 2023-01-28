This repository accompanies <https://stackoverflow.com/q/75265056/147356>.

## Deploying

You can deploy this repository by running:

```
kubectl apply -k .
```

This will deploy the manifests into the `env-example` namespace. You can view the environment in the application pod by running:

```
kubectl -n env-example exec -it deployment/env-example -- env
```
