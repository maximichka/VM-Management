# Vulnerability Management Project - Nessus Essentials

## Project Overview

This project documents my hands-on experience with vulnerability management using Nessus Essentials, Kali Linux, and Metasploitable 2. Following the ShellSharks Vulnerability Management Bootcamp, I configured a lab environment, performed credentialed and uncredentialed vulnerability scans, analyzed security findings, prioritized remediation recommendations, and developed a basic Python script to interact with the Nessus REST API.

The goal of this project was to gain practical experience identifying, assessing, and reporting vulnerabilities in a controlled lab environment.

## Tools & Technologies

- **Nessus Essentials** – Vulnerability scanning and analysis
- **Kali Linux** – Security testing environment
- **Metasploitable 2** – Intentionally vulnerable target machine
- **VirtualBox / VMware** – Virtual machine environment
- **Python** – Basic scripting and automation
- **Nessus REST API** – Programmatic retrieval of vulnerability scan information
- **GitHub** – Project documentation and evidence

## Lab Exercises

### Exercise 0 – Lab Setup

Configured the virtual lab environment for vulnerability management testing.

### Exercise 1 – Getting Started

Explored the lab environment and prepared the tools needed for vulnerability scanning.

### Exercise 2 – Discovery Scanning

Performed host discovery to identify the target system.

### Exercise 3 – Vulnerability Scanning

Performed credentialed and uncredentialed Nessus scans against Metasploitable 2.

### Exercise 4 – Scanning Enrichment

Explored Nessus scan configuration, scheduling, notifications, and advanced settings.

### Exercise 5 – Vulnerability Analysis

Analyzed scan results, identified exploitable vulnerabilities, and reviewed remediation priorities.

### Exercise 6 – Reporting

Explored vulnerability reporting and how findings can be communicated to stakeholders.

### Exercise 7 – Scripting & Automation

Built and tested a basic Python script with AI assistance to interact with the Nessus REST API. Troubleshot syntax errors, configured API authentication, and successfully retrieved existing vulnerability scans.

## Key Findings & Lessons Learned

- Learned the differences between credentialed and uncredentialed vulnerability scans.
- Identified critical vulnerabilities, including Shellshock and weak SSH encryption keys.
- Used CVSS, VPR, and EPSS scores to evaluate and prioritize vulnerabilities.
- Reviewed Nessus remediation recommendations and identified patching priorities.
- Explored scan scheduling, notifications, reporting, and configuration options.
- Practiced troubleshooting Python errors and using the Nessus REST API.
- Learned how vulnerability reports can help IT teams and security leadership make remediation decisions.

### Notable Vulnerabilities and Recommended Remediation

| Vulnerability | Severity | CVSS | Recommended Remediation |
|---|---|---|---|
| Bash Remote Code Execution (Shellshock) | Critical | 9.8 | Update Bash to a patched version. |
| Weak Debian OpenSSH Keys | Critical | 9.8 | Replace vulnerable SSH keys and update affected systems. |
| VNC Server Weak Password | Critical | 10.0 | Replace the weak password and restrict access to VNC. |

### Credentialed vs. Uncredentialed Scan Comparison

- **Uncredentialed scan:** 64 vulnerability entries identified.
- **Credentialed scan:** 86 vulnerability entries identified.
- Credentialed scanning provided additional visibility into system vulnerabilities that were not identified through unauthenticated scanning.

These findings were identified in an intentionally vulnerable lab environment. Remediation actions were recommended but not implemented as part of this exercise.

## Project Reference

This project was completed as part of the [ShellSharks Vulnerability Management Bootcamp](https://shellsharks.com/vm-bootcamp).

All scanning and testing were performed in a controlled lab environment using an intentionally vulnerable virtual machine.

## Exercise Navigation

[Exercise 1](Exercise-1/)

[Exercise 2](Exercise-2/)

[Exercise 3](Exercise-3/)

[Exercise 4](Exercise-4/)

[Exercise 5](Exercise-5/)

[Exercise 6](Exercise-6/)

[Exercise 7](Exercise-7/)
