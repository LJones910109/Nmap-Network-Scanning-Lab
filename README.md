# 🗺️ Nmap Network Scanning Lab

## Objective
Perform network reconnaissance against a vulnerable target (Metasploitable2) 
in a controlled home lab environment to identify open ports, services, and 
potential attack vectors.

---

## 🛠️ Tools Used
- Kali Linux (attacker machine)
- Metasploitable2 (target machine)
- VMware Fusion
- Nmap

---

## 🔬 Lab Environment
| Machine | OS | Role |
|---|---|---|
| Attacker | Kali Linux | Running Nmap scans |
| Target | Metasploitable2 | Intentionally vulnerable VM |

Both machines run on an isolated VMware network.

---

## 📋 Scans Performed

### 1. Host Discovery
```bash
nmap -sn 192.168.x.0/24
nmap 172.16.148.133
nmap -sV 172.16.148.133
nmap -0 172.16.148.133
nmap -A 172.16.148.133
