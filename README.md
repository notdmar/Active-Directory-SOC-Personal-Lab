# Active Directory SOC Personal Lab

## Overview
This project mimics an Active Directory infrastructure used by small businesses for incident response, threat detection, and security monitoring.
The lab was constructed with VirtualBox and uses Sysmon for endpoint telemetry and Splunk Enterprise for centralized log gathering.
## Lab Components

### Infrastructure

* Windows Server 2022 Domain Controller
* Windows 10 Client Workstation
* Active Directory Domain Services (AD DS)
* DNS Server

### Security Tools

* Splunk Enterprise
* Splunk Universal Forwarder
* Sysmon

## Network Architecture

See the diagrams folder for the network topology.

## Security Monitoring

Logs collected include:

* Windows Security Events
* Authentication Activity
* Account Creation Events
* Sysmon Process Creation Events
* PowerShell Execution Activity

## Incident Investigations

### Incident 1 – Brute Force Login Detection

* Event Number 4625
* Several unsuccessful attempts to log in were found
* Splunk was used for investigation.
## Skills Demonstrated

* Active Directory Administration
* Windows Event Logging
* Splunk Search & Analysis
* Sysmon Configuration
* Incident Response
* Threat Detection
* Security Monitoring

## Author
D'mar Hudson
Cybersecurity / SOC Analyst Portfolio Project
