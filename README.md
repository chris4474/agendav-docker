# Agendav-docker

This project generates an agendav 3.3.1 docker image. 

# Best used with Ansible Playbook
This docker image works best with the following ansible playbook https://github.com/chris4474/agendav-playbooks.

All you have to do before using this playbook is to populate a file which contains passwords and run the playbook. The playbook creates a docker compose file. The docker compose file is then used to deploy  agendav, baikal and a mariadb engine with the databses needed by baikal and agendav.

# Credits
All the credits for the agendav Dockerfiles goes to https://github.com/nagimov. I only adapted it to load agendav 3.3.1 and work with mariadb.
