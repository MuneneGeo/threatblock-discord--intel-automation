# 🛡️ ThreatBlock – Discord Cybersecurity Intelligence System
An automated threat monitoring system built using n8n that collects cybersecurity news and sends structured alerts to Discord.

---

## 🧠 Overview

ThreatBlock continuously monitors cybersecurity feeds, filters critical vulnerabilities, and delivers alerts directly into a Discord channel.

---

## ⚙️ How It Works

1. Scheduled trigger runs workflow
2. Fetches security news / CVEs / threat reports
3. Filters important/high-risk threats
4. Formats structured alert message
5. Sends it to Discord via webhook

---

## 💬 Discord Output Example

🚨 Critical Vulnerability Detected  
Title: Apache RCE Exploit  
Severity: HIGH  
Summary: Active exploitation detected in the wild  
Source: https://...

---

## 🧱 Tech Stack

- n8n automation engine  
- Discord Webhooks  
- CVE / RSS / Threat APIs  

---

## 📁 Project Structure

/workflows → automation JSON  
/docs → documentation  
/images → diagrams & screenshots  

---

## 🔐 Security Notes

- No API keys are stored in GitHub  
- Webhook URLs are kept in n8n credentials  
