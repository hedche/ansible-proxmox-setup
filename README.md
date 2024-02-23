# ansible-proxmox
Ansible to setup and maintain proxmox instances

### Variables
| Name     | Default | Description |
|----------|-----|--------|
| wol    | True  | Provided WOL is enabled in the BIOS, this variable will allow WOL in proxmox |
| upgrade    | True  | Run a full apt update and upgrade |
| enterprise      | False  |  If False, the proxmox enterprise sources will be commented out in `/etc/apt/sources.d/`  |
| terraform      | True  |  Downloads image from variables file and sets it up for use with terraform  |