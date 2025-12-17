# small-office-network-design_CCNA_-Project-_lab_02
<!--  ██████  ██████  ███    ██  █████  -->

<!--  CCNA NETWORKING PROJECT README   -->

<h1 align="center">🚀 CCNA Networking Project</h1>

<p align="center">
  <b>Designed Using Cisco Packet Tracer | VLANs | Subnetting | Routing | Switching</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CCNA-Networking-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PacketTracer-Project-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/VLAN-Implementation-purple?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IP-Subnetting-orange?style=for-the-badge"/>
</p>

---

## 🌐 Project Title

**Small Office / Home Office (SOHO) Network Design & Implementation**

---

## 🌟 Project Overview

This project demonstrates a **real-world SOHO network design** implemented using **Cisco Packet Tracer**, following **CCNA-level networking principles**. The network is segmented into multiple departments using **VLANs**, supports **wired and wireless devices**, and enables **inter-VLAN communication** through a router.

The design focuses on **security, scalability, and efficient traffic management**, making it suitable for academic evaluation as well as a professional networking portfolio.

---

## 🎯 Project Objectives

* Design a structured SOHO network topology
* Implement **VLAN-based departmental segmentation**
* Configure **router-on-a-stick** for inter-VLAN routing
* Apply efficient **IPv4 subnetting (/26)**
* Enable wired and wireless connectivity
* Verify end-to-end connectivity using ping tests

---

## 🗂️ Network Design Summary

| Department     | VLAN    | Subnet           | Purpose                   |
| -------------- | ------- | ---------------- | ------------------------- |
| Admin / IT     | VLAN 10 | 192.168.1.0/26   | Network administration    |
| Finance / HR   | VLAN 20 | 192.168.1.64/26  | Financial & HR operations |
| CS / Reception | VLAN 30 | 192.168.1.128/26 | Customer handling         |

---

## 🧩 Topology Architecture

* **Central Layer 2 Switch** for device aggregation
* **Router** providing inter-VLAN routing
* **Dedicated Access Points** for each department
* PCs, printers, laptops, and smartphones connected per VLAN

```
VLAN 10 (Admin)   
        |         
        |         
      SWITCH —— ROUTER —— Internet
        |         
        |         
VLAN 20 & 30 (Finance / CS)

---

## 💻 Skills Demonstrated

* ✔ VLAN creation and assignment
* ✔ IPv4 subnetting and IP addressing
* ✔ Router and switch configuration
* ✔ Wireless network integration
* ✔ Proper cabling and interface setup
* ✔ Connectivity testing and troubleshooting

---

## ✅ Connectivity Verification

* Admin VLAN → Finance VLAN → ✔ Successful
* Finance VLAN → CS VLAN → ✔ Successful
* Wireless devices → Wired devices → ✔ Successful
* Inter-VLAN routing → ✔ Operational

---

## 📚 Learning Outcomes

* Strong understanding of **enterprise-style network design**
* Practical VLAN and routing experience
* Improved troubleshooting and documentation skills
* Hands-on CCNA exam preparation

---

## 🛠 Tools & Technologies Used

* Cisco Packet Tracer
* Cisco IOS CLI Commands
* VLANs & Trunking
* IPv4 Subnetting
* CCNA Core Networking Concepts

---

## 👨‍💻 Author

**ANUP KUMAR SINGH**
🎓 BCA Student | Aspiring Network Engineer | CLOUD & DESKTOP SUPPORT ENGINEER 

---

## 🏁 Conclusion

This project successfully demonstrates a **secure, scalable, and well-structured SOHO network**. By applying VLAN segmentation, subnetting, and routing, the network achieves reliable inter-department communication and reflects real-world CCNA networking practices.

---

💡 *More networking projects will be added — from basic to advanced.*
⭐ *Star this repository to follow the journey.*
