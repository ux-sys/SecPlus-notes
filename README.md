
---

# 🔵 2. Sec+ Notes (STRUCTURED + UPGRADED)

```markdown
# Security+ Notes (Systems Perspective)

Structured notes focused on understanding cybersecurity from a systems and operational perspective.

---

## 🧩 Core Domains

1. Security Fundamentals  
2. Threats, Vulnerabilities, and Mitigations  
3. Security Architecture (Design & Topology)  
4. Security Operations (SOC, MDM, Monitoring)  
5. Governance, Risk, and Compliance  

---

## 🏗️ Foundational Concepts

### Standards & Protocols

- **Standard** → formal guideline (e.g., RFC, IEEE, ISO)
- **Protocol** → rules for communication (e.g., SSH, TLS)
- **Software** → implementation of a protocol
- **Software Stack** → multiple layers working together

### Standards Bodies

- RFC (IETF)  
- IEEE (e.g., 802.1Q)  
- ISO/IEC  
- ITU-T  
- Microsoft (MS-XXXX specs)  

---

## 🔐 Core Security Concepts

- ASCII (encoding)
- TLS / SSL
- Handshake process:
  - Client Hello
  - Server Hello
  - Key Exchange
  - Finished Messages

---

## 🧠 Organizational Security Model

Organizations operate in three layers:

### Objective (WHY)
- Defined in mission statement  
- Determines priority of **CIA triad**  
  - Confidentiality  
  - Integrity  
  - Availability  

---

### Goals (WHAT LEVEL)
- Measurable targets  
- Defines how much protection is required  
- Maps CIA importance to assets  

---

### Tactics (HOW)
- Day-to-day implementation  
- Defines how controls are enforced  
- Includes:
  - Access control (AAA)
  - Monitoring
  - Incident response  

---

## 🔐 AAA Framework (Security Interrogation Model)

A structured way to analyze any system.

---

### 1️⃣ Authentication (Identity)

- Who verifies identity?
- What proof is used? (password, token, cert)
- How is it transmitted?
- Where is it validated?
- What artifact is issued? (session, JWT, ticket)
- Where is it stored?
- How long is it valid?
- What invalidates it?
- Can it be replayed?
- Can it be forged?

---

### 2️⃣ Authorization (Access Control)

- Where are permissions defined?
- What determines access? (role, group, claims)
- Where is access evaluated?
- Centralized or distributed?
- Checked every request?
- Can permissions be inherited?
- Can they be delegated?
- Are there default permissions?
- What happens on failure?
- Can identity context change?

---

### 3️⃣ Accounting (Logging & Visibility)

- What is logged?
- Where are logs stored?
- Who can access logs?
- Are logs immutable?
- Are failures logged?
- Are privilege changes tracked?
- Are tokens logged?
- Can logs be bypassed?

---

## 🧠 Why AAA Matters

This framework helps analyze:
- OAuth
- Kerberos
- IAM systems (AWS / Azure)
- Web applications
- Enterprise environments

Instead of:
> “Understand everything”

You:
> systematically interrogate the system

---

## 🧭 Operator Mindset

- Use AAA as a scanning tool  
- Identify weak points quickly  
- Focus on inconsistencies  
- Expand only where needed  

---

## ⚙️ Practical Alias Example

```bash
alias nmappy='nmap -Pn -n --disable-arp-ping'
