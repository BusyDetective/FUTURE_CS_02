# FUTURE_CS_02

## 📌 Project: Social Engineering & Phishing Simulation

This repository contains the setup, execution, and findings of a phishing simulation project designed to assess employee awareness and improve cybersecurity training.

---

## 🎯 Objective

To simulate real-world phishing attacks using **Gophish** and **SET (Social Engineering Toolkit)** to evaluate how targets interact with malicious emails.

---

## 🛠️ Tools Used

- **Gophish** - Phishing simulation framework to send and track emails.
- **SET (Social Engineering Toolkit)** - Used to generate realistic phishing pages and capture credentials.
- **Mailtrap** - Used for email sandbox testing.
- **Kali Linux** - Host OS for running Gophish and SET.

---

## 🧪 Simulation Setup

- **Phishing Email Template:** “Immediate Password Reset Required”
- **Landing Page:** Microsoft login clone (via SET)
- **Payload Delivery:** Email sent via Gophish using Mailtrap SMTP
- **Recipients:** 5 test users at domain `yourlab.com`

---

## 📈 Results Summary

| User             | Email                | Status           | Reported |
|------------------|----------------------|------------------|----------|
| Alice Smith      | alice@yourlab.com    | Clicked Link     | ❌        |
| Bob Jones        | bob@yourlab.com      | Submitted Data   | ❌        |
| Coco Bongo       | coco@yourlab.com     | Submitted Data   | ❌        |
| Hello World      | hello@yourlab.com    | Submitted Data   | ❌        |
| Shami Nitra      | shami@yourlab.com    | Submitted Data   | ❌        |

---

## 📌 Recommendations

1. **Security Awareness Training**
   - Educate staff on recognizing phishing emails and suspicious links.

2. **Phishing Reporting**
   - Implement a "Report Phishing" button in email clients.

3. **Multi-Factor Authentication (MFA)**
   - Prevent access even if credentials are stolen.

4. **Regular Simulations**
   - Run quarterly phishing tests to improve awareness.

---

## 📂 Files

- `phishing_report.md` - Detailed campaign findings.
- `templates/` - Email and landing page templates.
- `screenshots/` - Campaign screenshots and results.