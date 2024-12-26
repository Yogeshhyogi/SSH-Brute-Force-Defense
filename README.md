# SSH-Brute-Force-Defense
This project aims to analyze SSH failed login attempts on a CentOS VM to detect and mitigate brute-force attacks.
# Project Purpose:

This project aims to analyze SSH failed login attempts on a CentOS Virtual Machine (VM) to detect and mitigate brute-force attacks.

**Importance of SSH Security:**

SSH (Secure Shell) is a critical protocol for remote access and secure communication with servers. Compromised SSH access can have severe consequences, 
**including:**

**Data Breaches:** Attackers can gain unauthorized access to sensitive data stored on the server.
**System Control:** Attackers can gain control of the server, allowing them to install malware, launch further attacks, or disrupt services.
**Denial of Service (DoS):** Constant brute-force attempts can overwhelm the server and make it inaccessible for legitimate users.
Mitigating Brute-Force Attacks

By analyzing SSH logs and identifying suspicious activity, this project aims to help system administrators proactively detect and mitigate brute-force attacks, enhancing the security of their CentOS VMs

## Steps to run
### 1. Create python virtual env and activate
```
python3 -m venv .venv 
source .venv/bin/activate
````

### 2. Install requirements library
```
pip3 install -r requirements.txt
```

### 3. Run 
```
python analyze_ssh_logs.py 
```