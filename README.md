# Home Lab – Proxmox + Docker + VLAN + VPN

This repository documents my personal Home Lab, built to explore virtualization, containerization, networking, and system hardening. The environment runs on a low-power HP mini PC with 16 GB RAM, hosting multiple services using Proxmox, Linux, and Docker.

---

## 🧱 Architecture Overview

- Proxmox as the main hypervisor  
- Linux Server VM hosting all containers  
- Docker + Portainer for orchestration  
- VLANs for network segmentation  
- AdGuard Home + Pi-hole for DNS filtering  
- WireGuard/OpenVPN for secure remote access  
- Samba/NFS for file sharing  
- rsync for automated backups  

---

## 🛠️ Technologies Used

- Proxmox  
- Docker  
- Portainer  
- Debian/Ubuntu Server  
- VLAN  
- WireGuard / OpenVPN  
- AdGuard Home  
- Pi-hole  
- Samba / NFS  
- rsync  
- Bash  
- Git  

---

## 🚀 Services Deployed

### **Jellyfin**  
Media server for local streaming.

### **Nextcloud**  
Personal cloud for files, contacts, and notes.

### **AdGuard Home**  
DNS filtering, ad blocking, and privacy protection.

### **Pi-hole**  
DNS sinkhole for redundancy and enhanced filtering.

### **Samba / NFS**  
File sharing across devices.

---

## ⚙️ Key Configurations

### **Proxmox**
- Installed on HP mini PC  
- Created VMs and LXC containers  
- Configured local storage  
- Enabled snapshots and internal backups  

### **Docker + Portainer**
- Installed Docker Engine  
- Deployed containers via Portainer  
- Organized services into stacks  
- Monitored container health and uptime  

### **Networking**
- Created and managed VLANs  
- Configured DNS filtering with AdGuard Home  
- Set up DHCP and DNS on the server  
- Enabled VPN for secure remote access  

### **Backups**
- Automated with `rsync`  
- Scheduled via cron  
- Backed up configs and container volumes  

---

## 📚 What I Learned

- Virtualization with Proxmox  
- Container management with Docker  
- Networking fundamentals (VLAN, DNS, DHCP, TCP/IP)  
- Security practices (VPN, hardening, DNS filtering)  
- Linux system administration  
- Backup automation and scripting  

---

## 🔮 Next Steps

- Implement monitoring with Grafana + Prometheus  
- Create Bash automation scripts  
- Expand Proxmox cluster for high availability  
- Document each service in separate folders  

---

## 📸 Screenshots 

Create a folder `/images` and include screenshots such as:

- Proxmox dashboard  
- Portainer interface  
- Jellyfin media library  
- Nextcloud file view  
- AdGuard Home stats  
- Pi-hole dashboard  
- VLAN setup on router  
- `docker ps` terminal output  

Embed them like this:

```markdown
![Proxmox Dashboard](images/proxmox.png)
