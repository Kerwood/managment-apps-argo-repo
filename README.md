# managment-apps-argo-repo
FATA[0000] rpc error: code = Internal desc = transport: received the unexpected content-type "text/html" 

argo app create management-apps \
    --dest-namespace argocd \
    --dest-server https://kubernetes.default.svc \
    --repo https://github.com/Kerwood/managment-apps-argo-repo \
    --path argo-manifests