# Ansible playbooks for OpenVDMv2

## Open Vessel Data Management
- https://github.com/webbpinner/OpenVDMv2
- http://www.oceandatarat.org/?page_id=1123

## Ansible
- https://www.ansible.com/

## Vagrant
- https://www.vagrantup.com

This repository contains an ansible playbook to set up OpenVDMv2 from scratch on an ubuntu 16.04 machine.  The playbook follows the instructions for installing OpenVDMv2 from that repos's [INSTALL.md](https://github.com/webbpinner/OpenVDMv2/blob/v2.3/INSTALL.md) and uses the same settings as the example (e.g. directories on `/var/FTPRoot`, served on `http://localhost/OpenVDMv2`, default `admin/demo` login, etc.)

This playbook can be combined with the provided [Vagrantfile](Vagrantfile) to create an OpenVDMv2 virtual machine with one command:

```
vagrant up
```