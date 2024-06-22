# First Depi Project 

simple ansible Project 
Installation

## Instructions on how to install the project.

## 1: Clone the repository
git clone https://github.com/Ahmed-Moourad/simple-nodejs-app

## 2: Install dependencies
 bash
apt update
apt install ansible

## 3: Config your hosts file 
 Write the server IP & key's information. 

## 4: Config your playbook.yaml file 
 Write the playbook configuration 

## 5: Push the configuration to the server 
by using the command 
``` bash
sudo ansible-playbook -i hosts your-playbook-file-name
```
### Important note: If you face a big red error, reinstall Ansible by using the pip command. ###

```bash
pip install ansible
```

## 6: Additional Resources
For more information and resources on Ansible, you can refer to the following links:

- [Ansible Documentation](https://docs.ansible.com/)
- [Ansible Galaxy](https://galaxy.ansible.com/)
- [Ansible GitHub Repository](https://github.com/ansible/ansible)

These resources will provide you with comprehensive documentation, pre-built roles, and access to the Ansible community.

Happy automating!