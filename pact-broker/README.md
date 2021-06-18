# Pact Broker Helm Chart

This Helm chart is a lightweight way to configure and run official
[pact broker](https://github.com/pact-foundation/pact_broker)
based on [pact broker docker image](https://github.com/pact-foundation/pact-broker-docker).

## Requirements

* Kubernetes >= 1.16
* Helm >= 3.3.0

## Installing

### Install released version using Helm repository

* Add the Helm charts repo:
```
helm repo add almorgv https://almorgv.github.io/helm-charts/charts
```

* Install it with Helm:
```
helm install pact-broker almorgv/pact-broker
```

### Install development version using master branch

* Clone the git repo: `git clone git@github.com:almorgv/helm-charts.git`

* Install it with Helm: `helm install pact-broker ./pact-broker`

## Configuration

See [values.yaml](./values.yaml)
