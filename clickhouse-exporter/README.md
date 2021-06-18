# Clickhouse Exporter for Prometheus

This is a Helm Chart for [Clickhouse Prometheus Exporter](https://github.com/ClickHouse/clickhouse_exporter) based on [docker image maintained by Flant](https://hub.docker.com/r/flant/clickhouse-exporter).

## Installing

### Install released version using Helm repository

* Add the Helm charts repo:
```
helm repo add almorgv https://almorgv.github.io/helm-charts/charts
```

* Install it with Helm:
```
helm install clickhouse-exporter almorgv/clickhouse-exporter
```

### Install development version using master branch

* Clone the git repo: `git clone git@github.com:almorgv/helm-charts.git`

* Install it with Helm: `helm install clickhouse-exporter ./clickhouse-exporter`

## Configuration

See [values.yaml](./values.yaml)
