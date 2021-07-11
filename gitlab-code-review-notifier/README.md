# Gitlab Code Review Notifier

This is a Helm Chart for [Gitlab Code Review Notifier](https://github.com/almorgv/gitlab-code-review-notifier).

## Installing

### Install a released version using Helm repository

* Add the Helm charts repo:
```
helm repo add almorgv https://almorgv.github.io/helm-charts/charts
```

* Install it with Helm:
```
helm install gitlab-code-review-notifier almorgv/gitlab-code-review-notifier
```

### Install development version using master branch

* Clone the git repo: `git clone git@github.com:almorgv/helm-charts.git`

* Install it with Helm: `helm install gitlab-code-review-notifier ./gitlab-code-review-notifier`

## Configuration

See [values.yaml](https://github.com/almorgv/helm-charts/blob/master/gitlab-code-review-notifier/values.yaml)
