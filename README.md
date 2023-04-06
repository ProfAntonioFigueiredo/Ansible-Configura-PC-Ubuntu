## Workstation Tools
This repository contains scripts to automate and speedup the workflow and preparation for my machine.

Disclaimer :
Those scripts are ubuntu related with major version 18+, for other distributions you'll need to adapt it

## Prepare Workstation

Read the myplaybook.yml file before applying and be sure to understand everything that will be done.

1 ) Install Ansible
sudo apt update && sudo apt install ansible unzip git -y

2 )Clone this repository
git clone https://github.com/ProfAntonioFigueiredo/Ansible-Configura-PC-Ubuntu.git

3 ) Apply the configuration
ansible-playbook Ansible-Configura-PC-Ubuntu/myplaybook.yml --ask-become-pass


Type your password when asked to give root permissions for some actions.
