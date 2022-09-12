# Hosts inventory

#### The task: create a playbook that performs an inventory of hosts and uploading information to a file /var/tmp/host.info
#### The template looks like:

```yaml
HOSTNAME:
OS:
KERNEL:
IPv4: 
IPv6: 
SYSTEMCTL: 
name:  status:
CPU:
cores:
threads per core: 
RAM: 
total 
free 
used  
HDD:
name: 
        partition:
        sectors:
        sectorsize: 
        size: 
        uuid: 

MOUNTS:
mount
        mount_path:
        device:
        options:
        size_available:
        size_total: 
        uuid:
PORTS:
__TCP:
__UDP:
USER_WITH_SHELL: 
CRON_JOBS:
```
