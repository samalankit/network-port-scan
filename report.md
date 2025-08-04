# 📝 Port Scanning Report

## 📌 Task: Local Network Port Scanning

This report documents the process, results, and analysis of scanning a local network to identify open ports and potential vulnerabilities using Nmap.

---

## 🎯 Objective

- Perform a TCP SYN scan on the local network.
- Identify live hosts and open ports.
- Analyze the risks associated with exposed services.

---

## 🛠 Tools Used

| Tool        | Purpose                                     |
|-------------|---------------------------------------------|
| Nmap        | Network discovery and port scanning         |
| Wireshark   | (Optional) Network packet analysis          |

---

## 🌐 Network Information

| Item                | Value               |
|---------------------|---------------------|
| Local IP Address    | 192.168.1.0        |
| Network Range Scanned | 192.168.1.0/24   |
| Scan Type           | TCP SYN Scan (`-sS`)|

---

## 🧪 Scan Command Used

```bash
nmap -sS 192.168.1.0/24 -oN scan_results.txt
