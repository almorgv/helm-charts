# Helm Charts

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/almorgv)](https://artifacthub.io/packages/search?repo=almorgv)

## Helm Repo

Helm repo located at https://almorgv.github.io/helm-charts/charts

```
helm repo add almorgv https://almorgv.github.io/helm-charts/charts
```

## Charts

- [Gitlab Code Review Notifier](./gitlab-code-review-notifier/README.md)
- [Pact Broker](./pact-broker/README.md)
- [Clickhouse Prometheus Exporter](./clickhouse-exporter/README.md)

## Contributing

1. Bump chart version
1. Package a chart
    ```
    helm package ./clickhouse-exporter/ -d charts/
    ```
1. Update index
    ```
    helm repo index charts/
    ```