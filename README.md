# SOC Analyst Home Lab

## Overview
This repository documents my hands-on SOC Analyst home lab used to develop practical skills in security monitoring, alert triage, and incident investigation. The lab is designed to simulate real-world enterprise environments and generate security events for analysis in a SIEM.

The goal of this lab is to understand how attacks and suspicious activity appear in logs, how to investigate alerts, and how to document findings in a SOC-style workflow.

## Lab Objectives
- Build and maintain a small enterprise-style environment
- Generate realistic security events
- Analyze logs in a SIEM
- Perform alert triage and incident investigation
- Create detection logic for common attack patterns
- Map activity to MITRE ATT&CK techniques
- Document findings clearly for escalation and response

## Lab Architecture
The lab includes the following components:
- Windows 10 endpoint (event generation and attack simulation)
- Ubuntu Linux server (log source and attacker simulation)
- SIEM platform (Wazuh / Splunk Free / Elastic)
- Network monitoring and packet capture (Wireshark)
- Centralized logging and alerting

A simple network diagram is included in the `/screenshots` folder.

## Folder Structure
