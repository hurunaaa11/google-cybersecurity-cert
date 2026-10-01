# Ransomware Incident Analysis

## Overview

This project documents a simulated ransomware security incident and demonstrates the use of an incident handler's journal to organize and analyze information during the incident response process.

The scenario involves a healthcare organization whose operations were disrupted after employees interacted with targeted phishing emails containing a malicious attachment. The attachment enabled attackers to gain access to the organization's network and deploy ransomware, resulting in the encryption of critical files.

This activity was completed as part of the **Google Cybersecurity Professional Certificate – Sound the Alarm: Detection and Response** course.

> **Note:** This is a simulated educational scenario and does not represent a real-world incident.

---

## Scenario

A small healthcare clinic experienced a major security incident at approximately **9:00 a.m. on a Tuesday**.

Employees reported that they could no longer access important files and software, including medical records. A ransom note appeared on affected computers stating that the organization's files had been encrypted.

The attackers demanded payment in exchange for a decryption key.

The initial access vector was identified as targeted phishing emails containing malicious attachments. After an employee downloaded the attachment, malware was installed and the attackers gained access to the organization's network. The attackers subsequently deployed ransomware, which encrypted critical files and disrupted business operations.

---

# Incident Analysis

## 5 W's

### Who?

The incident was caused by an organized group of attackers who targeted organizations in the healthcare and transportation sectors.

The attackers used phishing emails to gain initial access to the organization's environment.

### What?

The organization experienced a ransomware attack that encrypted critical files and prevented employees from accessing medical records and other software required for normal operations.

A ransom note was displayed on affected computers, demanding payment in exchange for a decryption key.

### When?

The incident occurred on a **Tuesday morning at approximately 9:00 a.m.**

Employees began reporting that they were unable to access important files and systems around this time.

### Where?

The incident occurred within the computer network of a small U.S. healthcare clinic providing primary-care services.

The attack affected employee computers and access to critical organizational files and systems.

### Why?

The attackers gained initial access through targeted phishing emails containing a malicious attachment.

After the attachment was downloaded, malware was installed and used to gain access to the organization's network, allowing the attackers to deploy ransomware.

---

# Attack Chain

The incident can be summarized as:

```text
Targeted Phishing Email
          │
          ▼
Malicious Attachment
          │
          ▼
Employee Downloads Attachment
          │
          ▼
Malware Installed
          │
          ▼
Network Access
          │
          ▼
Ransomware Deployment
          │
          ▼
Critical Files Encrypted
          │
          ▼
Business Disruption
          │
          ▼
Ransom Demand
```

---

# Incident Response Perspective

The incident demonstrates the importance of identifying and documenting each stage of a security incident.

From an incident response perspective, relevant activities would include:

1. Identifying the affected systems.
2. Containing compromised systems to prevent further spread.
3. Preserving relevant evidence and logs.
4. Investigating the phishing email and malicious attachment.
5. Determining the scope of the ransomware infection.
6. Eradicating the malicious software.
7. Recovering affected systems and data.
8. Documenting lessons learned.

---

# Incident Handler's Journal

A journal entry was used to record the incident details in a structured format.

### Entry

**Entry Number:** 1

**Incident Type:** Ransomware

**Initial Access:** Phishing email with malicious attachment

**Affected Organization:** Small healthcare clinic

**Approximate Incident Time:** Tuesday, 9:00 a.m.

**Primary Impact:** Critical files and medical records became inaccessible.

**Attacker Demand:** Payment in exchange for a decryption key.

---

## Tools

No specific cybersecurity tools were used to investigate the simulated scenario.

The activity primarily focused on:

* Incident documentation
* Incident analysis
* The 5 W's
* Incident response concepts
* Incident handler's journal

---

# Key Indicators

The scenario contains several indicators that could assist an incident responder:

| Indicator            | Observation                                   |
| -------------------- | --------------------------------------------- |
| Initial access       | Targeted phishing email                       |
| Malicious content    | Email attachment                              |
| Malware              | Installed after attachment was downloaded     |
| Impact               | Critical files encrypted                      |
| User impact          | Employees unable to access files and software |
| Ransomware indicator | Ransom note displayed                         |
| Business impact      | Operations disrupted                          |
| Data affected        | Medical records and other critical files      |

---

# Lessons Learned

This activity reinforced several important incident response concepts:

### 1. Documentation

Incident handlers need to maintain accurate records throughout an investigation. A structured journal helps organize observations, actions, and important questions.

### 2. Phishing as an Initial Access Vector

Phishing can provide attackers with an entry point into an organization's environment when users interact with malicious content.

### 3. Incident Impact

A successful ransomware attack can affect both technical systems and business operations. In a healthcare environment, loss of access to medical records can significantly disrupt normal operations.

### 4. Incident Response Lifecycle

The scenario demonstrates why organizations need a structured process for identifying, containing, eradicating, and recovering from security incidents.

### 5. Security Awareness

Technical controls are important, but employees also play an important role in preventing phishing-based attacks. Security awareness training and appropriate email security controls can help reduce risk.

---

# Reflection

The main takeaway from this activity was that incident response is not only about identifying malware or technical indicators. Effective response also requires structured documentation, communication, evidence collection, and understanding the business impact of an incident.

The incident handler's journal provides a practical way to record observations throughout an investigation and can support later analysis and lessons learned.

---

## Skills Demonstrated

* Incident response documentation
* Security incident analysis
* Ransomware analysis
* Phishing analysis
* Incident handler's journal
* 5 W's analysis
* Incident response lifecycle
* Security awareness
* Cybersecurity documentation

---

## Course

**Google Cybersecurity Professional Certificate**

**Course:** Sound the Alarm: Detection and Response

**Activity:** Document an Incident with an Incident Handler's Journal

This project is based on a simulated educational scenario completed as part of the course.
