# 🎓 College-Network-final-project Practice

This project is a full university network simulation designed using Cisco Packet Tracer as a training task.  
It includes real-world elements such as routing, VLANs, Telnet configuration, static & dynamic routing protocols, and secured CLI access – all based on practical lab knowledge.

---

## 🏫 Project Overview

The network simulates four university buildings:

1. CS (Computer Science)
2. Engineering
3. Medicine
4. Administration

Each building includes:
- A router with a unique IP address (based on student ID logic)
- A configured switch with Telnet access
- Multiple PCs for testing
- Custom routing tables and RIP/static routing
- CLI configuration with password protection

All configurations are supported with screenshots inside the Documentation folder.

---

## 🧠 IP Address Scheme (Based on ID ending in 192)

Each router and subnet are assigned using the last 3 digits of the student ID:  
> 192

| Building       | IP Address       | Subnet Mask           |
|----------------|------------------|------------------------|
| CS             | 192.168.1.92     | 255.255.255.224        |
| Engineering    | 192.168.5.92     | 255.255.255.224        |
| Medicine       | 192.168.6.92     | 255.255.255.224        |
| Administration | 192.168.7.92     | 255.255.255.224        |

---

## 🔐 Security Configurations

- Router passwords are set and documented in CLI screenshots.
- Telnet access is configured on all switches to simulate remote admin access.
- Static routing and RIP v2 routing used based on the network segment.
- Each building has an isolated and logically segmented setup.

---

## 📁 Documentation Included

Inside the Documentation folder you will find:

- VLAN configurations for each building  
- Telnet configurations for switches  
- CLI screenshots of each router's routing table
- Commands used for RIP and static routing  
- IP plan justification based on student ID  

All screenshots are taken directly from Packet Tracer and CLI.

---

## ⚙️ Tools Used

- 🛠 Cisco Packet Tracer
- 🖥 IPv4 Subnetting
- 🧩 VLAN Configuration
- 🔁 RIP v2 Protocol
- 📶 Static Routing
- 🛡 Telnet + Password Security
- 🧪 Ping testing and full end-to-end connectivity

---

## 🎯 Purpose

This project was created for educational purposes as part of a university networking course.  
It demonstrates:
- Proper IP planning and subnetting  
- Hands-on configuration of Cisco devices  
- Security implementation  
- Real-world simulation skills

---

## 🧾 Notes

- This project was built and tested fully.
- All devices are pingable.
- All routing tables are configured manually or via RIP and shown in screenshots.

---
