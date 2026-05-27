# Drake's Homelab

A personal homelab built to develop real-world IT infrastructure skills.

## Hardware
- Acer Predator PH16-71 (Proxmox host)
  - 16GB RAM
  - RTX 4060
- Managed Switch
- PDU
- Console Cable

## Network
- ISP: Cincinnati Bell Fioptics
- Router: Eero
- Proxmox Host IP: 192.168.4.50

## Stack
| Service | Purpose | Status |
|---|---|---|
| Proxmox VE 8.x | Hypervisor | ✅ Running |
| pfSense | Virtual Firewall/Router | 🔜 Pending |
| Windows Server 2022 | Active Directory/DNS/DHCP | 🔜 Pending |
| Ubuntu Server | Linux VM / Domain joined | 🔜 Pending |
| Grafana + Prometheus | Monitoring | 🔜 Pending |

## Progress Log
- [x] Installed Proxmox VE bare metal
- [x] Configured static IP (192.168.4.50)
- [x] Configured remote management via web UI
- [ ] Deploy pfSense VM
- [ ] Deploy Windows Server 2022
- [ ] Deploy Ubuntu Server
- [ ] Join Ubuntu to AD domain
- [ ] Set up Grafana monitoring
- [ ] Write Ansible playbooks`