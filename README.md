# Ansible Role: b4syk

## Introduction
Welcome to the **Ansible Role: b4syk**! 🎉 This role is your go-to solution for setting up and configuring servers with ease, across various Linux distributions and flavors. Whether you’re working with Debian-based systems like Ubuntu and Raspberry Pi OS, or Red Hat-based systems like CentOS, AlmaLinux, and traditional Debian or Red Hat, this role has got you covered! 🚀

## Features
- Seamless support for **Debian** and **Red Hat** distributions
- Versatile compatibility with **Ubuntu**, **Debian**, **Raspberry Pi OS**, **AlmaLinux**, and **CentOS**
- Streamlined setup for server basics, ensuring a smooth and hassle-free configuration experience

Elevate your server management game and embrace efficient, reliable, and consistent configurations with this role. Happy configuring! 😄🔧


## Requirements
### Ansible Collections
- ansible.posix
- community.general

### Other Requirements
- Root access, so either run it in a playbook with a global become: true.
- Include the role in your playbook and run it using the correct --tags for each task you want to perform.

## Tags

| **Tags**              | **Description**                                          |
|-----------------------|----------------------------------------------------------|
| `b4syk`               | Full Role                                                |
| `b4syk_packages`      | Manages essential packages for the server                |
| `b4syk_shell`         | Configures shell settings and environment                |
| `b4syk_vim`           | Sets up Vim editor with preferred configurations         |
| `b4syk_sshd`          | Configures SSH daemon settings                           |
| `b4syk_ssh_pubkeys`   | Manages SSH public keys for secure access                |
| `b4syk_tmux`          | Installs and configures tmux terminal multiplexer        |
| `b4syk_timezone`      | Sets the correct timezone on the server                  |
| `b4syk_docker`        | Installs and configures Docker                           |
