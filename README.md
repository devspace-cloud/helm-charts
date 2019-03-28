# component-chart

## Publishing

```
mkdir -p public
cd public
helm package ../component-chart;
helm repo index . --url https://charts.devspace.cloud/
```