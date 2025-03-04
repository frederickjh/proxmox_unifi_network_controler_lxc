## Unifi Network Controller in Proxmox LXC container

This is a fork of project [whiskerz007](https://github.com/whiskerz007/proxmox_portainer_lxc) and use the this of [Glenn](https://community.ui.com/questions/ccbc7530-dd61-40a7-82ec-22b17f027776)

Many benefits can be gained by using a LXC container compared to a VM. The resources needed to run a LXC container are less than running a VM. Modifing the resouces assigned to the LXC container can be done without having to reboot the container. Packages that are installed to not interfere with the Proxmox OS.
Usage

***Note:*** _Before using this repo, make sure Proxmox is up to date._

To create a new LXC container on Proxmox and setup Portainer to run inside of it, run the following in a SSH connection or the Proxmox web shell.

```
bash -c "$(wget -qLO - https://github.com/frederickjh/proxmox_unifi_network_controler_lxc/raw/main/create_container.sh)"
```

## Console

There is no login required to access the console from the Proxmox web UI. If you are presented with a blank screen, press CTRL + C to generate a prompt.

