# Pi-hole DNS Ad Blocking Lab (Ubuntu Server + VirtualBox)

## 📌 Overview
This project demonstrates deploying a network-wide DNS ad blocker using Pi-hole on Ubuntu Server 24.04 inside VirtualBox.

The goal was to simulate a small home network DNS filtering solution while practicing Linux administration, networking.

---

## 🛠 Technologies Used
- Ubuntu Server 24.04 LTS
- VirtualBox
- Pi-hole
- Linux CLI (ip, nslookup)
- DNS fundamentals

---

## 🌐 Network Configuration
- VirtualBox Mode: NAT
- VM IP Address: 10.0.2.15
- DNS configured to: 127.0.0.1 (Pi-hole local resolver)

---

## 🚀 Installation Steps

### 1️⃣ Installed Ubuntu Server in VirtualBox
Configured basic networking and confirmed connectivity.

### 2️⃣ Installed Pi-hole
```bash
curl -sSL https://install.pi-hole.net | bash

## Screenshots
![piblock-1](piblock-1.png)
![piblock-2](piblock-2.png)


