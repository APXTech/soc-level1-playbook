# SIEM Alert Triage (SOC Level 1)

## 🎯 Scenario
A security alert is generated in SIEM indicating suspicious activity such as login anomalies, malware detection, or unusual network behavior.

---

## 🔍 Alert Types

- Multiple failed login attempts
- Privilege escalation attempts
- Unusual geographic login
- Malware detection alerts
- Suspicious outbound traffic

---

## 🧠 Triage Process

### 1. Alert Validation
- Confirm alert is not false positive
- Check severity level (Low / Medium / High / Critical)

### 2. Log Correlation
- Correlate with firewall logs
- Check Windows Event Logs
- Analyze endpoint logs

### 3. User Analysis
- Identify affected user/system
- Check login history
- Validate access patterns

### 4. Threat Context
- Check IP reputation
- Verify against threat intelligence feeds
- Analyze attack pattern

---

## 🚨 Response Actions

- Escalate critical alerts immediately
- Block malicious IPs/domains
- Disable compromised accounts
- Isolate affected endpoints if required

---

## 🛠 Tools Used

- Seceon SIEM
- Sophos / Fortinet Firewall
- Windows Event Viewer
- Wireshark
- Threat Intelligence Platforms

---

## 📊 Escalation Rules

Escalate immediately if:
- Data exfiltration suspected
- Multiple systems affected
- Privilege escalation confirmed
- Ransomware indicators detected

---

## 📝 Outcome

- Reduced false positives
- Faster incident response
- Improved SOC efficiency
