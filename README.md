# dcos-ansible - Ansible Playbook for Mesosphere DC/OS
## Overview
dcos-ansible is a lightweight Ansible Playbook which will quickly provision DC/OS on any infrastructure.

## Compatibility
### Ansible
The playbook has been tested using Ansible 2.3.0 though it should be backwards compatible to support a minimum version of 2.1.0.
### Operating System
dcos-ansible has been tested on CentOS 7.3. It should also be compatible with RHEL 7.3.

It does not support Ubuntu or any other Debian-based operating systems yet, though this will change in the future.
### Mesosphere DC/OS
The playbook will download and install the latest stable release of DC/OS. It has been tested with DC/OS 1.9 as that is the latest version as of the lastest submission.
### Docker
dcos-ansible uses the latest DC/OS-supported version of Docker, 1.13.1.
