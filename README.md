"# complete-devops-project"
to get password of argocd admin : $ kubectl get secret argocd-initial-admin-secret -n argocd -o jsonpath="{.data.password}" | base64 -d
<img width="956" height="400" alt="image" src="https://github.com/user-attachments/assets/13372a9f-2c2c-4f59-8e9c-5392a1a44384" />
