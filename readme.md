It's role for install grafana from specefic repo
Before start you need to specify variables in vars/main.yml and upload ssh-key to target server
---
Example start:
ansible-playbook -i hosts grafana.yml -v