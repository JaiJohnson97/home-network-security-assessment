# 🛡️ Public Wi-Fi Network Security Assessment

## Project Overview

This project documents a security assessment of a public wireless network using a Chromebook to identify network characteristics, evaluate basic security, and document findings using cybersecurity best practices.

---

# 🎯 Objective

The objective of this assessment is to:

- Identify network characteristics
- Evaluate basic network security
- Identify potential security risks
- Recommend improvements to strengthen security
- Practice documenting findings like a cybersecurity analyst

---

# 🛠️ Tools Used

- Chromebook
- ChromeOS
- Chrome System Diagnostics (chrome://system)
- GitHub
- Markdown

---

# 📋 Scope

This assessment includes:

- Public Wi-Fi Network
- Chromebook Network Configuration
- Network Service Configuration
- Basic Security Assessment
- Risk Assessment
- Security Recommendations

---

# 🔍 Findings

## Finding #1 – Network Environment

During this assessment, my Chromebook was connected to a public wireless network (Library-Public) with a strong signal.

### Security Observation

Public Wi-Fi networks should always be considered untrusted because multiple users can connect to the same network. Sensitive activities should be protected by using HTTPS websites, avoiding unnecessary file sharing, and keeping the device firewall enabled.

### Risk Level

Medium

### Recommendation

Avoid accessing sensitive information on public Wi-Fi unless the connection is encrypted. When possible, use a trusted network or a reputable VPN when handling confidential information.

---

## Finding #2 – Network Configuration

### Device Connection

The Chromebook successfully obtained a private IPv4 address from the network using Wi-Fi.

### Network Details

- Connection Type: Wi-Fi
- Private IPv4 Address: 10.235.159.203
- Default Gateway: 10.128.128.128
- DNS Server: 10.128.128.128

### Security Observation

The device successfully received a private IP address from the local network. The gateway and DNS services appear to be provided by the same network device, which is common in managed environments.

### Risk Level

Low

### Recommendation

Continue using trusted networks whenever possible. When connected to public Wi-Fi, avoid transmitting sensitive information unless the connection is protected through HTTPS or a trusted VPN.

---

## Finding #3 – Network Service Status

### Service Details

- Network Name (SSID): Library-Public
- Connection State: Online
- Auto Connect: Enabled
- Wireless Interface: wlan0

### Security Observation

The Chromebook successfully connected to the public wireless network and obtained network services. Automatic reconnection is enabled, which is convenient for trusted networks but should be reviewed when using public Wi-Fi.

### Risk Level

Low to Medium

### Recommendation

Disable automatic reconnection for public wireless networks when they are no longer needed. This reduces the chance of automatically joining an untrusted network in the future.

---

# 📚 Skills Demonstrated

- Network Security Fundamentals
- Security Documentation
- Risk Assessment
- Technical Writing
- ChromeOS System Analysis
- Public Wi-Fi Security Analysis
- Network Configuration Analysis

---

# 🎓 Key Concepts Learned

Throughout this assessment, I gained hands-on experience with:

- The difference between public and private IP addresses
- Identifying a default gateway
- Understanding DNS servers
- Interpreting network configuration information
- Evaluating security risks on public Wi-Fi
- Documenting findings using a professional cybersecurity reporting format

---

# 📝 Conclusion

This assessment demonstrated how to gather and interpret network configuration data using ChromeOS diagnostic tools. While connected to a public wireless network, I analyzed network characteristics, documented observations, identified potential security considerations, and developed recommendations based on cybersecurity best practices.

This project strengthened my understanding of networking fundamentals, risk assessment, and technical documentation while providing practical experience performing a basic network security assessment.

---

# 🚀 Status

✅ Completed (Version 1)

Future improvements:

- Perform a home network assessment for comparison.
- Analyze router security settings.
- Create a basic network diagram.
- Expand the assessment using Windows networking tools and PowerShell.**
