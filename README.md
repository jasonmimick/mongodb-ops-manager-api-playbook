mongodb-ops-manager-api-playbook

This repository contains an Ansible Playbook
for interacting with the MongoDB Ops Manager
REST API.

It's meant to be consumed by other playbooks
which need to coordinate with MongoDB Ops Manager.

Injectable configuration parameters are found in
roles/defaults/main.yaml

The MongoDB Ops Manager Organization context is
set according to the api key & user used to 
authenticate to MongoDB Ops Manager.

Features:

Create a project (group) by name if it doesn't exist.
Add a standalong node to a project.
Add a replica set to a project.
Add a sharded cluster to a project.
?Alerts?
Apply backup configuration from an existing project to another.


