# Exploitation of Vulnerabilities in Windows XP (Metasploit)

## 📌 Overview
This project demonstrates the exploitation of vulnerabilities in **Windows XP SP3** using the **Metasploit Framework**.  
The objective was to showcase how legacy operating systems remain highly vulnerable to known exploits and why proper patching and upgrades are critical.

## 🛠 Tools & Environment
- **Operating System (Target):** Windows XP SP3 (32-bit)  
- **Attacker Machine:** Kali Linux  
- **Exploitation Tool:** Metasploit Framework  

## 🔍 Key Exploit
- **MS17-010 (EternalBlue / SMBv1 vulnerability)** – exploited using the Metasploit module:  
  `exploit/windows/smb/ms17_010_psexec`  

## 📑 Contents
- **/exploitation_report/** → Detailed documentation of the exploitation process  
- **/screenshots/** → Step-by-step evidence of the attack execution  

## ⚠️ Disclaimer
This project was conducted **strictly in a controlled lab environment** for educational and research purposes only.  
Do **not** attempt these methods on unauthorized systems.  

## 🎯 Learning Outcomes
- Practical understanding of how attackers exploit unpatched systems  
- Step-by-step exploitation workflow using Metasploit  
- Security best practices and mitigations against SMB vulnerabilities  

---
