# Helm Chart Repository

This repository contains custom Helm charts. It is configured as a Helm repository and hosted via GitHub Pages.

## 🧭 How to Use This Repo

Add this Helm repo to your local Helm client:

```bash
helm repo add myrepo https://lhes23.github.io/helm-charts/
helm repo update
```

## Install the chart
```
helm install my-wordpress my-helm-repo/wp-chart -f values.yaml
```