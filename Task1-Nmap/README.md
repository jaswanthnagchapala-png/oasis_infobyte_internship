# Task 1 - Network Port Scanning with Nmap

## Objective
The objective of this task is to perform network reconnaissance using Nmap and identify open ports and available services on a target system.

---

## Tool Used
- Nmap 7.98
- Kali Linux

---

## Commands Executed

### 1. Verify Nmap Installation

```bash
nmap --version
```

### Output
Nmap version 7.98 was successfully installed and available on the system.

---

### 2. Basic Port Scan

```bash
nmap 127.0.0.1
```

### Purpose
This command scans the localhost machine and checks for open TCP ports.

### Observation
- Host was reachable.
- No open TCP ports were found.
- All scanned ports were in closed state.

---

### 3. Service Version Detection

```bash
nmap -sV 127.0.0.1
```

### Purpose
This command attempts to identify service versions running on discovered ports.

### Observation
- Host was reachable.
- No active services were detected because no open ports were available.

---

## Screenshots

### Nmap Version Verification
See:

Pictures/nmap_version.png

### Basic Scan Result
See:

Pictures/nmap_scan.png

### Service Detection Scan
See:

Pictures/nmap_service_scan.png

---

## Results

| Scan Type | Result |
|------------|----------|
| Version Check | Successful |
| Basic Port Scan | Host reachable |
| Open Ports | None |
| Service Detection | Completed |
| Services Found | None |

---

## Conclusion

Nmap was successfully installed and used to perform network scanning on the localhost system. The scans confirmed that the target host was active, but no open TCP ports or running services were detected. This task demonstrates the basic usage of Nmap for reconnaissance and service discovery.

---

## Skills Learned

- Network Reconnaissance
- Port Scanning
- Service Enumeration
- Cybersecurity Documentation
- Nmap Usage
