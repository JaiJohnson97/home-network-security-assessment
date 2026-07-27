# 🛡️ Chromebook Network Security Assessment

## 👋 Project Overview

This project documents a basic network security assessment performed using a Chromebook and ChromeOS diagnostic tools. The objective was to collect network information, analyze the device's network configuration, identify potential security considerations, and document findings using cybersecurity best practices.

This project demonstrates my ability to gather technical information, analyze network configurations, assess potential risks, and communicate findings in a professional cybersecurity report.

---

# 🎯 Objective

The objectives of this assessment were to:

- Identify network characteristics
- Analyze the device's network configuration
- Understand private and public networking concepts
- Evaluate basic security risks
- Document findings using professional cybersecurity documentation
- Practice thinking like a cybersecurity analyst

---

# 🛠️ Tools Used

- Chromebook
- ChromeOS
- Chrome System Diagnostics (`chrome://system`)
- GitHub
- Markdown

---

# 📋 Scope

This assessment included:

- ChromeOS network diagnostics
- Wireless network configuration
- Private IPv4 addressing
- Default gateway identification
- DNS server identification
- Network service configuration
- Basic security observations
- Risk assessment
- Security recommendations

---

# 🔍 Findings

## Finding #1 – Public Wireless Network

During the assessment, the Chromebook successfully connected to a public wireless network.

### Security Observation

Public wireless networks should always be considered untrusted because multiple users may share the same network. Sensitive activities should only be performed over encrypted HTTPS connections, and users should avoid sharing confidential information on public Wi-Fi whenever possible.

### Risk Level

**Medium**

### Recommendation

Avoid accessing sensitive accounts while connected to public Wi-Fi unless the connection is protected through HTTPS or a trusted VPN.

---

## Finding #2 – Network Configuration

### Device Connection

The Chromebook successfully obtained a private IPv4 address from the network using DHCP.

### Network Details

- Connection Type: Wi-Fi
- Private IPv4 Address: 10.235.159.203
- Default Gateway: 10.128.128.128
- DNS Server: 10.128.128.128

### Security Observation

The Chromebook successfully received valid network configuration information from the network. The gateway and DNS server were provided by the local network, which is common in managed wireless environments.

### Risk Level

**Low**

### Recommendation

Continue using trusted networks whenever possible. When connected to public Wi-Fi, ensure secure websites use HTTPS and avoid transmitting sensitive information unless additional protection such as a VPN is being used.

---

## Finding #3 – Network Service Configuration

### Service Details

- Network Interface: wlan0
- Connection State: Online
- Auto Connect: Enabled

### Security Observation

The Chromebook successfully connected to the wireless network and automatically received network services. Automatic reconnection provides convenience but should be reviewed carefully when connecting to public wireless networks.

### Risk Level

**Low to Medium**

### Recommendation

Disable automatic reconnection for public wireless networks that are no longer trusted. This helps reduce the possibility of unintentionally reconnecting to an untrusted wireless network.

---

# 📸 Evidence

The following screenshots were collected during the assessment to support the findings documented above.

---

## ChromeOS System Information

This screenshot documents the Chrome browser version and ChromeOS system information used during the assessment.

![ChromeOS System](screenshots/Screenshot%202026-07-27%205.31.36%20PM.png)

---

## Network Devices

This screenshot documents the Chromebook's wireless adapter, private IPv4 address, default gateway, and DNS configuration.

![Network Devices](screenshots/Screenshot%202026-07-27%205.32.48%20PM.png)

---

## Network Services

This screenshot documents the active wireless network service and network configuration.

![Network Services](screenshots/Screenshot%202026-07-27%205.33.31%20PM.png)

---

# 📚 Skills Demonstrated

- Network Fundamentals
- ChromeOS System Analysis
- Network Configuration Analysis
- Security Documentation
- Risk Assessment
- Technical Writing
- Cybersecurity Best Practices
- GitHub Documentation
- Markdown

---

# 🎓 Key Concepts Learned

During this assessment, I strengthened my understanding of:

- Private IP addresses
- Public IP addresses
- Default gateways
- DNS servers
- DHCP
- Wireless networking
- Public Wi-Fi security
- Network risk assessment
- Professional cybersecurity documentation

---

# 📝 Conclusion

This project demonstrates my ability to collect technical network information, analyze network configurations, identify potential security considerations, and professionally document findings using cybersecurity best practices.

Completing this assessment strengthened my understanding of networking fundamentals while improving my technical documentation and analytical skills.

---

# 🚀 Future Improvements

Future versions of this project will include:

- Home network assessment
- Router security review
- Network diagram
- Windows networking tools
- PowerShell networking commands
- Wireshark traffic analysis
- Additional screenshots
- Expanded security recommendations

---

# ✅ Project Status

**Completed – Version 1.0**

Last Updated: July 2026

---

## 👩🏽‍💻 Author

**Jaliah Johnson**

Cybersecurity Student | Lone Star College

🔗 LinkedIn: https://www.linkedin.com/in/jaliah-johnson-516a43225

🌐 GitHub Portfolio: https://jaijohnson97.github.io/jaliah-cybersecurity-portfolio/
