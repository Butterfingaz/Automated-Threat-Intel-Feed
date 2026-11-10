# Automated-Threat-Intel-Feed
Programmatic Threat Intelligence Ingestion & Firewall Automation Pipeline

## 1. Project Overview
This project demonstrates automated cyber threat intelligence collection and defensive engineering. A custom Python script was constructed to parse Indicators of Compromise (IoCs) associated with active malware infrastructure networks, and programmatically translate them into production-ready firewall access-control list drop rules.

## 2. Technical Capabilities Demonstrated
* **Structured Data Processing:** Manipulation of threat data models using automated dictionary iterations.
* **Defensive Automation:** Seamless generation of native enterprise host-hardening blocks (`iptables` layer).
* **Operational Scale:** Elimination of manual string-parsing for Security Operations Center (SOC) engineers.

## 3. Operational Verification
Executing the pipeline utility automatically processes identified threat matrix vectors:
```bash
python3 fetch_threat_intel.py
```

### 📊 Automation Console & Firewall Output Proof

1. <img width="892" height="465" alt="fetch threat intel" src="https://github.com/user-attachments/assets/31a5fea0-8104-4a38-8d36-8f66cb79c1aa" />

2. <img width="886" height="256" alt="Running fetch threat" src="https://github.com/user-attachments/assets/5f1734be-e9de-4126-a5dc-eebbe5928591" />

3. <img width="888" height="204" alt="blocklist_firewall_rules" src="https://github.com/user-attachments/assets/e1b7df49-a0fa-4303-987e-44041bbb5821" />

4. <img width="874" height="68" alt="system clean up" src="https://github.com/user-attachments/assets/c17dbb81-0112-45b3-a48f-ec74da302387" />


The engine dynamically maps raw indicators directly to infrastructure policy controls, preventing data exfiltration traps instantly.
