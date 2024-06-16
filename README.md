# Networking_CA
Docker Deployment with Ansible
This repository contains files and instructions for deploying Docker containers using Ansible.

Objective

The objective of this assignment is to demonstrate the deployment of Docker containers using Ansible. The specific tasks include:

Deploying a Docker container running an Apache service with a static web page.
Configuring networking for the Docker container to allow communication with the host machine.
Prerequisites

Before running the Ansible playbook, ensure the following prerequisites are met:

Docker is installed on the target machine(s).
Ansible is installed on the control machine.
Proper network connectivity is established between the control machine and the target machine(s).
Repository Structure

sri.yml`: Ansible playbook for deploying Docker containers.
README.md: This file, providing an overview of the repository and instructions.
Instructions

Clone this repository to your local machine.
Modify the Ansible playbook (sri.yml) as needed, specifying the appropriate target hosts and configurations.
Run the Ansible playbook using the command ansible-playbook docker_deploy.yml.
Verify the deployment and accessibility of the Apache service from the host machine.
