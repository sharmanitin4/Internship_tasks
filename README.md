# InsightOps Cyber Security Internship 2026

## Overview

This repository contains the work completed during my Cyber Security Internship at InsightOps from **1 May 2026 to 31 May 2026**.

The internship focused on practical cybersecurity concepts including:

* Network Reconnaissance
* Web Application Enumeration
* Network Traffic Analysis
* Password Cracking
* Binary Analysis
* Reverse Shell Exploitation
* Virtual Lab Setup

---

# Intern Information

| Field      | Details                                         |
| ---------- | ----------------------------------------------- |
| Name       | Nitin Kumar Sharma                              |
| University | Purnima Institute of Engineering and Technology |
| Major      | Computer Science and Engineering                |
| Company    | InsightOps                                      |
| Domain     | Cyber Security                                  |
| Duration   | 1 May 2026 - 31 May 2026                        |

---

# Lab Environment

## Attacker Machine

* Kali Linux
* Host-Only Network Configuration

## Victim Machine

* Windows 11 Virtual Machine
* Connected to Kali through Host-Only Adapter

## Tools Used

* Nmap
* Gobuster
* Wireshark
* John The Ripper
* VeraCrypt
* PE Explorer
* Metasploit Framework
* Apache2
* VirtualBox

---

# Internship Tasks

## Beginner Level

### Task 1 - Open Port Discovery

#### Objective

Identify open ports and running services on the target web application.

#### Tools Used

* Nmap

#### Methodology

1. Performed reconnaissance against the target website.
2. Executed service detection scan.
3. Identified available ports and services.
4. Documented scan results.

#### Outcome

Successfully identified exposed services and open ports available on the target host.

#### Evidence

Screenshots available in:

```text
Beginner-Level/Task-01-Port-Scanning/screenshots
```

---

### Task 2 - Directory Enumeration

#### Objective

Discover hidden directories and resources exposed by the target application.

#### Tools Used

* Gobuster

#### Methodology

1. Configured Gobuster using a common wordlist.
2. Initiated directory brute-force scan.
3. Analyzed HTTP response codes.
4. Recorded accessible resources.

#### Outcome

Successfully enumerated multiple directories and publicly accessible resources.

#### Evidence

```text
Beginner-Level/Task-02-Directory-Enumeration/screenshots
```

---

### Task 3 - Credential Capture Using Wireshark

#### Objective

Analyze network traffic and observe credential transmission.

#### Tools Used

* Wireshark

#### Methodology

1. Started packet capture.
2. Generated login traffic.
3. Filtered HTTP POST requests.
4. Reconstructed HTTP streams.
5. Analyzed transmitted credentials.

#### Outcome

Successfully observed credentials transmitted through unencrypted HTTP communication.

#### Evidence

```text
Beginner-Level/Task-03-Credential-Capture-Wireshark/screenshots
```

---

# Intermediate Level

### Task 4 - VeraCrypt Password Recovery

#### Objective

Recover the password protecting an encrypted VeraCrypt volume.

#### Tools Used

* John The Ripper
* VeraCrypt
* RockYou Wordlist

#### Methodology

1. Extracted provided hash.
2. Performed dictionary attack.
3. Recovered plaintext password.
4. Mounted encrypted container.
5. Retrieved secret code.

#### Outcome

Successfully unlocked encrypted storage and accessed protected information.

#### Evidence

```text
Intermediate-Level/Task-01-VeraCrypt-Hash-Cracking/screenshots
```

---

### Task 5 - PE Explorer Analysis

#### Objective

Perform static analysis on a Windows executable.

#### Tools Used

* PE Explorer

#### Methodology

1. Loaded executable into PE Explorer.
2. Examined PE Header information.
3. Identified Address Of Entry Point.
4. Documented findings.

#### Outcome

Successfully analyzed executable metadata and identified entry point information.

#### Evidence

```text
Intermediate-Level/Task-02-PE-Explorer-Analysis/screenshots
```

---

### Task 6 - Reverse Shell Establishment

#### Objective

Establish a Meterpreter reverse shell connection in a controlled laboratory environment.

#### Tools Used

* Metasploit Framework
* msfvenom
* Apache2

#### Methodology

1. Configured isolated lab environment.
2. Generated payload using msfvenom.
3. Hosted payload on Apache web server.
4. Configured Metasploit handler.
5. Executed payload on victim machine.
6. Established Meterpreter session.

#### Outcome

Successfully obtained remote command execution on the target virtual machine.

#### Evidence

```text
Intermediate-Level/Task-03-Metasploit-Reverse-Shell/screenshots
```

---

# Skills Acquired

## Technical Skills

* Network Reconnaissance
* Service Enumeration
* Directory Discovery
* Packet Analysis
* Password Cracking
* Cryptographic Concepts
* Binary Analysis
* Reverse Shell Operations
* Meterpreter Usage
* Virtual Lab Deployment

## Professional Skills

* Technical Documentation
* Problem Solving
* Troubleshooting
* Security Research
* Analytical Thinking

---

# Repository Structure

```text
InsightOps-CyberSecurity-Internship-2026
│
├── README.md
│
├── Final-Report
│   └── Internship_Final_Report_Nitin_Kumar_Sharma.pdf
│
├── Beginner-Level
│   ├── Task-01-Port-Scanning
│   ├── Task-02-Directory-Enumeration
│   └── Task-03-Credential-Capture-Wireshark
│
├── Intermediate-Level
│   ├── Task-01-VeraCrypt-Hash-Cracking
│   ├── Task-02-PE-Explorer-Analysis
│   └── Task-03-Metasploit-Reverse-Shell
│
└── Assets
```

---

# Disclaimer

All activities documented in this repository were performed exclusively within authorized laboratory environments and intentionally vulnerable systems provided for educational and training purposes.

No unauthorized systems, networks, or applications were targeted.

---

# Conclusion

This internship provided practical exposure to multiple cybersecurity domains including network security, web application security, cryptography, binary analysis, and exploitation techniques. The tasks helped bridge the gap between theoretical knowledge and practical implementation while strengthening problem-solving and analytical skills required in cybersecurity roles.
