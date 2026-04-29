# AI Task Platform - Infrastructure

This repository contains Kubernetes manifests and ArgoCD configuration for deploying the AI Task Processing Platform.

## Structure

- infra/k8s → Kubernetes manifests
- infra/argocd → ArgoCD application config

## Deployment

Apply manually:
```bash
kubectl apply -f infra/k8s
