# Automating Infrastructure using Ansible

This project automates the installation and configuration of the Nginx web server on AWS EC2 instances using Ansible.

## Features
- Installs Nginx
- Starts and enables the Nginx service
- Configures the firewall to allow HTTP traffic on port 80

## Usage
1. Clone the repository: `git clone https://github.com/afsasaleem/ansible-nginx-automation.git`
2. Set up your Ansible inventory file with your EC2 instance IP.
3. Run the Ansible playbook: `ansible-playbook -i hosts nginx-install.yml --key-file /path/to/private-key.pem`
