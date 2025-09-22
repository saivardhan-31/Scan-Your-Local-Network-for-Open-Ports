# Scan-Your-Local-Network-for-Open-Ports

This repository contains the results of a network scan performed using **Nmap 7.98**.  
The target system scanned was: **192.168.56.1**

## 🖥 Host Information
- **Status:** Host is up
- **OS Detected:** Likely Microsoft Windows (10 / 11 / Server 2022)
- **Uptime Guess:** ~4.5 days

## 📡 Open Ports and Services
| Port  | State | Service        | Version                       |
|-------|-------|----------------|-------------------------------|
| 135/tcp | open  | msrpc          | Microsoft Windows RPC         |
| 139/tcp | open  | netbios-ssn    | Microsoft Windows NetBIOS-SSN |
| 445/tcp | open  | microsoft-ds   | SMB (message signing enabled) |
| 3306/tcp| open  | mysql          | MySQL (unauthorized)          |

## 📜 Notes
- SMB signing enabled but **not required** (potential risk).
- MySQL service is exposed but does not allow unauthorized access.
- OS detection suggests **Windows 10/11 family**.

---

