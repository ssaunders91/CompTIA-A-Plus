# CompTIA A+ (220-1201) | Technical Lab Portfolio

## Project Overview
I am currently working through the CompTIA A+ curriculum with a primary focus on **technical mastery and hands-on proficiency**. While my immediate goal is to acquire the industry-standard knowledge required for a modern IT role, I am documenting these labs to demonstrate my ability to apply theoretical concepts to real-world hardware and networking scenarios. 

Even without the formal examination at this stage, I am committed to maintaining a high standard of documentation and technical accuracy as I build my foundation in IT Support and Systems Administration.

---

## 📱 Section 1: Mobile Devices
### Lab: Mobile Mail & Synchronisation (Objective 1.1)

**The Goal:** To understand the underlying protocols that allow mobile devices to communicate with mail servers and stay in sync.

**What I did:**
I manually configured a professional mail account, moving away from "automatic" setups to look at the specific port configurations and protocols involved.

**Key Observations:**
* **Protocols:** Investigated the functional differences between **IMAP** and **POP3**, specifically how they handle data retention on the server.
* **Security:** Verified the use of **SSL/TLS** encryption to secure data in transit.
* **Syncing:** Audited the synchronisation of contacts and calendars across multiple platforms to understand cloud-based data consistency.

**My takeaway:** Seeing the actual security certificates and port numbers (like 993 for IMAPS) made the theory much easier to digest. It’s about understanding the "how" behind the daily tasks we take for granted.

---

## 🌐 Section 2: Networking
### Lab: Network Diagnostics & CLI Proficiency (Objective 2.1)

**The Goal:** To use Command Line Interface (CLI) tools to map my local network and verify end-to-end connectivity.

**What I did:**
I used standard Windows CLI tools to gather technical evidence of a stable network connection.

**1. Local Configuration (`ipconfig /all`)**
I audited my network stack to identify my **MAC Address** and **Default Gateway** (192.168.0.1). I also confirmed that **DHCP** was functioning correctly, as my workstation was successfully leased a private Class C IP address.

**2. Connectivity Testing (`ping`)**
I tested the path to an external server (`google.com`) using ICMP packets.
* **Result:** 0% packet loss with an average latency of 28ms. 
* **Conclusion:** This confirmed that my local hardware, the router, and the ISP’s gateway were all communicating without errors.

**3. DNS Resolution (`nslookup`)**
I used `nslookup` to verify that my DNS resolver was correctly translating Fully Qualified Domain Names (FQDNs) into IP addresses. This confirmed that Port 53 was open and the "phonebook" of the internet was accessible.

---

### Lab: SOHO Router Security Audit (Objective 2.3)

**The Goal:** To navigate a real-world Small Office/Home Office (SOHO) router interface and audit its security posture.

**What I did:**
Using the gateway IP identified in the previous lab, I accessed the router's management GUI to review its configuration.

**Findings:**
* **Wireless Security:** Confirmed the use of **WPA2-PSK (AES)**, which is the current industry standard for secure home networking.
* **DHCP Management:** Located the IP address pool and verified the lease settings for local clients.
* **SSID Configuration:** Checked the broadcast settings and frequency channels to ensure optimal performance.

**My takeaway:** Navigating a real-world interface turned the textbook definitions into practical knowledge. It’s one thing to read about a "DHCP Pool," but it's much more valuable to know exactly where to find it when a user's device won't connect.

-----

## 🛠️ Skills Demonstrated
* **CLI Troubleshooting:** Proficient with `ipconfig`, `ping`, and `nslookup`.
* **Network Admin:** Understanding of IP addressing, DNS hierarchy, and Gateway routing.
* **Security Awareness:** Auditing WPA2/AES encryption and SOHO best practices.
---
[⬅️ Back to CompTIA A+ Hub](https://github.com/ssaunders91/CompTIA-A-Plus/blob/main/README.md)

[⬅️ Back to Profile Hub](https://github.com/ssaunders91)

