# Steadybit Kubernetes Extension 

This Helm chart adds the Steadybit Kubernetes extension to your Kubernetes cluster via a deployment.

## Quick Start

### Add Steadybit Helm repository

```
helm repo add steadybit https://steadybit.github.io/helm-charts
helm repo update
```

### Installing the Chart

To install the chart with the name `steadybit-extension-kubernetes`.

```bash
$ helm upgrade steadybit-extension-kubernetes \
    --install \
    --wait \
    --timeout 5m0s \
    --create-namespace \
    --namespace steadybit-extension \
    steadybit/steadybit-extension-kubernetes
```
