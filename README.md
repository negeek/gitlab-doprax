# Gitlab-Doprax

This repository hosts an Ansible playbook for the automated installation and configuration of GitLab on Doprax Virtual Machines (VMs). The installation process is streamlined through the Doprax VM panel, enabling users to install GitLab with just a few clicks, without manually running the playbook or setting up configurations.

## Features

- **One-Click Installation**: Deploy GitLab on your Doprax VMs through a simple and user-friendly interface.
- **Preconfigured Settings**: The playbook comes with sensible defaults, including a free subdomain, ensuring a hassle-free setup.
- **Automated Execution**: The process automates the cloning of this repository and the execution of the Ansible playbook, requiring minimal user intervention.

## How to Install GitLab on Doprax VMs

1. **Log into Your Doprax Account**:
   Access your Doprax account and navigate to your VM dashboard.

2. **Install New App**:
   In the VM panel, select the option to 'Install New App'.

3. **Select GitLab**:
   From the list of available applications, choose 'GitLab'.

4. **Click Install**:
   Simply click the 'Install' button. This action triggers the backend processes to automatically clone this repository, run the Ansible playbook, and set up GitLab with default configurations.

5. **Access Your GitLab Instance**:
   Once the installation is complete, GitLab will be accessible on the VM. You'll be provided with a free subdomain and initial access credentials.

## Default Configuration

The playbook is configured with the following default settings:

- **Domain**: A free subdomain is provided for your GitLab instance.
- **External URL**: Configured based on the provided domain.
- **Root Password**: A secure default password is set (recommended to change post-installation).

## Support and Contributions

For support, suggestions, or issues, please use the issue tracker in this repository. Contributions to improve the playbook are welcomed through pull requests.



## Disclaimer

This playbook is provided "as is". We strive for reliability, but cannot guarantee its suitability for all environments. It is recommended to familiarize yourself with the configuration and adjust as necessary for your specific needs.

