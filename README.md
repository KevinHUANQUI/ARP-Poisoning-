# ARP Poisoning Attack Simulation (MITM)

## 📌 Description
This project demonstrates an ARP poisoning (Man-in-the-Middle) attack using Python (Scapy) in a controlled lab environment. The objective is to understand how attackers intercept network traffic and how such attacks can be detected and mitigated.

---

## 🛠️ Tools Used
- Kali Linux
- Python (Scapy)
- Wireshark

---

## 🌐 Network Setup
- Attacker (Kali): 192.168.X.X
- Victim: 192.168.X.X
- Router/Gateway: 192.168.X.X

---

## ⚙️ Attack Execution

### 1. Enable IP Forwarding
```bash
echo 1 > /proc/sys/net/ipv4/ip_forward
