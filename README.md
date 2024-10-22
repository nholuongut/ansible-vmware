# Stone Payments - Ansible VMware
![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

This repository contains a role for create, delete or to manage a Virtual Machine (VM) using VMware vSphere vCenter

## Prerequisites
* [PyVmoni](https://pypi.python.org/pypi/pyvmomi/) is the Python SDK for the VMware vSphere API that allows you to manage ESX, ESXi, and vCenter.

### Install PyVmoni
The official release is available using epel, just run `yum install python2-pyvmomi`

## Role Variables
Look the file [`defaults/main.yml`](defaults/main.yml)

## Example Playbook
```yaml
---
- hosts: localhost
  gather_facts: false
  vars_prompt:
    - name: "vmware_vcenter_username"
      prompt: "Enter your vCenter username"
      private: no

    - name: "vmware_vcenter_password"
      prompt: "Enter your vCenter password"
      private: yes
  roles:
    - role: stone-payments.ansible-vmware
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
