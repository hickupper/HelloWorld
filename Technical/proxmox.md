# 🖥️ Proxmox Host Server - LXC Container Tracker

## 🧾 Host Information
- **Hostname**:  
- **IP Address**:  10.10.2.30:8006
- **Location**:  
- **Proxmox Version**:  
- **CPU Model**:  
- **CPU Cores / Threads**:  
- **Total RAM**:  
- **Total Storage**:  
- **ZFS/LVM Used**:  
- **Node Role (Cluster/Standalone)**:  
- **Admin Contact**:  

---

## 📦 LXC Container Summary

| CT ID | Hostname | IP Address | OS Template | CPU | RAM | Disk | Status | Notes |
|-------|----------|------------|-------------|-----|-----|------|--------|-------|
| 100   | web01     | 192.168.1.100 | debian-12   | 2   | 2GB | 20GB | Running | Web Server |
| 101   | pihole    | 192.168.1.101 | ubuntu-22.04| 1   | 512MB| 5GB  | Stopped | DNS Filter |
| 102   | media     | 192.168.1.102 | alpine-3.18 | 1   | 1GB | 15GB | Running | Jellyfin |

> 🔄 _Update this table whenever a container is added, removed, or modified._

---

## 🔍 Resource Allocation Overview

- **Total Containers**:  
- **Total Allocated RAM**:  
- **Total Allocated Disk**:  
- **Available Resources**:  

---

## ⚙️ Networking

- **Primary Bridge (vmbr0)**:  
- **Secondary Interfaces**:  
- **Firewall Rules Summary**:  
- **NAT / Port Forwarding Notes**:  

---

## 🔐 Access & Security

- **Root Login via SSH**: ☐ Enabled ☐ Disabled  
- **Admin Users**:  
- **SSH Keys Stored At**:  
- **Firewall Enabled**: ☐ Yes ☐ No  
- **2FA for Web UI**: ☐ Yes ☐ No  

---

## 🧰 Maintenance Log

| Date       | Action                       | Performed By | Notes |
|------------|------------------------------|--------------|-------|
| 2025-06-01 | Updated Proxmox to 8.2.3     | Larry        | Post-reboot required |
| 2025-06-10 | Added CT 102 (media)         | Larry        | Media streaming |
| 2025-06-20 | Increased host RAM to 32GB   | Larry        | Hardware upgrade |

---

## 📁 Backups & Snapshots

- **Backup Schedule**:  
- **Retention Policy**:  
- **Snapshot Enabled for CTs**: ☐ Yes ☐ No  
- **External Backup Location**:  

---

## 📝 Additional Notes

- **Custom Hook Scripts**:  
- **System Alerts / Monitoring Tools**:  
- **Future Upgrade Plans**:  

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTM3OTE4OTM3OV19
-->