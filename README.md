# 📧 Phishing Email Analysis - Cybersecurity Task

This project is part of a cybersecurity internship task to analyze a phishing email and identify malicious indicators through email header inspection, link analysis, and domain investigation.

---

## 📝 Objective

- Identify phishing traits in a sample email
- Learn to analyze email headers
- Examine suspicious links and domain info
- Report findings in a structured format

---

## 📂 Files in this Repo

| File Name              | Description                                       |
|------------------------|---------------------------------------------------|
| `phishing_email.eml`   | The raw sample phishing email                    |
| `header_analysis.txt`  | Extracted headers from the email (analyzed online) |
| `whois_output.txt`     | Whois output for the suspicious link's domain    |
| `virustotal_result.png`| Screenshot of VirusTotal scan                    |
| `report.md`            | Full phishing analysis report                    |
| `README.md`            | This project overview                            |

---

## 🛠 Tools Used

- **Google Header Analyzer** - for analyzing email headers  
- **VirusTotal** - to scan the phishing link  
- **WHOIS (Linux)** - to check domain registration details  
- **Nano/VSCode/Git** - to build and manage the project  

---

## 📌 Key Findings

- Spoofed email sender (`support@paypa1.com`)
- Urgent language and threats used
- Suspicious domain not registered (or recently registered)
- Link flagged as phishing on VirusTotal

---

## 🚀 How to Run

You can inspect the files manually or run these Linux commands:
```bash
cat phishing_email.eml
cat whois_output.txt
