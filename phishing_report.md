# Phishing Simulation Report

**Date:** May 7, 2025  
**Conducted by:** Internal Security Team  
**Tools Used:** Gophish, SET (Social Engineering Toolkit), Mailtrap

---

## 1. Objective

Simulate a phishing campaign to test user susceptibility to credential theft and enhance organizational cybersecurity posture.

---

## 2. Attack Vector

- **Email Subject:** ACTION REQUIRED: Immediate Password Reset Required
- **From:** IT Support <support@yourcompany.com>
- **Landing Page:** Microsoft login spoofed using SET
- **Tracking:** Gophish links and credential capture logs

---

## 3. Execution Steps

1. **SET** used to clone the Microsoft login page.
2. Hosted phishing page locally and integrated with Gophish as landing URL.
3. Configured Mailtrap SMTP in Gophish.
4. Created a campaign targeting 5 test users.
5. Sent emails and monitored interactions.

---

## 4. Results

| First Name | Last Name | Email              | Status          | Reported |
|------------|-----------|--------------------|-----------------|----------|
| Alice      | Smith     | alice@yourlab.com  | Clicked Link    | ❌        |
| Bob        | Jones     | bob@yourlab.com    | Submitted Data  | ❌        |
| Coco       | Bongo     | coco@yourlab.com   | Submitted Data  | ❌        |
| Hello      | World     | hello@yourlab.com  | Submitted Data  | ❌        |
| Shami      | Nitra     | shami@yourlab.com  | Submitted Data  | ❌        |

---

## 5. Analysis

- 100% open rate.
- 80% (4 out of 5) submitted credentials.
- None of the users reported the phishing attempt.

---

## 6. Recommendations

- Mandatory phishing training and simulations.
- Awareness campaigns using real-world examples.
- Enforce MFA to limit impact of compromised credentials.

---

## 7. Screenshots

Refer to `/screenshots/` for email preview and results page from Gophish.