# Wazuh SOC Lab: Threat Detection & Incident Response

Hands-on SOC lab built around Wazuh SIEM/XDR, with three attack-and-detection exercises, each documented in a formal report.

> **Lab environment only.** All attacks were run against intentionally vulnerable systems that I own or was authorized to test. No real targets.

## Reports

| # | Report | What it covers |
|---|---|---|
| 1 | [Wazuh SOC: Threat Detection & Incident Response](01-wazuh-soc-lab.pdf) | Wazuh manager, indexer and dashboard; Linux and Windows agents; email alerting; Nmap and Hydra detection tests (512 failed-authentication events, 52 high-severity alerts, MITRE ATT&CK T1110); source-IP identification and UFW containment |
| 2 | [Insider-Threat Kill Chain Simulation](02-insider-threat-kill-chain.pdf) | Privilege escalation via sudo misconfiguration, cron persistence, SCP exfiltration and log tampering, mapped to MITRE ATT&CK and checked against Wazuh detections; encrypted-exfiltration gap and recommendations |
| 3 | [Web Attack Detection Validation (DVWA)](03-web-attack-detection-dvwa.pdf) | DVWA on Apache/PHP/MySQL with web logs in Wazuh; Gobuster, brute force and SQL injection (manual and sqlmap) and the alerts they produce |

## Tools
Wazuh, Kali Linux, Nmap, Hydra, Gobuster, sqlmap, DVWA, UFW, MITRE ATT&CK

## Author
**Younes Belayouni**, Cybersecurity Engineering student, Ecole Polytechnique de Sousse
[LinkedIn](https://www.linkedin.com/in/younes-belayouni-5b26033a6) | [TryHackMe](https://tryhackme.com/p/wanassi)
