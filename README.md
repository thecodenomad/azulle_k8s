# K8s on Azulle Access 3 Mini-PC

This project is meant to suppliment a blog post around setting up a cluster of Azulle Access 3 Mini PCs.

#### Software Required

Ansible >= 2.7
Debian 9.6

#### Hardware Required
* 1x 5 port gigabit ethernet switch
* 3x Ethernet cables
* 3x Azulle Access 3 Mini-PCs (or similar) with Debian 9.6+ installed
* 3x Micro USB Power

### Playbooks

dungeon.yml - This is used to establish the cluster for kubernetes

gluster.yml - This is used to establish an optional GlusterFS setup on worker nodes
