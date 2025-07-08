# Introduction to Zabbix
Zabbix is a powerful, open-source monitoring solution for networks, servers, virtual machines, and cloud services. It is widely used by IT administrators and DevOps engineers to track the health and performance of their infrastructure in real time.
## How Zabbix Works:
* Zabbix Server: The central component that stores data and processes alerts.
* Zabbix Agent: Installed on monitored systems to send performance data to the server.
## Zabbix Server && Zabbix agent 2
* Zabbix Server Deploy in docker compose
* Zabbox Agent 2 automate installing using Ansible in your machine \
> <code style="color : Gold">[!IMPORTANT]</code> **Currently, Zabbix-agent2 installation which we focus on ubuntu only.**
#
## Deploy Zabbix Server using docker compose
### Properties
> * Python3
> * Ansible
> * collection: community.docker.docker_compose_v2
* To run docker compose using ansible please run the ansible command below:
  ```
    ansible-playbook ansible/deploy-zabbix-server.yml
  ```
  > <code style="color : Orange">[!NOTE]</code>
  > * Username: **Admin**
  > * Password: **zabbix**
## Zabbix-Agent2 installations
### Requirement
> * Python
> * Ansible
### Install Zabbix-agent 2 using Ansible
* plz run the command below:

  ```
    sudo apt update
  ```
  ```
    ansible-playbook ansible/deploy-zabbix-agent.yml
  ```
