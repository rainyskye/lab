# lab - Simple Automated Homelab Setup

> Please note this is still *very* in progress, things may change at any time and new services may be added or removed, the structure also may change at any time, therefore there may be breaking changes, if you're using the `main` branch, expect *something* to break at some point.

### Requirements:
- x86 PC/Laptop *(ARM support will be certified in the future)*
  - Depending on the services you want to run, your requirements will change, a relatively modern 2/4 Core CPU, 8GB of RAM and an SSD for Boot/Services is recommended.
  - Using a Laptop can work, but you may have to manually take some steps to ensure that closing the lid won't suspend the machine, etc.
- Ubuntu Server 22.04 LTS
  - Support may be added for other distributions (Fedora Server, Debian, etc.), but it isn't planned at this time.

### Services: (Services with a strikethrough are yet to be added, but are planned.)
- Traefik (Reverse Proxy)
- Vaultwarden (Bitwarden Server written in Rust)
> If you want a service that isn't listed here, feel free to open an issue or submit a PR adding it!

### How to Configure/Setup:
*to-do*
include: disabling services, any required config, updating/maintenance
ansible-galaxy collection install community.docker

### Planned Features/Services to be added
 - [x] Fully Automated Installation and Setup
 - [x] Traefik (Reverse Proxy) 
 - [ ] Homer (Dashboard)
 - [x] Vaultwarden (Bitwarden Server written in Rust)

### Thanks to:
- Jeff Geerling - My first introduction to Ansible [[Book - Ansible for DevOps](https://www.ansiblefordevops.com/), [Github](https://github.com/geerlingguy), [YouTube](https://www.youtube.com/c/JeffGeerling)]