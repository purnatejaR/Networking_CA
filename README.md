# Networking_CA
Docker Deployment with Ansible
This repository contains files and instructions for deploying Docker containers using Ansible.

Objective

The objective of this assignment is to demonstrate the deployment of Docker containers using Ansible. The specific tasks include:
1.Deploying a Docker container running an Apache service with a static web page.
2.Configuring networking for the Docker container to allow communication with the host machine.
Prerequisites

Before running the Ansible playbook, ensure the following prerequisites are met:
1.Docker is installed on the target machine(s).
2.Ansible is installed on the control machine.
3.Proper network connectivity is established between the control machine and the target machine(s).

Repository Structure
1.sri.yml`: Ansible playbook for deploying Docker containers.
2.README.md: This file, providing an overview of the repository and instructions.

Instructions
1.Clone this repository to your local machine.
2.Modify the Ansible playbook (sri.yml) as needed, specifying the appropriate target hosts and configurations.
3.Run the Ansible playbook using the command ansible-playbook docker_deploy.yml.
4.Verify the deployment and accessibility of the Apache service from the host machine.
