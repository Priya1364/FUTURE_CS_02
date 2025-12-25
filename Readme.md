# 🛡️ Security Alert Monitoring & Incident Response – Task 2

This project is part of the **Future Interns Cyber Security Internship**.

The objective of this task is to monitor security logs, detect suspicious activity, classify incidents, and document the response.

---

## 🧰 Tools Used
- Sample Linux authentication logs  
- Manual log analysis  

---

## 📂 Log Source
The file `authentication_failed` contains authentication and SSH login events from a Linux server.

---

## 🚨 Incident Detected
The log file shows **approximately 300 authentication failures** from external IP addresses.  
This indicates a **brute-force attack** targeting user and root accounts over SSH.

Some sessions were opened and closed, meaning attackers attempted to gain access to the system.

---

## 📄 Files in this Repository
- `authentication_failed` – Log file containing failed and suspicious login attempts  
- `Task2-Incident-Report.pdf` – Detailed incident response report  
- `README.md` – Project explanation  

---

## 🔐 Security Recommendations
- Block malicious IP addresses  
- Enable account lockout  
- Use strong passwords  
- Enable Multi-Factor Authentication  
- Monitor logs continuously  

---

## ✅ Conclusion
This task demonstrates the ability to detect real-world attacks using security logs and perform basic SOC-level incident response.
