# Portfolio
# Active Directory & SIEM Home Lab

## Overview

This project demonstrates the design, deployment, and monitoring of a small enterprise-style Windows environment within an isolated virtual lab. The infrastructure was built to simulate a corporate Active Directory network and forms the foundation for future security operations, threat detection, and incident response exercises.

The lab consists of a Windows Server Domain Controller, domain-joined Windows workstation, and a dedicated Splunk SIEM server used to collect and analyse security events in real time.

---

## Infrastructure

| Component                      | Role                                         |
| ------------------------------ | -------------------------------------------- |
| **Windows Server 2025**        | Active Directory Domain Controller & DNS     |
| **Windows 11 Pro**             | Domain-joined client workstation             |
| **Splunk Enterprise**          | SIEM platform for centralised log collection |
| **Splunk Universal Forwarder** | Endpoint log collection                      |
| **Oracle VirtualBox**          | Virtualisation platform                      |
| **Isolated NAT Network**       | Simulated enterprise network                 |

---

## Project Highlights

### Active Directory Deployment

* Built a Windows Server 2025 Domain Controller from scratch
* Configured Active Directory Domain Services (AD DS)
* Implemented internal DNS for domain name resolution
* Created organisational units, user accounts, and computer objects
* Joined Windows 11 workstation to the domain
* Configured static IP addressing and enterprise-style network architecture

### SIEM & Security Monitoring

* Deployed Splunk Enterprise within the lab
* Configured Universal Forwarders on multiple Windows hosts
* Centralised Windows Security, System, and Application logs
* Validated successful log ingestion using Splunk Search Processing Language (SPL)
* Generated and detected failed authentication events (Windows Event ID 4625)
* Built the foundation for future threat hunting and detection engineering exercises

---

## Technologies Used

* Windows Server 2025
* Windows 11 Pro
* Active Directory
* DNS
* Splunk Enterprise
* Splunk Universal Forwarder
* Windows Event Logs
* Search Processing Language (SPL)
* Oracle VirtualBox
* Virtual Networking
* Windows Firewall
* Identity & Access Management (IAM)

---

## Skills Demonstrated

* Active Directory Administration
* Windows Server Management
* SIEM Deployment & Configuration
* Log Collection & Analysis
* Security Monitoring
* Identity & Access Management
* Windows Networking
* DNS Configuration
* Virtualisation
* Infrastructure Troubleshooting
* Incident Investigation
* Technical Documentation

---

## Business Relevance

This lab mirrors the core technologies found within many enterprise IT environments. It demonstrates practical experience deploying and supporting Microsoft infrastructure while implementing centralised security monitoring similar to that used by Security Operations Centres (SOCs).

Rather than simply installing software, this project showcases the complete lifecycle of enterprise infrastructure:

* Designing a secure Windows domain
* Managing users and authentication
* Centralising security telemetry
* Investigating authentication events
* Building infrastructure ready for vulnerability management, attack simulation, and threat detection

---

## Outcome

The completed environment provides:

* Enterprise-style Active Directory infrastructure
* Centralised identity management
* Internal DNS services
* Domain-joined Windows endpoints
* Centralised SIEM logging
* Real-time security event monitoring
* A scalable platform for future cybersecurity projects including Sysmon, Atomic Red Team, Kali Linux, Nessus, and detection engineering.

This project demonstrates practical, hands-on experience with technologies commonly used in Systems Administration, Infrastructure Engineering, Cyber Security, SOC Operations, and Blue Team environments.

