# home-lab
# Home Lab: Ubuntu Server VM

A personal home lab running on a virtual machine with Ubuntu Server, hosted alongside Windows. It provides cloud storage, a Minecraft server, and temporary web hosting for a friend's website.

## Services Hosted

- **Cloud Storage** – Self‑hosted file sync and access from anywhere  
- **Minecraft Server** – Java edition server for friends and personal use  
- **Web Hosting** – Hosted a friend's website for about 2 months  

## Technologies Used

- Virtualization: VirtualBox / VMware  
- Operating System: Ubuntu Server (LTS)  
- Cloud Storage: Nextcloud  
- Minecraft: Vanilla / PaperMC  
- Web Server: Nginx or Apache  
- Remote Access: SSH, Port Forwarding, Dynamic DNS  

## Setup Overview

1. Installed Ubuntu Server in a virtual machine on a Windows host  
2. Configured SSH for remote administration  
3. Installed and configured Nextcloud for cloud storage  
4. Set up a Minecraft server with basic plugins  
5. Deployed a simple website using Nginx and PHP  
6. Configured router port forwarding and dynamic DNS  

## What I Learned

- Linux server administration (package management, systemd, permissions)  
- Virtual machine creation and resource allocation  
- Network configuration, port forwarding, and firewall rules  
- Installing and securing self‑hosted web applications  
- Managing game servers and troubleshooting connectivity  
- Long‑term uptime and basic maintenance  

## Future Improvements

- Add automatic backups for all services  
- Implement monitoring with Grafana and Prometheus  
- Use Docker for easier service management  
- Set up HTTPS with Let's Encrypt and a reverse proxy  
- Migrate to Proxmox for advanced virtualization  

## Disclaimer

This project was built for learning and personal use. All services were used in a home environment and are not intended for production.
