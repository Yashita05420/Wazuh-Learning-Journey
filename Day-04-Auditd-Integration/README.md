# Day 4 – Auditd Integration

## Objective

Integrate Auditd with Wazuh to monitor Linux audit events and analyze them through the Wazuh Dashboard.

## Lab Environment

- Ubuntu
- Wazuh Manager
- Wazuh Agent
- Auditd

## Steps Performed

1. Installed and started Auditd.
2. Configured audit rules to monitor system activity.
3. Generated audit events.
4. Verified Auditd logs on the endpoint.
5. Confirmed that Wazuh collected and displayed the Auditd events.

## Detection Results

- Audit events successfully generated.
- Wazuh ingested Auditd logs.
- Security events were visible in the Wazuh Dashboard.

## Key Learning

- Learned how Auditd records Linux system events.
- Verified successful integration between Auditd and Wazuh.
- Practiced monitoring Linux security events using a SIEM.

  ## Progress

| Day | Topic | Status |
|------|-------|--------|
| Day 1 | Wazuh Installation | ✅ |
| Day 2 | File Integrity Monitoring | ✅ |
| Day 3 | Suricata Integration | ✅ |
| Day 4 | Auditd Monitoring | ✅ |
| Day 5 | SSH Brute Force Detection | ⏳ |
| Day 6 | Active Response | ⏳ |
| Day 7 | Sysmon Integration | ⏳ |
