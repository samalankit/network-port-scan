# 🔍 Local Network Port Scan

This project is part of a cybersecurity assignment aimed at identifying potential vulnerabilities within a local network. Using **Nmap**, the scan detects active hosts and their open ports to understand network exposure and risk.

---

## 📌 Objective

- Discover active devices on the local subnet.
- Identify open TCP ports and associated services.
- Assess potential risks due to exposed services.

---

## 🛠 Tools Used

- [**Nmap**](https://nmap.org/) – Network discovery and port scanning
- [**Wireshark**](https://www.wireshark.org/) *(optional)* – Packet sniffing and analysis

---

## 🧪 Methodology

1. Identified the local subnet using:
   - `ipconfig` (Windows) or `ifconfig/ip a` (Linux/macOS)
2. Determined subnet: `192.168.1.0/24`
3. Ran a TCP SYN scan:
   ```bash
   nmap -sS 192.168.1.0/24 -oN scan_results.txt
