# Prometheus with Grafana using Ansible

All versions up to date as of 01/09/2022

In this project, we are configurating prometheus, node_exporter, alertmanager and Grafana. We setup Grafana dashboard which can use source as Prometheus.

## Getting Started

Step 1: Update ip address of instances in inventory file.

Step 2: Run ansible command to setup prometheus, node_exporter, alertmanager and Grafana services

Ansible command: ansible-playbook playbook.yml -i inventory
