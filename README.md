# Ansible OpenVPN role

This Ansible role will install the OpenVPN server from the main Ubuntu
repository. The role is tested and designed for use on Ubuntu 16.04.

## Installation

```
cd roles

git clone https://github.com/Kumiko/ansible-openvpn openvpn
```

## Usage

Include the role in your playbook:

```
- hosts: your_openvpn_hosts
  roles:
    - name: openvpn
```

