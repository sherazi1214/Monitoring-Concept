# Monitoring-Concept

## Audits & Event Logs / **[SNMP NetFlow and SCAP](https://github.com/sherazi1214/SNMP-NetFlow-and-SCAP)**

**English:**

**Audit Logs** / Event Logs are detailed records of system and user activities (login, file access, changes, errors).

They help in **accountability, compliance, troubleshooting, and forensic investigations.**

**Urdu:**
Ye ek record-keeping diary hoti hai jo har chhoti badi activity system me likhti rehti hai, taake baad me proof mile.

## Routine Log Analysis

**English:**

Regular log analysis means continuously reviewing logs to detect suspicious activities, failed login attempts, malware indicators, or system errors.

Helps in early threat detection.

**Urdu:**
Daily ya routine check karna zaroori hai warna suspicious activity miss ho sakti hai.

## Logging Challenges

**English:**

**High Volume of Logs** – Thousands/millions of entries per day.

**Noise vs Signal** – Difficult to filter important alerts.

**Storage & Retention** – Logs consume huge space.

**Standardization Issues** – Different systems create different log formats.

**False Positives** – Too many irrelevant alerts.

**Urdu:**
Bari problem ye hai ke itne zyada logs hotay hain ke asli threat ko dhoondhna tough ho jata hai.

## Syslog

**English:**

Syslog is a standard logging protocol used to collect log messages from different systems into a central server.

Provides consistency and centralized monitoring.

**Urdu:**
Ye ek common language hai jo har device apne logs bhejne ke liye use karta hai.

## Log Analysis

**English:**

Process of reviewing, interpreting, and correlating log data to identify anomalies.

Tools like Splunk, Graylog, Elastic Stack are often used.

**Urdu:**
Logs ko properly padhna aur un se clues nikalna yani analysis.

## SIEM (Security Information and Event Management)

**English:**

SIEM collects logs from multiple sources, correlates them, and provides real-time alerts, dashboards, and reports.

**Example:** Splunk, IBM QRadar, ArcSight.

**Urdu:**
Ye ek master tool hai jo alag alag systems ke logs ko jor kar ek jagah analysis karta hai.

## TIP (Threat Intelligence Platform)

**English:**

A TIP aggregates threat intelligence feeds (malicious IPs, domains, malware signatures).

Helps analysts understand new and emerging threats.

**Urdu:**
Ye tool batata hai ke duniya me naye attackers aur threats kaunse chal rahe hain.

## UEBA (User and Entity Behavior Analytics)

**English:**

UEBA monitors normal user and entity (devices, accounts) behavior.

Detects anomalies like unusual login times, excessive file downloads, or privilege abuse.

**Urdu:**
Agar user ka behavior abnormal ho jae to UEBA turant flag kar deta hai.

## SOAR (Security Orchestration, Automation, and Response)

**English:**

SOAR platforms automate incident response workflows (e.g., blocking IPs, isolating devices, sending alerts).

Integrates with SIEM, TIP, UEBA for faster response.

**Urdu:**
Yani automation tool jo attacks ka jawab turant aur automatically deta hai.

## Summary Flow (English + Roman Urdu)

**Logs** → Activity record (system diary).

**Routine Analysis** → Daily checking.

**Challenges** → Too much data, storage, false positives.

**Syslog** → Standard format.

**Log Analysis** → Finding clues.

**SIEM** → Collect + correlate + alert.

**TIP** → Global threat intelligence.

**UEBA** → Detect abnormal behavior.

SOAR → Automated response.
