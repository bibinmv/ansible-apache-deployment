# Ansible Apache Deployment

## 📌 Project Overview
This project automates the installation and configuration of Apache (httpd) on RHEL systems using Ansible.

## 🛠 Technologies Used
- RHEL 8/9
- Ansible
- YAML
- SSH

## 📂 Project Structure
- inventory – Defines managed hosts
- playbook.yml – Ansible playbook for Apache deployment

## ▶️ How to Run

```bash
ansible-playbook -i inventory playbook.yml
