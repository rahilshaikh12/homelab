---
layout: page
title: Next Steps
---

With the core infrastructure and centralized logging pipeline established, the next phase of this project shifts from architecture to active detection engineering. My upcoming focus will be validating this SIEM deployment through controlled penetration testing and adversary emulation.

## Endpoint & Network Pentesting 

I plan to systematically attack my network and endpoints to evaluate the exact level of visibility provided by Suricata, Zeek, and Wazuh. To do this safely, I will be spinning up isolated sandbox environments equipped with Wazuh agents. Within these sandboxes, I can confidently detonate payloads and execute common attack vectors—such as privilege escalation, lateral movement, and simulated malware execution—without risking the integrity of my primary network.

## Alert Analysis & SIEM Tuning 

The primary goal of these exercises is to observe exactly how different attack techniques translate into raw telemetry and SIEM alerts. By actively analyzing the resulting logs in the Wazuh dashboard, I will map the alerts to the MITRE ATT&CK framework, tune out false positives, and identify blind spots in my current configuration. This hands-on approach will allow me to write custom detection rules for any malicious behavior that bypasses the default out-of-the-box signatures, simulating the exact triage and tuning workflows used by SOC analysts.
