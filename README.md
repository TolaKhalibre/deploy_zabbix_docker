# Zabbix Server && Zabbix agent 2
* Zabbix Server Deploy in docker compose
* Zabbox Agent 2 automate installing using Ansible in your machine \
> <code style="color : Gold">[!IMPORTANT]</code> **Currently, Zabbix-agent2 installation which we focus on ubuntu only.**
#
## Deploy Zabbix Server using docker compose
* to deploy Zabbix Server using docker compose you have to run the command below:

  ```
    docker compose up -d
  ```
## Installation Zabbix-agent 2 using Ansible
* plz run the command below:

  ```
    ansible-playbook ansible/playbook.yml
  ```
#
## Unstallation Zabbix-agent 2 using Ansible
> <code style="color : RED">[!NOTE]</code> Inprogress
