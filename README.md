# INE-eCTHP-Exam-Guide-Study-Guide-Certified-Threat-Hunting-Professional
Practical INE eCTHP study guide covering threat hunting methodology, CTI, network and endpoint hunting, Wireshark, Splunk, ELK, IOC analysis, labs, and exam preparation.
# INE eCTHP – Certified Threat Hunting Professional Study Guide

Welcome to this practical, community-driven study repository for the **INE Certified Threat Hunting Professional (eCTHP)** certification.

The eCTHP is designed around real-world threat-hunting activities rather than a traditional multiple-choice testing format. Candidates work through a simulated enterprise environment and investigate threats using network traffic, endpoint data, threat intelligence, indicators of compromise, and investigative tooling.

This guide is intended to help cybersecurity professionals build the technical knowledge and practical reasoning needed for the eCTHP certification.

> **Certification:** Certified Threat Hunting Professional  
> **Exam Code:** eCTHP  
> **Provider:** INE Security  
> **Level:** Professional  
> **Focus:** Threat Hunting, Network Analysis, Endpoint Analysis, CTI, IOC Investigation

---

## Table of Contents

- [About This Repository](#about-this-repository)
- [What Is the INE eCTHP?](#what-is-the-ine-ecthp)
- [Who Should Take eCTHP?](#who-should-take-ecthp)
- [How the eCTHP Exam Works](#how-the-ecthp-exam-works)
- [Exam Domains](#exam-domains)
- [Domain 1: Threat Hunting Methodology](#domain-1-threat-hunting-methodology)
- [Domain 2: Threat Hunting Strategies](#domain-2-threat-hunting-strategies)
- [Domain 3: Cyber Threat Intelligence](#domain-3-cyber-threat-intelligence)
- [Domain 4: Network Threat Hunting](#domain-4-network-threat-hunting)
- [Domain 5: Endpoint Threat Hunting](#domain-5-endpoint-threat-hunting)
- [MITRE ATT&CK for Threat Hunters](#mitre-attck-for-threat-hunters)
- [Cyber Kill Chain](#cyber-kill-chain)
- [IOC Analysis](#ioc-analysis)
- [Threat Hunting Workflow](#threat-hunting-workflow)
- [Wireshark Study Notes](#wireshark-study-notes)
- [tcpdump Study Notes](#tcpdump-study-notes)
- [Splunk and ELK Hunting](#splunk-and-elk-hunting)
- [Windows Threat Hunting](#windows-threat-hunting)
- [Linux Threat Hunting](#linux-threat-hunting)
- [Practical Hunting Labs](#practical-hunting-labs)
- [30-Day Study Plan](#30-day-study-plan)
- [Common Mistakes](#common-mistakes)
- [Exam Preparation Tips](#exam-preparation-tips)
- [Final Checklist](#final-checklist)
- [Official Resources](#official-resources)
- [eCTHP Exam Voucher](#ecthp-exam-voucher)
- [Disclaimer](#disclaimer)

---

# About This Repository

Threat hunting is fundamentally different from waiting for an alert.

A traditional security workflow may look like:

```text
Alert
  |
  v
Investigate
  |
  v
Respond
