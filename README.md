![master status](https://github.com/sdelrio/argocd-sops/actions/workflows/main.yml/badge.svg)

# argocd-sops

Auto build image for ArgoCD with SOPS, folowing the article:

https://hackernoon.com/how-to-handle-kubernetes-secrets-with-argocd-and-sops-r92d3wt1

# Tools added to the image

| Tool  | Small description|
|-------|------------------|
| [SOPS](https://github.com/mozilla/sops) | Secret management using PGP  |
| [Helm Secrets](https://github.com/zendesk/helm-secrets ) | allow helm to use secrets, in our case from SOPS |


