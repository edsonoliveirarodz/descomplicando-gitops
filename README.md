# descomplicando-gitops
Descomplicando GitOps LinuxTips

# instalando o ArgoCD
1. Criação de namespace "argocd"
2. Execução do comando abaixo:
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
3. Validar a instalação:
kubectl get pods -n argocd

# Logando no Argo
1. Acessar o serviço "argocd-server"
2. Pegar a senha na secret do ArgoCD criada "argocd-initial-admin-secret"
User: admin
Pass: <SENHA_DESCRIPTOGRAFADA>

# Repositório de aplicações de teste
https://github.com/argoproj/argocd-example-apps



Repositório no Github: https://github.com/bernardolsp/descomplicando-gitops-no-kubernetes-argocd/

Links úteis:
- Getting Started (https://argo-cd.readthedocs.io/en/stable/getting_started/)