## Helm Install
```bash
helm upgrade --install nginx charts/nginx -n default
```

## ArgoCD
Create an ArgoCD Application that points to the GitHub repo and sets:
- Path: `charts/nginx`
- Sync Policy: auto
- Namespace: `default`

Once deployed, access the application via:
```bash
http://<any-node-ip>:30080
```
# Trigger build
# trigger
