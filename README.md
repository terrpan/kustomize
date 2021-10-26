# kustomize


Change directory in to correct overlay eg. dev
```bash
cd overlays/dev
```

Run kustomize for that overlay and save it for better times
```bash
kubectl kustomize > /tmp/complete-deployment.yml
```
Run kustomize and deploy to a k8s cluster

```bash
kubectl apply -k
```
