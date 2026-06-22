# Phishing Incident Response Playbook

## 🎯 Scenario
A user reports a suspicious email asking for login credentials or contains a malicious link.

---

## 🔍 Detection

Indicators:
- Unknown sender domain
- Urgent language ("verify immediately")
- Suspicious URL links
- Email attachment (.exe, .zip, .html)

---

## 🧠 Investigation Steps

1. Check email headers for spoofing
2. Analyze URL reputation (VirusTotal / browser inspection)
3. Verify sender domain authenticity
4. Check SIEM logs for user interaction
5. Identify affected users

---

## 🚨 Containment

- Block sender domain at firewall level (Sophos / Fortinet)
- Remove email from all user inboxes
- Reset credentials if clicked
- Force MFA re-authentication

---

## 🛠 Tools Used

- SIEM (Seceon)
- Firewall (Sophos / Fortinet)
- Email Security Gateway
- VirusTotal
- Windows Event Logs

---

## 📊 Escalation

Escalate to L2 if:
- Credentials compromised
- Malware download confirmed
- Multiple users affected

---

## 📝 Lesson Learned

- Improve email filtering rules
- Conduct user awareness training
- Update threat intelligence feeds
