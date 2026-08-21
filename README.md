Windows SOC Event Log Monitoring & Threat Investigation Lab
Project Overview

A hands-on Windows SOC L1 / Blue Team lab focused on endpoint log monitoring, suspicious activity generation, evidence collection, and threat investigation using native Windows logging and Sysmon.

The project demonstrates a basic SOC investigation workflow:

Generate Activity → Collect Logs → Investigate → Identify IOCs → Build Timeline → Map to MITRE ATT&CK

Lab Environment
Operating System: Windows 11
Virtualization: Oracle VirtualBox
Monitoring: Windows Event Viewer
Endpoint Telemetry: Sysmon
Investigation: Windows Event Logs + Sysmon Events
Framework: MITRE ATT&CK
Investigations

Three suspicious activities were generated and investigated:

01 — svchost.exe

Investigated a suspicious svchost.exe process creation event using Windows/Sysmon telemetry.

02 — WmiPrvSE.exe

Investigated WmiPrvSE.exe activity and examined the associated process creation evidence.

03 — PowerShell.exe

Investigated PowerShell process execution and analyzed the available event telemetry.

Evidence Collected

The project contains:

Windows/Sysmon event log evidence
.evtx event files
Investigation screenshots
Sysmon deployment evidence
Investigation notes
Final project report
Project Structure
SOC-Windows-Event-Log-Lab
│
├── 01-Lab-Setup
│   ├── Lab setup screenshots
│   └── Lab setup notes
│
├── 02-Sysmon
│   ├── Sysmon service evidence
│   └── Sysmon deployment notes
│
├── 03-Evidence
│   ├── svchost.exe evidence
│   ├── WmiPrvSE.exe evidence
│   ├── PowerShell.exe evidence
│   └── .evtx event files
│
├── 04-Investigations
│   └── SOC investigation notes
│
└── 05-Final-Report
    ├── Final report
    └── PDF report
Skills Demonstrated
Windows Event Log Analysis
Sysmon Monitoring
Process Creation Analysis
Suspicious Activity Investigation
IOC Identification
Event Timeline Analysis
PowerShell Investigation
Windows Endpoint Monitoring
Basic MITRE ATT&CK Mapping
SOC L1 Investigation Workflow
Objective

The objective of this project was to simulate a basic SOC investigation environment and demonstrate the process of detecting and investigating suspicious Windows endpoint activity using logs and endpoint telemetry.

Disclaimer

This project was created in an isolated lab environment for educational and defensive cybersecurity purposes.
