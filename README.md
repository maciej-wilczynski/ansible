# ansible

## Installation
```bash
sudo apt update && apt -y upgrade
sudo apt -y install ansible git
echo PASSWORD > /root/.vault_pass
ansible-pull -U git://github.com/maciej-wilczynski/ansible.git init.yml
```
