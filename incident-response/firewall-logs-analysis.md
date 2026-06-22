# Firewall Log Analysis (SOC Level 1)

## 🎯 Scenario
Suspicious network activity detected through firewall logs such as unauthorized access attempts, blocked traffic spikes, or abnormal outbound connections.

---

## 🔍 Log Indicators

- Multiple failed login attempts
- Blocked IP addresses repeatedly hitting firewall
- Unusual port scanning activity
- High outbound traffic to unknown IPs
- Geo-location anomalies

---

## 🧠 Investigation Steps

1. Identify source and destination IPs
2. Analyze frequency of requests
3. Check port and protocol usage
4. Correlate with SIEM alerts
5. Validate against threat intelligence feeds

---

## 🚨 Response Actions

- Block suspicious IPs at firewall level
- Restrict access to affected ports/services
- Enable IPS rules for detection prevention
- Notify SOC team for escalation if required

---

## 🛠 Tools Used

- Sophos Firewall
- Fortinet Firewall
- Seceon SIEM
- Wireshark
- Nmap
- Threat Intelligence Feeds

---

## 📊 Escalation Criteria

Escalate if:
- Persistent attack from multiple IPs
- Internal system compromise suspected
- Data exfiltration indicators found
- Critical service disruption occurs

---

## 📝 Outcome

- Improved network visibility
- Faster detection of malicious traffic
- Strengthened firewall policies
