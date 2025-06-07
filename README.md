# ansible-playbooks

This repository contains Ansible playbooks for automating the setup and configuration of various services that I frequently use. It helps maintain consistent configuration across different environments.

## Available Services and Scripts

| Service/Script | Description | Location |
|----------------|-------------|-----------|
| NGINX Installation | Automated installation and basic configuration of NGINX web server | `playbooks/install-nginx.yaml` |

## Project Structure
- `playbooks/` - Directory containing all Ansible playbooks
- `inventories/` - Contains inventory files for different environments
- `Vagrantfile` - Configuration for local development using Vagrant

## Usage
To use these playbooks, make sure you have Ansible installed and configure your inventory files accordingly.

Feel free to contribute or modify these playbooks according to your needs.