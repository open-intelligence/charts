# OpenI Charts Repo

This is an Open-Intelligence charts repository.

### Prerequisites

- Connectable Kubernetes cluster
- [Helm 2.8.0+](https://github.com/helm/helm#install)

### How It Works

```console
# add repository into helm repos
$ helm repo add ocharts https://open-intelligence.github.io/charts/

# search the available charts
$ helm search ocharts

$ helm get/install ocharts/xxxx
```
