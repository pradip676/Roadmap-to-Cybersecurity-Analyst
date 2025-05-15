# Basics of Cybersecurity

Cybersecurity is the practice of protecting systems, networks, and data from digital attacks, unauthorized access, or damage. As a cybersecurity analyst, understanding the core principles and common threats is essential before diving into defensive or offensive techniques.

---

## What is Cybersecurity?

Cybersecurity involves applying policies, technologies, and practices to defend computers, servers, mobile devices, networks, and data from malicious attacks.

---

## Core Security Objectives (CIA Triad)

### 1. **Confidentiality**

* Ensures data is only accessible by authorized individuals.
* Tools: Encryption, Access Control Lists (ACLs)

### 2. **Integrity**

* Ensures that data has not been tampered with.
* Tools: Checksums, Hashing (e.g., SHA-256)

### 3. **Availability**

* Ensures that systems and data are accessible when needed.
* Tools: Load balancing, backups, redundancy, DDoS protection

---

## Common Cyber Threats

### Malware

* Malicious software designed to damage, disrupt, or gain unauthorized access to systems.
* Types: Viruses, Worms, Trojans, Ransomware, Spyware

### Phishing

* Fraudulent attempts (usually via email) to trick users into revealing personal information or credentials.

### Man-in-the-Middle (MitM)

* An attacker secretly intercepts and possibly alters communication between two parties.

### Denial-of-Service (DoS/DDoS)

* Attackers flood a server or network with traffic to make it unavailable.

### SQL Injection

* Attackers inject malicious SQL commands into a database query to gain access or manipulate data.

### Zero-Day Exploits

* Vulnerabilities that are unknown to the vendor and actively exploited by attackers.

---

## Basic Security Principles

* **Least Privilege**: Give users only the access they need to perform their tasks.
* **Defense in Depth**: Use multiple layers of defense (firewall + antivirus + IDS/IPS).
* **Fail Securely**: Systems should fail in a way that protects data.
* **Keep Systems Updated**: Regularly patch and update software and firmware.
* **Security by Design**: Integrate security at the development stage, not after deployment.

---

## Security Domains

| Domain                 | Examples                                 |
| ---------------------- | ---------------------------------------- |
| Network Security       | Firewalls, IDS/IPS, VPN                  |
| Endpoint Security      | Antivirus, Device Control, Patching      |
| Application Security   | Secure coding, OWASP, fuzz testing       |
| Data Security          | Encryption, Backup, DLP                  |
| Identity & Access Mgmt | MFA, RBAC, SSO                           |
| Cloud Security         | IAM policies, workload security, logging |

---

## Basic Tools Every Analyst Should Know

| Tool               | Purpose                           |
| ------------------ | --------------------------------- |
| Wireshark          | Network protocol analyzer         |
| Nmap               | Port scanner and network mapper   |
| Burp Suite         | Web vulnerability testing         |
| Nessus             | Vulnerability scanner             |
| Sysinternals       | Advanced Windows system tools     |
| Linux Command Line | For log analysis, file inspection |

---

## Cybersecurity Best Practices

* Use strong, unique passwords
* Enable Multi-Factor Authentication (MFA)
* Avoid clicking unknown links or downloading untrusted files
* Keep backups and test recovery
* Log and monitor user/system activity

---

## Recommended Certifications

### <a href="https://www.comptia.org/certifications/security"><u>CompTIA Security+</u></a>

* Great entry-level cert covering threats, tools, policies, and incident response

### <a href="https://www.isc2.org/certifications/cc"><u>(ISC)² Certified in Cybersecurity (CC)</u></a>

* Entry-level cert from (ISC)² that touches on security operations, risks, and threats

---

## Free Learning Resources

* [TryHackMe - Introduction to Cybersecurity](https://tryhackme.com/path/outline/introtocyber)
* [Cybrary - Security Fundamentals](https://www.cybrary.it/skill-paths/cybersecurity-fundamentals)
* [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity)
* [OWASP Top 10](https://owasp.org/www-project-top-ten/)
* [Cybersecurity Basics - IBM SkillsBuild](https://skillsbuild.org/college-students/course-catalog/cybersecurity-fundamentals)

---

Next: Apply this foundational knowledge by building your own [Home Lab Setup](../Projects/home-lab-setup.md) and practicing real-world scenarios.
