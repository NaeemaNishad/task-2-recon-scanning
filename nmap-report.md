# 🔎 Nmap Scan Report

## 🎯 Target
Metasploitable2  
IP Address: 192.168.56.102  

---

## ⚙️ Commands Used

- nmap 192.168.56.102  
- nmap -sS 192.168.56.102  
- nmap -sU 192.168.56.102  
- nmap -sV 192.168.56.102  
- nmap -O 192.168.56.102  

---

## 📊 Scan Results

### Open Ports & Services

| Port | Service | Description |
|------|--------|------------|
| 21   | FTP    | vsFTPd 2.3.4 |
| 22   | SSH    | OpenSSH |
| 80   | HTTP   | Apache Web Server |
| 139  | NetBIOS | Samba |
| 445  | SMB    | Samba |

---

## 🧠 Analysis

- Multiple services are running on the target system  
- FTP service is outdated and potentially vulnerable  
- SMB and HTTP services may also contain vulnerabilities  

---

## 📌 Conclusion

Nmap scanning successfully identified open ports and services, providing valuable information for further vulnerability assessment.
