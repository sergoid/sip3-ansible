# Ansible scripts to configure and install SIP3 

`sip3-ansible` project aims to provide an easy way to configure and install SIP3 components. If you are not familiar with SIP3 architecture checkout [this page](https://sip3.io/features).

## 1. Prerequsites

Before starting with `sip3-ansible` make sure that you have installed:

* [Docker](https://docs.docker.com/install/)
* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## 2. Playbooks

SIP3 is a multi-components project. That's why `sip3-ansbile` suggests you different playbooks with different component configuration according to your VoIP network size, infrastructure requirements and other needs:

* [Trial](playbooks/trial) - Showcase version of SIP3. Run it as a monolitic application with just a few commands. Keep in mind that this version has restrictions in terms of performance and available features.

## 3. License

This project is available under the Apache License 2.0

## 4. Support

If you have a question about SIP3, please contact us at [Gitter](https://gitter.im/SIP3-Community/community) or reach us by [email](mailto:support@sip3.io). We are always ready to help you.