## Reference links

- [ArgoCD docs](https://argo-cd.readthedocs.io/en/stable/operator-manual/installation/)
- [Kubernetes gitops with ArgoCD by Janani Ravi - Linkedin Learning](https://www.linkedin.com/learning/kubernetes-gitops-with-argocd)
- [How to Deploy to Kubernetes using Argo CD and GitOps](https://www.digitalocean.com/community/tutorials/how-to-deploy-to-kubernetes-using-argo-cd-and-gitops)
- [Argo CD helm chart](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd)

### Install CLI tools

```bash
brew install argocd
```

```bash
brew install k3d
```

## Local Test Notes

### Create a multi node k3d cluster

```bash
k3d cluster create argocd-cluster --config ./cluster-config.yaml
```
Or,
```bash
k3d cluster create argocd-cluster --agents 2 --servers 1
```
