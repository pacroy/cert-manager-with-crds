# Bookstack Helm Chart

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --set email=<email@domain.com>
```

## Installation from Repository

```sh
helm repo add pacroy https://raw.githubusercontent.com/pacroy/helm-repo/master
```

```sh
helm repo update
```

```sh
helm install <release_name> pacroy/cert-manager --namespace=<namespace> --set email=<email@domain.com>
```
