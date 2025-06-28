# Enumeration
# 🔍 Project: Network Discovery, Enumeration & Vulnerability Scanning

This repository documents my practical task to perform **network discovery**, **SMB enumeration**, **email address harvesting**, and **vulnerability scanning** as part of my cybersecurity internship.

---

## 📌 Tasks Completed

### 1️⃣ Network Discovery

- Identified a **target network/system** within a virtual lab or controlled test environment.
- Defined the IP range and scope for scanning, ensuring all activities remained within the authorized test range.

---

### 2️⃣ Scanning with Nmap

- Used **Nmap** to perform an initial scan to:
  - Identify **live hosts**
  - Detect **open ports**
  - Determine **services & versions** running on each host

**Example Commands:**

```bash
# Ping sweep to find live hosts
nmap -sn 192.168.1.0/24

# Service and version detection
nmap -sV 192.168.1.5

# Aggressive scan for more detail
nmap -A 192.168.1.5
