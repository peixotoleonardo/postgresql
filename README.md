# PostgreSQL

## Running in Kubernetes

```bash
helm upgrade --create-namespace  --namespace postgresql --install --atomic  \
    --set config.database.name=order \
    --set config.database.username=user \
    --set config.database.password=StrongPassword \
    postgresql ./.k8s/ -f ./.k8s/values.yaml
```