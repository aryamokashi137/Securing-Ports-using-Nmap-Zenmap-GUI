# 🔒 Securing Ports using Nmap – Zenmap GUI

## 🔎 Overview
This project focuses on using **Nmap (via Zenmap GUI)** to perform port scanning, identify open/filtered/closed ports, and secure vulnerable services.  
During the analysis, port **3306 (MySQL)** was found to be open and unauthorized. Security measures were implemented to restrict access and harden the system.

---

## 🎯 Objectives
- Explore **Nmap – Zenmap GUI** for port scanning.  
- Identify open, closed, and filtered ports on a device.  
- Detect unauthorized access (MySQL service on port 3306).  
- Secure MySQL service using local-only configuration and firewall rules.  
- Understand port states and their security implications.  

---

## 🛠 Tools Used
- **Nmap / Zenmap GUI** – For scanning and port state analysis.  
- **Windows Firewall** – To block unwanted access.  
- **MySQL Server 8.0** – For service testing and configuration.  
- **Command Prompt (cmd)** – For service and firewall management.  


---

## 🔍 Key Learnings
- **Port Numbers** are logical addresses at the **Transport Layer (Layer 4)** (e.g., HTTP: 80, HTTPS: 443).  
- **Open Ports** → Service is accessible and may be exploited.  
- **Closed Ports** → No service listening, but reachable.  
- **Filtered Ports** → Blocked by firewall, invisible to attackers.  
- **Security Practices**:
- Keep only required ports open.  
- Use strong authentication for services.  
- Restrict services (like MySQL) to localhost if remote access is not needed.  
- Block unused or risky ports with firewall rules.  

---

## ✅ Conclusion
Nmap – Zenmap GUI revealed that MySQL port 3306 was exposed.  
By restricting MySQL to local connections and blocking external access through firewall rules, the port was secured.  
**Open ports increase the attack surface; therefore, unused or weakly protected ports must always be closed or filtered.**

---

✍️ This project was created as part of my **cybersecurity learning journey**.
