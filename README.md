
# nmap-port-scan-task-1
Task 1 – Cyber Security Internship: Local Network Scan using Nmap

# Task 1: Nmap Port Scan of Local Network

## 🔧 Tools Used:
- Nmap 7.97
- OS: Windows 10

## 🧪 Steps Followed:
1. Installed Nmap from official website.
2. Found local IP using `ipconfig` → 192.168.0.103
3. Ran scan: `nmap -sS 192.168.0.0/24`
4. Saved result in `scan_result.txt`

## 📋 Results Summary:

### ➤ 192.168.0.1 (Router)
- Port 80 (http) open  
- Service: Web Admin Panel  
- Risk: May be vulnerable if default credentials used

### ➤ 192.168.0.100 (Mobile/Smart Device - Xiaomi)
- All ports closed ✅

### ➤ 192.168.0.103 (My System)
- Open Ports:
  - 135 (msrpc)
  - 139 (netbios-ssn)
  - 445 (microsoft-ds)
  - 3306 (mysql)
- Risks:
  - File-sharing ports are vulnerable to malware
  - MySQL exposed if not secured properly

## 🎯 Learning Outcome:
- Understood port scanning and network exposure
- Identified services and basic risks

