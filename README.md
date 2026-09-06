"# complete-devops-project"
to get password of argocd admin : $ kubectl get secret argocd-initial-admin-secret -n argocd -o jsonpath="{.data.password}" | base64 -d
