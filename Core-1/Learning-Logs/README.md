# 💻CompTIA A+ Certification Core 1 (220-1201) Study & Practice Logs 

This directory serves as a chronological record of my progress through the CompTIA A+ Core 1 curriculum. It tracks my performance on practice materials and highlights areas for further technical review.

---

## 📈 Section 1 Quiz Results

| Quiz | Topic | Score | Status |
| :--- | :--- | :--- | :--- |
| 1.1 | Mobile Hardware & Servicing | **76.19%** | 🟡 To re-do  |
| 1.2 | Connection Methods | **81.82%** | 🟢 Pass |
| 1.3 | Mobile Accessories | **94.12%** | 🟢 Pass |
| 1.4 | Network Connectivity | **81.82%** | 🟢 Pass |
| 1.5 | Application Support | **83.33%** | 🟢 Pass |

---

## 📓 Lessons Learnt & Knowledge Gaps

### **1.1 Mobile Hardware & Servicing**
* **Mistake Corrected:** I initially thought that disabling battery-saving features helped with health monitoring. **Lesson Learnt:** Battery health is actually tracked via internal telemetry (cycles and capacity) using **S.M.A.R.T.** or OS-level diagnostic tools; battery-saving modes are purely for power management, not diagnostics.
* **Signal Routing:** I clarified that Wi-Fi antennas are located in the **display bezel** (screen) to avoid interference from the motherboard, which is a common "trick" question in the exam.
* **Maintenance:** I reinforced the rule that **compressed air** should never be used on microphones due to their delicate diaphragms, a mistake that can lead to permanent hardware damage.

### **1.2 Connection Methods**
* **Mistake Corrected:** I previously confused **Port Replicators** with **Docking Stations**. **Lesson Learnt:** A Docking Station is much more advanced, often using a proprietary connection to extend the system bus, whereas a Port Replicator is essentially a glorified USB hub.
* **Reversibility:** I confirmed that **USB-C** is the modern standard for reversible connections, supporting high-speed data, power delivery, and video (Alt-mode) simultaneously.

### **1.3 Mobile Accessories**
* **NFC Misconception:** I learnt that NFC isn't just for payments; its role in **Bootstrap** pairing for Bluetooth is a critical technical function for simplifying the synchronisation of devices.
* **Hands-free Safety:** I reinforced that **Bluetooth headsets** are considered a primary accessory for hands-free communication, particularly in environments where physical tethering to a handset is restricted.

### **1.4 Network Connectivity**
* **Mistake Corrected:** I underestimated the role of **Cellular Triangulation**. **Lesson Learnt:** While GPS is more accurate, cellular location is the essential failover for when a device is indoors or in "urban canyons" where satellite signals are blocked.
* **Authentication:** I reinforced that the **PIN** during Bluetooth pairing is a mandatory security handshake to ensure the user has physical control over both devices being linked.

### **1.5 Application Support**
* **Mistake Corrected:** When an app disappears, I shouldn't just assume a software crash. **Lesson Learnt:** In an enterprise environment, the first check should be the **MDM (Mobile Device Management)** console to see if the app was remotely uninstalled or if access was revoked by the administrator.
* **Corporate Policy:** I clarified the difference between **BYOD** and **COPE**, specifically how MDM software allows a company to segregate and remotely wipe business data without affecting a user's personal files.

---

## 📈 Section 2 Quiz Results

| Quiz | Topic | Score | Status |
| :--- | :--- | :--- | :--- |
| 2.1 | Network Protocols | **75%** | 🟡 To re-do |
| 2.2 | TCP & UDP Ports | **94.12%** | 🟢 Pass |
| 2.3 | Wireless Networking Technologies | **94.74%** | 🟢 Pass |
| 2.4 | Network Services | **95%** | 🟢 Pass |
| 2.5 | Network Configuration Concepts | **93.33%** | 🟢 Pass |
| 2.6 | Common Networking Hardware | **85.19%** | 🟢 Pass |
| 2.7 | IP Addressing | **73.08%** | 🟡 To re-do  |
| 2.8 | Internet Connection Types | **90%** | 🟢 Pass |
| 2.9 | Network Types | **100%** | 🟢 Pass |
| 2.10 | Networking Tools | **87.5%** | 🟢 Pass |

---

## 📓 Lessons Learnt & Knowledge Gaps

### 2.1 Network Protocols
* **Telnet Security:** I missed that **Telnet** actually provides username and password authentication. Even though it transmits data in plaintext (unencrypted), the login handshake still exists.
* **SMTP vs. Retrieval:** SMTP is strictly for **sending** mail. I incorrectly selected "Retrieving email"; that role belongs to POP3 or IMAP.
* **IMAP Syncing:** IMAP is the protocol used to sync folders across multiple devices, which is its primary advantage over POP3.
* **NetBIOS:** The API used for host-to-host communication on a LAN is **NetBIOS**, not TCP/IP.

