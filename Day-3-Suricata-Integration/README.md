# Day 3 – Suricata Integration

## Objective

Integrate Suricata with Wazuh to detect and monitor network-based threats.

## Lab Environment

- Ubuntu
- Wazuh Manager
- Suricata IDS

## Steps Performed

1. Installed Suricata.
2. Verified that Suricata was generating logs.
3. Configured Wazuh to ingest Suricata's `eve.json` logs.
4. Restarted the Wazuh Manager.
5. Triggered network activity to generate alerts.
6. Verified Suricata alerts in the Wazuh Dashboard.

## Detection Results

- Network intrusion events detected.
- Suricata logs successfully forwarded to Wazuh.
- Alerts visible in the Wazuh Dashboard.

## Key Learning

- Learned how to integrate Suricata with Wazuh.
- Understood how Suricata network events are processed by Wazuh.
- Practiced analyzing IDS alerts within the SIEM dashboard.

## Progress

| Day | Topic | Status |
|------|-------|--------|
| Day 1 | Wazuh Installation | ✅ |
| Day 2 | File Integrity Monitoring | ✅ |
| Day 3 | Suricata Integration | ✅ |
| Day 4 | Auditd Monitoring | ⏳ |
| Day 5 | SSH Brute Force Detection | ⏳ |
| Day 6 | Active Response | ⏳ |
| Day 7 | Sysmon Integration | ⏳ |
