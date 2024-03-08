---
abstract: The readme for some Ansible playbooks that have the goal of deploying
    a Root Certificate Authority to a Linux host.
authors: Xander Harris
date: 2024-03-08
title: Ansible Root CA
---

## Assumptions

The default configuration assumes a vault password exists at
{file}`/etc/ansible/vault`. It also assumes the inventory file is in YAML format
and located at {file}`/etc/ansible/hosts.yaml`

## Fact Caching

The default configuration uses fact caching with Redis running on the controller
with the default port.
