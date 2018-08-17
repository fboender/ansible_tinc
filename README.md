# Tinc Ansible role

This is a role to install Tinc with Ansible.

tinc is a meshing Virtual Private Network (VPN) daemon that uses tunnelling
and encryption to create a secure private network between hosts on the
Internet.

**This role works on**:

- Ubuntu 14.04
- Ubuntu 16.04
- Ubuntu 18.04

**It does the following**:

- Install and configure Tinc on each host
- Distributes the tinc hosts files to each host
- Adds entries for each host in `/etc/hosts`

**Shortcomings**:

- Only supports one tinc network.

**Notes**:

I do not provide support for this repo.
