# Automated Multi-Server Configuration

## Overview

This project showcases the use of Ansible to automate the installation of software and the management of configuration files on multiple Ubuntu servers hosted on VirtualBox. The automation process leverages SSH keys for secure and password-less authentication, streamlining the server setup and configuration.

## Technologies Used

- **Ansible**: For automation of server setup and configuration.
- **Linux/Unix (Ubuntu Server)**: Operating system used for the servers.
- **Shell**: For scripting and command-line operations.
- **SSH**: For secure and password-less communication between the control machine and the servers.
- **VirtualBox**: To host the virtual servers.
- **Automation**: To minimize manual intervention and enhance efficiency.

## Project Features

- **Ansible Playbooks and Roles**: Designed and implemented to streamline the setup and configuration of the servers.
- **Automated Software Installation**: Ensures consistent and efficient installation of required software across all servers.
- **Configuration File Management**: Automated management of configuration files to maintain uniformity and correctness.
- **Secure Orchestration**: Utilizes SSH keys to manage and orchestrate tasks securely across multiple virtual machines.

## Usage
```
ansible-playbook --ask-become-pass [playbook.yml] # run custom playbook
```
- install_packages.yml install predetermined applications. 
- remove_packages.yml removed installed appplications.
- target_install.yml install diff applications on diff server.
