## Description

In case of having more than one interface, which needed to be captured, You should use this role to deploying sip3-captain.
You should run this this role for each interface separately with change captain.pcap parameters (dev, and optionally bpf_filter) for interfaces.
It will cretae separate directories for every interface and daemons for sip3-captain.
Daemons will look like sip3-captain-interface_dev_name and you can manage it with systemctl,
for example:

```sh
# systemctl restart sip3-captain-eth0
```

## Deploying

It means that You already cloned this project on your disk.

You can use **examples/sip3-captain-multiinterface.yml** file.
- copy this file to **inventories** directory;
- change the necessary parameters;
- run with:

```sh
$ ansible-playbook -i inventories/sip3-captain-multiinterface.yml playbooks/sip3.yml
```
