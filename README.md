# ansible-proxmox
Ansible to setup and maintain proxmox instances

### Variables
| Name     | Default | Description |
|----------|-----|--------|
| wol    | True  | Provided WOL is enabled in the BIOS, this variable will allow WOL |
| enterprise      | False  |  If False, the proxmox enterprise sources will be commented out in `/etc/apt/sources.d/`  |
