# Task 7 - Web Vulnerability Scanning Using Nikto

## Objective

The objective of this task is to perform a basic web vulnerability assessment using Nikto, an open-source web server scanner, and understand how vulnerability scanning tools are used in cybersecurity.

---

## Tool Used

- Nikto 2.6.0
- Kali Linux

---

## About Nikto

Nikto is an open-source web vulnerability scanner that performs comprehensive tests against web servers. It checks for outdated software, insecure configurations, default files, and known vulnerabilities.

---

## Commands Executed

### 1. Verify Nikto Installation

```bash
nikto -Version
```

### 2. Perform Vulnerability Scan on Localhost

```bash
nikto -h http://127.0.0.1
```
