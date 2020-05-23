# Cert-manager Helm Chart with CRDs

## IMPORTANCE NOTES!

The latest Jetstack's cert-manager v0.15.0 has now included CRDs in the chart. You can install those CRDs by setting `installCRDs` to `true`.
See https://cert-manager.io/docs/installation/kubernetes/ for more information

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
