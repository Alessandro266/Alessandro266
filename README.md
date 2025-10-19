# Incident Response Exercise-

### TryHackMe
### Alessandro Di Giovanni
### ITECH1502 


---

## Project Summary
- **The Project:** demonstrates a hands-on incident response exercise completed on the TryHackMe 
- **The activity:** simulated a real-world cybersecurity investigation focused on detecting and removing a malicious file from a Windows system
- **The goal:** was to apply incident response steps in a controlled environment while developing practical investigation skills and also analysis skills

---

## Learning Objectives
- Understand the steps of the incident response process
- Detect and analyse suspicious files
- Investigate registry entries linked to malware
- Apply safe remediation techniques

---

## Tools & Platforms Used
- TryHackMe (Incident Response Room)
- Windows Task Manager
- Microsoft Word (View Macros)
- Windows Registry and Editor

---

## Screenshots / Evidence
### 1. Task Manager – Suspicious Process
This screenshot shows the unknown process identified in Task Manager that indicated unusual activity.


### 2. Downloads Folder – Suspicious File
Here we traced the malicious file to the Downloads folder in Microsoft Edge. The file was a .docm Word document.


### 3. Macro Analysis
Using the "View Macros" function in Word, we confirmed the file contained an active macro.


### 4. Registry Entry – Persistence
The malicious file had added a registry key named default app to automatically execute on startup.



---

## Reflection
- This exercise helped me gain hands-on experience in identifying malicious behaviour and understanding how threats persist in systems
- It strengthened my technical and analytical skills, which are essential for future roles in incident response and SOC environments

---

## 📎 Related Files
- [Project Report (PDF)](link-to-your-report.pdf)
- [Presentation Slides (PPTX)](link-to-your-presentation.pptx)
