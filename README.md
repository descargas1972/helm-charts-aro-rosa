# Helm Charts for Managed Openshift Black Belt examples

## Charts

See [/charts](charts) for a list of charts.

1. Add This Repository to your Helm

    ```bash
    helm repo add mobb https://rh-mobb.github.io/helm-charts/
    ```

1. Update your Repository

    ```bash
    helm repo update
    ```

1. Install a Chart

    ```bash
    helm install -n my-prometheus mobb/rosa-federated-prometheus
    ```

## Starters

To create a new chart using one of our starters, clone down this repo and run

```bash
helm create example-cr --starter $(pwd)/../starters/cr
```