### 2.2 TCP & UDP Ports
* **Telnet Port:** I misidentified the port as 22. Telnet uses **TCP Port 23**, while Port 22 is reserved for **SSH**.
* **Port Knowledge:** Reinforced Port **445** for SMB/CIFS and Port **3389** for RDP.

### 2.3 Wireless Networking Technologies
* **Channel Width:** Increasing channel width **increases data throughput** but also increases the risk of radio frequency interference.
* **Frequencies:** **2.4 GHz** provides the longest range and best penetration, while **5 GHz** offers more non-overlapping channels for high-density areas.


### 2.4 Network Services
* **AAA Protocols:** **TACACS+** is the TCP-based enterprise solution that separates AAA functions. I mistakenly chose OAuth.
* **Spam Gateway:** This device is specifically used to monitor inbound communication to block malicious or unwanted messages.

### 2.5 Network Configuration Concepts
* **DNS Records:** I learned that **AAAA records** map hostnames to 128-bit **IPv6** addresses, while **A records** are for 32-bit IPv4 addresses.
* **DHCP Scope:** A DHCP **Scope** is the specific range of IP addresses available for dynamic assignment.

### 2.6 Common Networking Hardware
* **Managed Switches:** I reinforced that a **Managed Switch** is required for advanced features like **VLANs**, Port Mirroring, and Quality of Service (QoS).
* **Hub vs. Bridge:** A Hub is a legacy broadcast device, while a **Bridge** is used to connect two network segments using MAC addresses.

### 2.7 IP Addressing
* **APIPA:** A **169.254.x.x** address is a "Link-Local" address used when a client cannot obtain an address from a DHCP server.
* **IPv6 Loopback:** I noted that **::1** is the IPv6 loopback address (the equivalent of 127.0.0.1).
* **Subnet Masks:** I learned that a subnet mask is used by a device to determine which part of an IP address belongs to the network vs. the host.

### 2.8 Internet Connection Types
* **Satellite Latency:** High latency is the primary drawback of **Satellite** internet because the signal has to travel thousands of miles to space and back.
* **Physical Media:** **DSL** uses copper phone lines, while **Cable** uses coaxial TV lines.

### 2.9 Network Types
* **Network Scopes:** Correctly distinguished between **PAN** (Bluetooth), **LAN** (Local), **MAN** (City), and **WAN** (Global/Country-wide).

### 2.10 Networking Tools
* **Physical Identification:** A **Toner Probe** is used to find a specific wire in a bundle of cables.
* **Testing:** A **Loopback Plug** is used to test the physical port of a network interface card (NIC) to see if it is functioning.

---

## 📈 Section 3 Quiz Results

| Quiz | Topic | Score | Status |
| :--- | :--- | :--- | :--- |
| 3.1 | Display Devices | **85.71%** | 🟢 Pass |
| 3.2 | Cabling | **84.13%** | 🟢 Pass |
| 3.3 | Connectors | **95.65%** | 🟢 Pass |
| 3.4 | RAM | **84.85%** | 🟢 Pass |
| 3.5 | Storage Devices | **86.05%** | 🟢 Pass |
| 3.6 | Motherboard | **78.13%** | 🟡 To re-do |
| 3.7 | BIOS | **84.62%** | 🟢 Pass |
| 3.8 | CPU | **83.33%** | 🟢 Pass |
| 3.9 | Power Supply | **80%** | 🟢 Pass |
| 3.10 | Multifunction Devices | **86.36%** | 🟢 Pass |
| 3.11 | Printers | **86.67%** | 🟢 Pass |

---

## 📓 Lessons Learnt & Knowledge Gaps

### **3.1 Display Devices**
* **Mistake Corrected:** I initially thought Mini-LEDs provided true black levels like OLED. **Lesson Learnt:** Only **OLED** achieves true blacks via self-emissive pixels; **Mini-LED** is superior for high peak brightness in well-lit environments.
* **Component Roles:** I reinforced that a **Digitiser** is the specific component that translates analogue touch/pen input into digital signals for processing.
* **Legacy Support:** I clarified that an **Inverter** is required for older LCD backlights (converting DC to AC) but is entirely absent in OLED technology.

