# ubuntu-KVM

Install KVM on Ubuntu 20.04 Server. This installation uses Cockpit to create and manage virtual machines.

## Requirements

- Host running  Ubuntu 20.04 Server
- Install pipenv using pip
- Must have Python 3.8 or greater

## How to Use

Update the `host` file with proper ip addresses and hosts which will have KVM installed on them.

To use run ansible using the Pipfile:

```
pipenv run ansible-playbook -h host playbook.yml
```
