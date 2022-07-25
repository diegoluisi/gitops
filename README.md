# gitops
ArgoCD Autopilot Repo

## Kind:
kind create cluster --name gitops

## argocd-autopilot
export GITHUB_ACCESS_TOKEN='XXXXX'
export GIT_REPO=https://github.com/diegoluisi/gitops
argocd-autopilot repo bootstrap --recover
