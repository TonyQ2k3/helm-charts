# helm-charts
Centralized Helm charts for multiple apps


# Pushing a chart
```bash
helm push ./chart.tgz oci://registry-1.docker.io/username
```

# Installing a chart
```bash
helm install libba oci://registry-1.docker.io/tonyq2k3/library-manager --version 2.0.0 --set database.service.url=<remote_database_url>
```