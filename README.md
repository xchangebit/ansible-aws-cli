# ansible-aws-cli
Ansible Playbook: Install AWS CLI
Install Amazon AWS Command Line Interface to an Ubuntu server.

## Configure
Set your AWS credentials in `vars/main.yml`

## Run
### Test Run
ansible-playbook playbook.yml --check

### Execute
ansible-playbook playbook.yml --check




* Make sure the user that ansible becomes has permissions to modify /usr/bin*