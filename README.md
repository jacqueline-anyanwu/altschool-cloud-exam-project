# altschool-cloud-exam-project
AWS cloud deployment with Ansible automation

## Description
This project deploys a load-balanced web application on AWS using Ansible automation.

## Architecture
- 2 EC2 instances running Ubuntu with NGINX
- Application Load Balancer distributing traffic
- Automated deployment using Ansible
- S3 static website for comparison

## Technologies Used
- AWS (EC2, ALB, S3)
- Ansible
- NGINX
- Ubuntu Linux

## Files
- `host-inventory.ini` - Ansible inventory file listing EC2 instances
- `deploy.yml` - Ansible playbook for deploying NGINX
- `index.html` - HTML template deployed to servers

## How to Use
1. Update `host-inventory.ini` with your EC2 instance IPs and SSH key path
2. Ensure your SSH key has correct permissions (chmod 400)
3. Run: `ansible-playbook -i host-inventory.ini deploy.yml`

## Author
Jacqueline Anyanwu

## Medium Article
[Link will be added after publication]
