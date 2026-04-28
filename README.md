# Day 11  
## MITRE ATT&CK Framework (Advanced)  

---

##  Objective  

- Understand the MITRE ATT&CK framework  
- Learn attacker tactics and techniques (TTPs)  
- Map real-world attacks to MITRE stages  
- Apply structured threat analysis in SOC  

---

##  What is MITRE ATT&CK?  

MITRE ATT&CK is a knowledge base of real-world cyber adversary behavior used to understand, detect, and respond to attacks effectively.  

It helps SOC analysts map security events to structured attack techniques.

---

##  Core Concept – TTPs  

- **Tactics** → Why the attack happens  
- **Techniques** → How the attack is performed  
- **Procedures** → Specific implementation  

---

##  Key Tactics  

- **Initial Access** → Entry into system (e.g., phishing)  
- **Execution** → Running malicious code  
- **Persistence** → Maintaining access  
- **Privilege Escalation** → Gaining admin access  
- **Credential Access** → Stealing passwords  
- **Lateral Movement** → Moving across network  

---

##  Common Techniques  

- Brute Force Login  
- Phishing Emails  
- Malicious Script Execution  
- Credential Dumping  

---

##  Attack Mapping Example  

| Activity | Tactic | Technique |
|----------|--------|----------|
| Failed logins | Credential Access | Brute Force |
| Phishing email | Initial Access | Phishing |
| Malware run | Execution | Malicious Code |

---

##  Importance in SOC  

- Understand attacker behavior  
- Improve SIEM detection rules  
- Map alerts to attack stages  
- Enhance incident response  

---

##  Assignment  

### 1. MITRE ATT&CK Explanation  
MITRE ATT&CK is a framework that helps analysts understand how attackers behave and map real-world attacks to structured techniques.

---

### 2. Tactics with Examples  

- **Initial Access** → Phishing email  
- **Execution** → Malware execution  
- **Credential Access** → Brute force attack  

---

### 3. Brute Force Mapping  

| Stage | Tactic | Technique |
|------|--------|----------|
| Step 1 | Credential Access | Brute Force |
| Step 2 | Persistence | Valid Accounts |
| Step 3 | Lateral Movement | Credential Use |

---

##  Key Takeaway  

Understanding attacker behavior is essential for effective detection and response in a SOC environment.

---

##  Conclusion  

This session helped in understanding how to map cyber attacks using the MITRE ATT&CK framework and apply structured analysis for better threat detection.

---

##  Author  

**Adithya Raj K R**  

---

## 🏷️ Tags  
`Cybersecurity` `SOC` `MITRE ATT&CK` `ThreatAnalysis` `InfoSec`
