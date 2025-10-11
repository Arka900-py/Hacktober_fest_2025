

#  AI-Assisted PostgreSQL Automation with Ansible + Gradient AI


##  Overview
This project integrates **Gradient AI (by DigitalOcean)** with **Ansible playbooks** for automating PostgreSQL installation and replication setup.

It uses AI to **analyze existing playbooks** and **suggest improvements** in performance, syntax, and best practices.

---

##  Features
- AI-based code review of Ansible playbooks
- PostgreSQL installation and replication automation
- Written for Rocky Linux / RHEL
- Ideal for Hacktoberfest open-source contributions

---

##  Usage

###  Install dependencies
```bash
Ansible latest and Greatest
Python latest
ansible-playbook -i inventory.ini install_postgresql.yaml
ansible-playbook -i inventory.ini setup_replication.yaml
