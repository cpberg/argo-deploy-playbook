# Deploy Argocd to Kubernetes CLuster

## Setup

```
ansible-galaxy install -r roles/requirements.yml -f
```

## Server setup

```
ansible-playbook -b -k -K -i argocd-servers argocd.yml
```
