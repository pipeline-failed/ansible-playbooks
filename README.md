# ansible-playbooks

This repository contains Ansible playbooks for automating the setup and configuration of various services that I frequently use. It helps maintain consistent configuration across different environments.

## Available Services and Scripts

| Service/Script | Description | Location |
|----------------|-------------|-----------|
| NGINX Installation | Automated installation and basic configuration of NGINX web server | `playbooks/install/nginx.yaml` |
| Docker Installation | Automated installation and configuration of Docker | `playbooks/install/docker.yaml` |
| K3s Master Setup | Installation and configuration of K3s master node | `playbooks/install/k3s.master.yaml` |
| K8s Environment Secret | Setup Kubernetes environment secrets | `playbooks/setup/k8s-env-secret.yaml` |
| K8s Docker Registry Secret | Configure Docker registry secrets in Kubernetes | `playbooks/setup/k8s-docker-registry-secret.yaml` |
| K8s ArgoCD Repository Secret | Configure ArgoCD repository secrets | `playbooks/setup/k8s-argo-repo-secret.yaml` |
| ArgoCD Setup | Setup and configuration of ArgoCD | `playbooks/setup/argocd.yaml` |

## Project Structure
- `playbooks/` - Directory containing all Ansible playbooks
  - `install/` - Installation playbooks for various services
  - `setup/` - Configuration and setup playbooks for Kubernetes and ArgoCD
- `inventories/` - Contains inventory files for different environments
- `group_vars/` - Directory for group variables (currently empty)
- `Vagrantfile` - Configuration for local development using Vagrant

## Usage
To use these playbooks, make sure you have Ansible installed and configure your inventory files accordingly.

Feel free to contribute or modify these playbooks according to your needs.