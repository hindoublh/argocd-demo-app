# Argo CD Demo App

This repository contains Kubernetes manifests used by Argo CD.

## Structure

```
argocd-demo-app/
└── manifests/
    ├── deployment.yaml
    └── service.yaml
```

The deployment creates an NGINX Pod.

The service exposes the application using a NodePort service.