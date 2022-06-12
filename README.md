# Blue-Green Test

Simple test app to demonstrate [Argo CD](https://argo-cd.readthedocs.io/en/stable/). Image available at [adrianoneres/blue-green](https://hub.docker.com/repository/docker/adrianoneres/blue-green).

## Execute

### 1. Create cluster

```shell
kind create cluster --config=k8s/kind.yml --name=example
```

### 2. Install Argo CD

### 3. Run apply command

```shell
kubectl apply -f k8s/application.yml
```