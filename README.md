# Homelab Argo CD

## Base Setup

```bash
# Install Argo CD via helm
  helm upgrade \
    --install argocd ./argocd \
    --namespace=argocd \
    --create-namespace \
    -f values-server.yaml
```