# Agent Instructions: GitOps & Kubernetes Manifests

## 🎯 Context
ArgoCD Application definitions and Kubernetes manifests for automated deployment.

## 🏗️ Structure & Standards
1. **Manifest Format:** Use pure YAML and Kustomize (`kustomization.yaml`) for environments (base vs overlays).
2. **ArgoCD:** Workloads must be defined as ArgoCD `Application` resources.
3. **Images:** Never use the `:latest` tag. Assume specific semantic versions or Git SHAs.
