# Logsheild-
LogShield is a powerful and portable log analyzer built specifically for Termux on Android devices. It enables security enthusiasts, ethical hackers, and system administrators to scan and monitor server log files for suspicious activities, helping detect cyber threats such as brute-force attacks, port scans, unauthorized access attempts, and more
# 🔐 LogShield – Advanced Log Analyzer for Termux

**LogShield** is a powerful and portable log analyzer built specifically for **Termux** on Android devices. It helps ethical hackers, cybersecurity learners, and system administrators analyze server log files and detect suspicious activity like brute-force attacks, port scans, unauthorized access, and more — all directly from a mobile device.

This tool simplifies log auditing by automating detection patterns and generating readable reports, enabling real-time and offline analysis of logs such as `auth.log`, `syslog`, and other system or custom log files.

---

## 🛡️ Features

- ✅ Detects:
  - Brute-force login attempts
  - Port scans
  - DoS (Denial of Service) attacks
  - Suspicious IP access
- 📁 Analyzes default or custom log files
- 📊 Generates clean, exportable reports (text or JSON)
- 🔁 Works offline — great for mobile auditing
- ⚙️ Lightweight, Bash-based (no dependencies)
- ☁️ Optional Firebase or email alert integration

---

## 📦 Use Cases

- Log analysis after penetration testing
- Security event detection for small or personal servers
- Educational tool to learn how attackers leave traces in logs
- Easy mobile monitoring for field use

---

## 🚀 Getting Started

```bash
# Make script executable
chmod +x logshield.sh

# Run the tool
bash logshield.sh
## 📁 Project Structure
Logsheild-/
├── logshield.sh          # Main script
├── patterns.conf         # Detection patterns (optional/customizable)
├── report/               # Output folder for results
└── README.md             # This file
