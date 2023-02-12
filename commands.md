# Commands

## Description

This file contains the list of commands ran in the article [How to Use Ansible to Manage VMware Infrastructure](https://cloudhat.eu/use-ansible-manage-vmware-infrastructure/)

## Commands

Install Python 3
```
sudo dnf install python3 python3-devel
```

Install Ansible
```
pip install ansible
```

Install Ansible Community.VMware collection
```
pip install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git
```

Check Ansible version
```
ansible --version
```

Run [get-hosts-info-REST.yml](https://github.com/cghioc/cloudhat/blob/main/How-to-Use-Ansible-to-Manage-VMware-Infrastructure/get-hosts-info-REST.yml)
```
ansible-playbook get-hosts-info-REST.yml
```

Run [get-hosts-info.yml](https://github.com/cghioc/cloudhat/blob/main/How-to-Use-Ansible-to-Manage-VMware-Infrastructure/get-hosts-info.yml)
```
ansible-playbook get-hosts-info.yml
```
