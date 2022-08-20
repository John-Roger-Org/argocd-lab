# argocd-lab
test argocd 

# copy application.yaml, service.yaml to k8s master node 

# generate a github token, and then login k8s master node: 
  export GITHUB_TOKEN = <token>
  kubectl apply -f secert.yaml
  kubectl apply -f application.yaml

# if the token fail to authenticate, login argocd UI to configure the private repo authentication using the same token.  