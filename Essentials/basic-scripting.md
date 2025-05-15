# Basic Scripting

Scripting is the process of writing small programs (scripts) to automate tasks that would otherwise be done manually. It is one of the most important skills for a cybersecurity analyst, especially in areas like automation, log parsing, vulnerability scanning, and file manipulation.

---

## Why Learn Scripting?

* Automate repetitive tasks
* Quickly analyze data (e.g., logs, reports)
* Write your own tools for scanning and monitoring
* Understand how scripts and exploits function

---

## Popular Scripting Languages in Cybersecurity

### 1. **Python**

* Easy to learn and powerful
* Great for automation, networking, web scraping, and writing security tools
* Used in tools like Scapy, Nmap automation, and vulnerability scanners

### 2. **Bash (Linux Shell Scripting)**

* Useful for automating commands and managing Linux environments
* Common in penetration testing, server automation, and scripting security tools

### 3. **PowerShell (Windows)**

* Ideal for Windows system administration
* Often used for managing Active Directory, event logs, and automated security tasks

---

## Key Concepts in Scripting

### Regular Expressions (Regex)

Regex is a powerful tool for pattern matching in strings. It's commonly used in cybersecurity for filtering logs, validating inputs, and extracting data.

**Example:** Match all `.log` files:

```bash
ls | grep "\.log$"
```

**Example in Python:**

```python
import re
log_entry = "Failed login from 192.168.0.1"
if re.search(r"\d+\.\d+\.\d+\.\d+", log_entry):
    print("IP address found")
```

### `awk` and `sed` (Linux Text Processing Tools)

These are essential tools for working with structured or semi-structured text files in Linux.

**Example (awk):** Print usernames from `/etc/passwd`

```bash
awk -F":" '{ print $1 }' /etc/passwd
```

**Example (sed):** Replace all instances of "admin" with "user"

```bash
sed 's/admin/user/g' users.txt
```

---

## Common Use Cases

* Log file parsing
* Port scanning automation
* Network monitoring and alerting
* File encryption/decryption scripts
* Pattern matching using regex
* Filtering logs using `grep`, `awk`, `sed`

---

## Example Scripts

### Python: Hello World

```python
print("Hello, Cybersecurity World!")
```

### Bash: List files

```bash
#!/bin/bash
echo "Listing files in current directory:"
ls -lah
```

### PowerShell: Get running processes

```powershell
Get-Process | Sort-Object CPU -Descending | Select-Object -First 5
```

---

## Tools to Practice Scripting

| Tool           | Description                                 |
| -------------- | ------------------------------------------- |
| VS Code        | Popular editor for scripting and automation |
| TryHackMe Labs | Scripting practice in realistic cyber labs  |
| Hack The Box   | Challenges often require simple scripts     |
| Python REPL    | Interactive Python interpreter              |


---

## Recommended Learning Resources

* [Automate the Boring Stuff with Python](https://automatetheboringstuff.com/)
* [TryHackMe - Scripting Rooms](https://tryhackme.com/module/scripting-for-pentesters)
* [RegexOne (Interactive Regex Practice)](https://regexone.com/)
* [Awk Tutorial (Grymoire)](https://www.grymoire.com/Unix/Awk.html)
* [PowerShell for Beginners (Microsoft Learn)](https://learn.microsoft.com/en-us/training/modules/introduction-to-powershell/)
* [Python Scripting Basics](https://youtube.com/playlist?list=PLx8HYVzPNOImIT7msbXNkk5KVHje8cKB2&si=cwMmMpmqkG2k2JVQ)

---

Now that you’ve got a grip on scripting, move on to [Basics of Cybersecurity](basics-of-cybersecurity.md) to learn the principles behind securing networks and systems.
