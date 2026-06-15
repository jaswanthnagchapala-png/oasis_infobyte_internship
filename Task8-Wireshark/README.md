# Task 8 - Network Traffic Analysis Using Wireshark

## Objective

Analyze network traffic using Wireshark and identify different types of packets transmitted across the network.

---

## Tool Used

* Wireshark
* Kali Linux

---

## About Wireshark

Wireshark is a network protocol analyzer used to capture and inspect packets traveling through a network. It helps security professionals analyze network communication and troubleshoot issues.

---

## Steps Performed

1. Verified Wireshark installation.
2. Started packet capture on the active network interface.
3. Generated network traffic by browsing websites.
4. Applied protocol filters.
5. Analyzed captured packets.

---

## Filters Used

### DNS Filter

```text
dns
```

Used to view domain name resolution requests and responses.

### TCP Filter

```text
tcp
```

Used to inspect TCP communication between systems.

### HTTP/TLS Filter

```text
http
```

or

```text
tls
```

Used to analyze web traffic.

---

## Observations

| Protocol | Observation |
|-----------|------------|
| DNS | Domain name queries and responses captured |
| TCP | TCP connections established between hosts |
| TLS/HTTP | Web communication traffic observed |

---

## Conclusion

Wireshark was successfully used to capture and analyze network packets. Different protocol filters were applied to inspect DNS, TCP, and web traffic. This task demonstrated basic network monitoring and packet analysis techniques.

---

## Skills Learned

* Packet Capture
* Traffic Analysis
* DNS Analysis
* TCP Communication Analysis
* Network Monitoring
* Cybersecurity Documentation
