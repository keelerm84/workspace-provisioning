# Workspaces Provision Script

This repository contains the ansible playbooks required to provision the
various servers that I work on.

## Setup

In order to use this repository, you can first must have ansible installed.

    pip install ansible

Once this is installed, you can install the third-party ansible roles using

    ansible-galaxy install -r requirements.txt

## Provisioning

Provisioning the servers is as easy as:

    ansible-playbook server-configuration.yml
