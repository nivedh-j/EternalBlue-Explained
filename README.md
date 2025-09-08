# EternalBlue (CVE-2017-0144) – Educational Documentation

## 📌 Introduction
EternalBlue is the codename for a cyberattack exploit developed by the U.S. National Security Agency (NSA).  
It takes advantage of a vulnerability in Microsoft’s Server Message Block (SMBv1) protocol on Windows systems, including **Windows 7 and Windows Server 2008**.  

The exploit was leaked by the group **Shadow Brokers** in April 2017 and later weaponized in major global attacks such as **WannaCry** and **NotPetya**.  

This repository is created **strictly for educational and research purposes** to help cybersecurity students understand the impact of EternalBlue, its history, and the mitigation techniques.

---

## ⚠️ Disclaimer
- This repository does **NOT** contain any exploit code, malware, or binaries.  
- The content here is limited to **educational documentation, research notes, and diagrams**.  
- The purpose is to raise awareness and improve understanding of one of the most significant vulnerabilities in modern cybersecurity history.  
- Any misuse of the knowledge presented here is strictly prohibited.  

---

## 🔎 Vulnerability Details
- **CVE ID:** [CVE-2017-0144](https://nvd.nist.gov/vuln/detail/CVE-2017-0144)  
- **Affected Protocol:** Microsoft SMBv1  
- **Impact:** Remote code execution (RCE)  
- **Affected Systems:** Windows XP, Windows Vista, Windows 7, Windows Server 2008, and others  

EternalBlue exploited a buffer overflow vulnerability in Microsoft’s SMBv1 protocol. This allowed attackers to remotely execute code on a target machine without authentication.

---

## 🕒 History & Impact
- **2017 (March):** Microsoft released patch MS17-010 (KB4012598).  
- **2017 (April):** Shadow Brokers leaked the exploit.  
- **2017 (May):** WannaCry ransomware outbreak infected hundreds of thousands of computers worldwide.  
- **2017 (June):** NotPetya attack caused billions in damages, using EternalBlue as one of its spreading mechanisms.  

---

## 🛡️ Mitigation
1. Apply Microsoft’s **MS17-010 security update**.  
2. Disable **SMBv1 protocol** where possible.  
3. Use modern operating systems and keep them up to date.  
4. Implement network-level protections such as IDS/IPS to detect SMB exploitation attempts.  

---

## 📚 References
- [Microsoft Security Bulletin MS17-010](https://learn.microsoft.com/en-us/security-updates/securitybulletins/2017/ms17-010)  
- [CVE-2017-0144 – NVD](https://nvd.nist.gov/vuln/detail/CVE-2017-0144)  
- [WannaCry Ransomware Attack (Wikipedia)](https://en.wikipedia.org/wiki/WannaCry_ransomware_attack)  
- [NotPetya Cyberattack (Wikipedia)](https://en.wikipedia.org/wiki/2017_cyberattacks_on_Ukraine)  

---

## ✅ Educational Purpose
This repository is intended for:  
- Cybersecurity students  
- Ethical hackers  
- Researchers  
- IT administrators learning from past vulnerabilities  

⚡ **Remember:** Security through knowledge, not exploitation.