### **3.2 Cabling**
* **Media Classification:** I missed that **Coaxial cable** is officially classified as a copper-based transmission medium for cable TV and high-speed internet.
* **Environmental Needs:** I reinforced that **Direct Burial STP** is the standard for underground infrastructure due to its resistance to moisture and chemicals.
* **Signal Capabilities:** I learnt that **DisplayPort** is a versatile digital interface capable of carrying both high-definition video and audio signals.

### **3.3 Connectors**
* **Internal Power:** I previously confused peripheral power. **Lesson Learnt:** The **Molex** connector is the standard 4-pin interface for powering older internal drives and fans.
* **Fibre Standards:** I clarified that the **LC (Lucent Connector)** is a Small Form Factor connector, distinct from the larger, push-pull SC connectors.
* **Legacy Communication:** I reinforced that the **DB-9** is the standard copper connector for serial communication on older PCs and networking hardware.

### **3.4 RAM (Memory)**
* **Cache Mechanics:** I initially underestimated SRAM usage. **Lesson Learnt:** **SRAM** is utilised for CPU cache because it is much faster than the DRAM used for system memory.
* **Compatibility:** I reinforced that RAM generations (DDR3, DDR4, etc.) are **not backward compatible**; the physical notch is moved on each generation to prevent incorrect installation.
* **Error Handling:** I clarified the difference between **Parity** (detection only) and **ECC** (detection and correction), noting that desktops usually use Non-ECC.

### **3.5 Storage Devices**
* **Cable Limits:** I learnt that both SATA II and SATA III specify a maximum cable length of **1 metre** and support only **one device** per cable.
* **Transfer Speeds:** I reinforced that **SATA Revision 2.0** supports 3 Gbps, while **Revision 3.0** supports 6 Gbps.
* **External Specs:** I confirmed that **eSATA** supports hot-swapping and allows for longer 2-metre cables compared to internal SATA.

### **3.6 Motherboard**
* **Standard Sizes:** I mistakenly identified ITX as the desktop standard. **Lesson Learnt:** **ATX** is the standard for full-size desktops, while **ITX** is the smallest common form factor.
* **Power Logic:** I clarified that the power and reset switches plug into **Front Panel Headers** on the motherboard, not directly into the power supply.

* **Socket Restrictions:** I reinforced that motherboards are built for specific CPU manufacturers; you cannot use an AMD CPU in an Intel-based motherboard.

### **3.7 BIOS / UEFI**
* **Security Hardware:** I learnt that the **TPM (Trusted Platform Module)** is a dedicated chip for storing cryptographic keys and ensuring platform integrity.
* **Access Control:** I clarified the difference between a **Boot Password** (stops the OS from loading) and a **Supervisor Password** (protects the BIOS settings themselves).
* **Configuration:** I reinforced that drive boot priority is adjusted within the **Boot Options** menu of the BIOS/UEFI.

### **3.8 CPU**
* **Architectures:** I reinforced that **x86** designates 32-bit architecture, while **x64** is the 64-bit standard.
* **Thermal Management:** I learnt that a **Heat sink** is a passive cooling device, and **Thermal Paste** is required specifically to bridge the gap between the CPU and the heat sink.

* **Virtualisation Tech:** I distinguished between **VT-x** (Intel) and **AMD-V** (AMD) hardware enhancements.

### **3.9 Power Supply**
* **Rail Voltages:** I missed that USB ports and smaller logic circuits draw from the **5V rail**, while the **12V rail** is reserved for high-power components like GPUs.
* **Power Units:** I reinforced that a PSU's total output capacity is measured in **Watts**.
* **Redundancy:** I learnt that **Redundant PSUs** are critical in enterprise environments for load balancing and automatic failover.

### **3.10 Multifunction Devices (MFDs)**
* **Scanning Automation:** I reinforced that the **ADF (Automatic Document Feeder)** is the component responsible for pulling multiple pages through the scanner automatically.
* **PDL Differences:** I clarified that **PostScript** is preferred for high-end graphics and accuracy, while **PCL** is more efficient and faster for general office text.
* **Networking:** I confirmed that **802.11x (Wi-Fi)** is the standard wireless protocol for modern office MFDs.

### **3.11 Printers**
* **Consumables:** I learnt that **Thermal printers** require no ink or toner, as they use heat-sensitive paper to create images.
* **Laser Cycle:** I clarified that the **Imaging Drum** is the component that holds the negative charge during the laser printing process.

* **Bonding:** I reinforced that the **Fuser** assembly uses heat and pressure to permanently bond toner to the paper fibres.
---

## ** Work In Progress**



---

[⬅️ Back to CompTIA A+ Hub](https://github.com/ssaunders91/CompTIA-A-Plus/blob/main/README.md)

[⬅️ Back to Profile Hub](https://github.com/ssaunders91)
