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

<img width="648" height="520" alt="Scan-Basic-port" src="https://github.com/user-attachments/assets/eed03898-4ce8-4617-ad80-e91101ea86aa" />

<img width="723" height="617" alt="scan1-host-discovery" src="https://github.com/user-attachments/assets/a1dd08a5-a074-4f01-ad76-99e266600671" />

<img width="709" height="584" alt="Scan2-basic-port-scan" src="https://github.com/user-attachments/assets/8a181723-08bd-4bca-9e97-a5c2e055cff7" />

<img width="711" height="581" alt="Scan2-service-version" src="https://github.com/user-attachments/assets/6fc7a70d-ebf4-4df3-aec2-c199ced43296" />

<img width="709" height="587" alt="Scan5-aggressive" src="https://github.com/user-attachments/assets/1bd52337-16fa-44f3-898c-886f73c2ac52" /> <img width="760" height="586" alt="Scan5(2)-aggressive" src="https://github.com/user-attachments/assets/492bfe20-e48b-4b2f-896b-20a2651370f6" /> <img width="787" height="582" alt="Scan5(3)-aggressive" src="https://github.com/user-attachments/assets/093606b2-e533-4ae6-b7eb-1d5487715c19" /> <img width="776" height="540" alt="Scan5(4)-aggressive" src="https://github.com/user-attachments/assets/1de3139f-1f87-45e2-ba90-eb89ddf8c096" />
