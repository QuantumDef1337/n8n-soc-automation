# n8n-soc-automation
Automate your SOC operations with real-time alerts using n8n. This repository contains workflow templates that detect, notify, and respond to critical incidents including real-time alerting via Telegram, automatic IP blocking, and endpoint scanning. Ideal for blue teams and security analysts who want to reduce response time and improve visibility.

# 🔐 Wazuh + n8n: SOC Automation Workflows

This repository provides **ready-to-use automation workflows** built with [n8n](https://n8n.io) to enhance and accelerate your SOC operations on top of Wazuh. Each use case automates specific detection or response actions and integrates seamlessly with tools like Telegram, firewalls, or endpoint scanners.

## ✨ Use Cases

1. **Critical Incident Reporting**  
   Real-time alert delivery to Telegram (or any channel) when Wazuh detects high-severity events like unauthorized root access or PAM events.

2. **IP Blocking Automation**  
   Automatically block malicious IPs in firewalls (e.g., UFW or CrowdSec) when brute-force or suspicious logins are detected.

3. **Endpoint Threat Response**  
   Trigger full system scans using Wazuh agent on endpoints where malware or suspicious behavior is detected.

> More use cases coming soon — contribute or watch this repo for updates!

## 📂 Folder Structure

