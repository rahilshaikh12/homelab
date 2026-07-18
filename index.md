---
layout: home
title: Centralized Threat Detection & NSM Architecture
---

Welcome to my Network Security Monitoring (NSM) lab documentation. To bridge the gap between theoretical security concepts and hands-on detection engineering, I architected and deployed this security stack from the ground up.

This project details the complete deployment pipeline for **Wazuh (SIEM)**, **Suricata (IDS)**, and **Zeek (NSM)**. Rather than relying solely on simple virtualized networks, this lab focuses heavily on robust defensive infrastructure, highlighting the physical Port Mirroring (SPAN) configurations, VLAN segregation, and stealth interfaces required to safely capture and analyze raw internet traffic.

### Navigation Guide

This documentation is structured as a start-to-finish engineering report. To follow the deployment process logically, from the initial infrastructure design through to sensor validation and SIEM integration, **please use the navigation bar at the top of the page and proceed chronologically from left to right.**

**Security & Deployment Disclaimer**
This architecture was designed strictly as an educational home lab to practice threat detection and security engineering. Placing sensors directly on the WAN edge and capturing raw internet traffic introduces inherent risks. While I implemented logical isolations—such as strict VLAN segregation and disabling IP bindings on the capture interfaces—this setup is not a production-grade enterprise guide. If you replicate this topology, you do so at your own risk.
