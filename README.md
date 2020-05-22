# storage-lab-setup

# Use VMware workstation
* setup network.
* VM -> newtork -> host-only,   you will get 192.168. IP.
  * Note: if you have to install pkg to Ubuntu, may need set NAT network firstly to install required package.
* Use ubuntu


# Ubtuntu OS info
* `Linux ubuntu 5.3.0-28-generic #30~18.04.1-Ubuntu SMP Fri Jan 17 06:14:09 UTC 2020 x86_64 x86_64 x86_64 GNU/Linux`
## Goal
* NFS server and client
* iscsi server and client

## NFS
### References
* https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nfs-mount-on-ubuntu-18-04
* https://help.ubuntu.com/community/SettingUpNFSHowTo
### Nodes in my network
* node-storage-server
* node-storage-client-a
* node-storage-client-b
