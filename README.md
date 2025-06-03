<h1>🏢 Active Directory Home Lab (Windows Server)</h1>

### 📺 [Watch YouTube Setup Walkthrough](https://www.youtube.com/watch?v=YOUR_VIDEO_1)

---

<h2>📄 Project Overview</h2>

This project demonstrates the setup of a **Windows Server-based Active Directory (AD) Lab**—designed to replicate a real-world enterprise domain environment. It's ideal for cybersecurity professionals, system administrators, and students aiming to learn or demonstrate:

- Domain management and Group Policy application  
- Secure user and group administration  
- Enterprise network architecture principles  

This lab environment serves as a foundational platform for experimenting with identity access management, domain security, automation, and SIEM integration.

---

<h2>🧩 Key Components</h2>

- **Domain Controller Setup**  
  Configure a Windows Server machine as a primary domain controller (DC) to manage authentication and network policies.

- **User & Group Management**  
  Create and organize users, groups, and Organizational Units (OUs) that mimic an enterprise organizational structure.

- **Group Policy Implementation**  
  Apply security and operational policies to users and machines via Group Policy Objects (GPOs), including password policies, software restrictions, and login restrictions.

---

<h2>🔧 Tools & Technologies Used</h2>

- **Windows Server 2019 / 2022**  
- **Active Directory Domain Services (AD DS)**  
- **Group Policy Management Console (GPMC)**  
- **PowerShell (optional scripting/automation)**

---

<h2>🛠️ Environment Setup</h2>

- Host OS: Windows 10/11 or Linux (using VirtualBox/VMware)  
- Guest VM(s): Windows Server (domain controller), Windows 10 (client machines)  
- Network Mode: Internal/Host-Only (isolated lab network)  

---

<h2>📈 Advanced Recommendations & Security Guidance</h2>

- 🔐 **Enhance Security**  
  Use the [Microsoft Security Compliance Toolkit](https://www.microsoft.com/en-us/download/details.aspx?id=55319) to apply secure policy baselines to domain and client systems.

- 📋 **Integrate Logging**  
  Set up [Windows Event Forwarding (WEF)](https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-event-forwarding/windows-event-forwarding-overview) to centralize logs and monitor activities across the domain.

- 📊 **Explore SIEM Integration**  
  Forward logs to a SIEM platform (e.g., Splunk, Graylog, or ELK Stack) to detect suspicious behavior, failed logins, privilege escalations, and more.

---

<h2>🧪 Suggested Lab Scenarios</h2>

- Test GPO enforcement on client machines  
- Simulate password policy misconfigurations  
- Lock down administrative access using least privilege  
- Track lateral movement using event logs  
- Deploy security software via GPO  

---

<h2>📦 Repository Contents</h2>

- `AD_Lab_Setup.docx` – Step-by-step deployment guide  
- `Lab_Network_Topology.png` – Visual layout of the lab environment  
- `Baseline-GPOs/` – Folder with example policy templates  
- `Scripts/` – Optional PowerShell scripts to automate AD tasks  

---

<h2>📫 Connect With Me</h2>

- GitHub: [@TheSyAnalyst](https://github.com/TheSyAnalyst)  
- LinkedIn: [Cybersecurity Professional](https://www.linkedin.com/in/judewalin/)  
- YouTube: [Tech Walkthroughs](https://www.youtube.com/c/YOUR-YOUTUBE-CHANNEL)

---

> ⚠️ **Disclaimer**  
> This lab is designed for educational and professional development purposes only. Do not connect lab environments to live or production networks.

