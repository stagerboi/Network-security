🔐 Network Security Basics 

This repository contains the detailed report and resources for **"Introduction to Network Security Basics"**, focusing on identifying common network threats, securing a basic network setup, and analyzing traffic using Wireshark.

📄 Project Overview

The purpose of this task was to explore the fundamentals of network security through a combination of research and hands-on practice. The task included:

- Understanding common types of network threats
- Implementing basic security configurations on a home or test network
- Monitoring real-time traffic using Wireshark
- Learning to recognize suspicious patterns and potential security issues

👨‍💻 Key Activities

- 🔍 **Threat Research**  
  Researched viruses, worms, trojans, phishing attacks, and Man-in-the-Middle (MitM) attacks.

- 🔧 **Security Configuration**  
  - Configured Windows Defender Firewall  
  - Changed default router credentials  
  - Enabled WPA2/WPA3 encryption on Wi-Fi  
  - Disabled unnecessary network services like file sharing

- 🌐 **Traffic Monitoring with Wireshark**  
  - Filtered and analyzed DNS, TCP, TLS, and ICMP packets  
  - Interpreted real-time packet captures to understand network behavior  
  - Identified possible signs of suspicious traffic


## 📊 Protocols Observed

| Protocol | Purpose                               | Filter Used |
|----------|----------------------------------------|-------------|
| DNS      | Domain resolution and lookups         | `dns`       |
| TCP      | Reliable communication protocol       | `tcp`       |
| TLS      | Encrypted HTTPS traffic               | `tls`       |
| ICMP     | Network diagnostics (e.g., ping)      | `icmp`      |


✅ Security Best Practices Applied

- Enabled and customized the system firewall
- Used strong passwords and changed default login credentials
- Enforced WPA2/WPA3 for encrypted Wi-Fi communication
- Regularly updated the OS and antivirus
- Disabled unnecessary sharing and discovery services

🧠 Reflections

This task helped build a clear understanding of how network devices communicate and how easily threats can arise when basic protections are not in place. It also highlighted the importance of using tools like Wireshark to detect anomalies and enforce strong security measures — even in a simple home network.

 📁 Files Included

- `TASK 1 REPORT (REDYNOX).pdf` – Full PDF report including:
  - Threat summaries
  - Step-by-step security configurations
  - Protocol analysis with screenshots
  - Reflections and best practices

 💬 How to Use This

Anyone starting out in cybersecurity or network analysis can review the report and replicate the steps using:

- A home network (Wi-Fi + connected devices)
- Wireshark (for traffic capture and analysis)
- Basic Windows security tools (like Windows Defender Firewall)


## 🔗 Useful Resources

- [Wireshark Official Site](https://www.wireshark.org)
- [Microsoft Firewall Guide](https://support.microsoft.com/windows/turn-microsoft-defender-firewall-on-or-off)
- [Cybersecurity Basics (by CISA)](https://www.cisa.gov/topics/cybersecurity-best-practices)

