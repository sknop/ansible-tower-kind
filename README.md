# ansible-tower-kind
Ansible Tower (AWS) deployed in kind (k8s)

Run 

  kind create cluster -f kind.config
  kustomize .
  kubectl apply -f ingress.yml
  
 
