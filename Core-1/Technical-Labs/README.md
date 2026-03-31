# 💻CompTIA A+ (220-1201) Core 1 | Technical Lab Portfolio

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

---

## 🖥️ Section 3: Hardware
### Lab: System Inventory & Visual Component Identification (Objectives 3.4 - 3.8)

**The Goal:** To identify the specific internal hardware components of a live system using OS-level tools and map them to their physical form factors and socket types.

**What I did:**
Using the **System Information (msinfo32)** tool and **Task Manager**, I audited the technical specifications of a Windows workstation. I practised "data sanitisation" by masking sensitive identifiers while retaining the technical data required for hardware support and inventory management.

**1. Motherboard & CPU Identification**
I identified the Processor and BIOS mode to determine the system architecture and firmware security capabilities.
* **Motherboard:** Generic OEM (Intel Gemini Lake Entry)
* **CPU:** Intel Celeron J4105 @ 1.50GHz (4 Cores)
* **BIOS Mode:** **UEFI**
* **Technical Context:** By confirming the **UEFI** BIOS mode, I verified that the system supports modern security features such as **Secure Boot** and is capable of handling GPT (GUID Partition Table) drives larger than 2TB. The Celeron J4105 is a System-on-a-Chip (SoC) design, meaning the CPU and many motherboard functions are integrated for high energy efficiency.

**2. Memory (RAM) Audit**
I investigated the system memory profile to check for performance modes and physical expansion availability.
* **Speed:** 2133 MT/s
* **Slots Used:** 2 of 4
* **Form Factor:** **DIMM**
* **Technical Context:** Identifying the form factor as **DIMM** confirms this is a desktop-class motherboard. Since **2 of 4 slots** are occupied, the system is likely configured for **Dual-Channel memory**, which doubles the communication bandwidth between the RAM and the CPU. The 2133 MT/s speed is the baseline for DDR4, providing a stable environment for office and administrative tasks.

**3. Graphics & Expansion**
I identified the Graphics Processing Unit (GPU) to understand the system's video rendering capabilities and shared resources.
* **GPU:** Intel UHD Graphics 600
* **Interface:** Integrated (Intel Goldmont Plus)
* **Technical Context:** This system utilises **Integrated Graphics**, meaning the GPU is built into the CPU die and shares the system RAM (UMA - Unified Memory Architecture). This is an ideal configuration for low-power workstations where a dedicated (discrete) PCIe graphics card is not required for standard business applications.

**My takeaway:** A key skill in IT support is the ability to identify hardware specifications without opening the case. By using these administrative tools, I was able to determine the system's upgrade path (two empty RAM slots) and its firmware security status (UEFI) without any physical downtime.

---

## 🛠️ Skills Demonstrated 

### **Section 1: Mobile Devices**
* **Protocol Proficiency:** In-depth understanding of **IMAP, POP3, and SMTP** for mobile mail configuration.
* **Security Implementation:** Verified deployment of **SSL/TLS** encryption and digital certificates for securing data in transit.
* **Cloud Synchronisation:** Managed cross-platform data consistency for contacts, calendars, and application data.

### **Section 2: Networking**
* **CLI Troubleshooting:** Proficient in using Windows command-line tools (`ipconfig`, `ping`, `nslookup`) to diagnose connectivity issues.
* **Network Administration:** Solid understanding of **DHCP** leasing, **DNS** hierarchy (Port 53), and default gateway routing.
* **Security Auditing:** Experienced in auditing SOHO router configurations, specifically **WPA2-PSK (AES)** encryption and SSID management.

### **Section 3: Hardware**
* **Administrative Tools:** Proficient in using `msinfo32` and Task Manager for hardware auditing and inventory management.
* **System Architecture:** Clear understanding of **SoC (System-on-a-Chip)**, Integrated Graphics, and the advantages of **UEFI** over Legacy BIOS.
* **Performance Logic:** Ability to interpret RAM slot usage and the performance benefits of **Dual-Channel** memory bandwidth.
* **Information Security:** Practised technical **data sanitisation** by removing sensitive OEM strings and personal identifiers from public-facing documentation.

---

## ** Work In Progress**

---
[⬅️ Back to Profile Hub](https://github.com/ssaunders91)

[⬅️ Back to CompTIA A+ Hub](https://github.com/ssaunders91/CompTIA-A-Plus/blob/main/README.md)

[⬅️ Back to CompTIA A+ Core 1 Hub](https://github.com/ssaunders91/CompTIA-A-Plus/blob/main/Core-1/README.md)

