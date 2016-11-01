# Ansible Role: ObserviumAgent

An Ansible role that installs [Observium UNIX Agent](http://observium.org/docs/unix_agent/) on Centos 

## Example Playbook
```sh
---
 - hosts: common
   roles:
        - { role: ObserviumAgent, when: nosnmpd is not defined }
```
## Requirements

None.

## Dependencies

None.

