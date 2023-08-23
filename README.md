# Ansible Leapp Collection

## Overview

This collection provides Ansible roles you can use to perform RHEL in-place upgrades using the Leapp framework. Successfully executing upgrades at scale across a large RHEL estate demands a customized end-to-end automation approach tailored to meet the requirements of your enterprise environment. Use these roles as the foundation of your RHEL in-place upgrade automation solution.

## Roles

These are the roles included in the collection. Follow the links below to see the detailed documentation and example playbooks for each role.

- [`analysis`](./roles/analysis/) - executes the Leapp pre-upgrade phase
- [`common`](./roles/common/) - used for local logging, mutex locking, and common vars
- [`parse_leapp_report`](./roles/parse_leapp_report/) - reads pre-upgrade results and checks for inhibitors
- [`upgrade`](./roles/upgrade/) - executes the Leapp OS upgrade

## Playbooks

Playbooks can be found [here](./playbooks/).