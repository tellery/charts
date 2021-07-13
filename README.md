# Tellery Helm Charts

## Charts

| name | description |
| --- | --- |
| [charts/tellery](https://github.com/tellery/charts/tree/main/charts/tellery) | the Tellery Helm Chart - used to deploy Tellery on Kubernetes

## Repo Usage

```sh
helm repo add tellery-stable https://tellery.github.io/charts
helm repo update

helm install tellery tellery-stable/tellery
```
