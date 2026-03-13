# FUTURE_CS_02
FUTURE_CS_02 – Phishing Email Analysis Report (Task-02)  Future Interns – Cyber Security Internship (Feb–March 2026)

# FUTURE_CS_02 – Phishing Email Analysis Report (Task-02)

**Future Interns – Cyber Security Internship (Feb–March 2026)**

---

## Intern Details

**Name:** Sanita Salomon  
**Track:** Cyber Security  
**CIN ID:** FIT/FEB26/CS6325  
**Date Reported:** 13 March 2026  

---

## Task Objective

The objective of this task was to analyze suspicious email samples to identify phishing indicators and potential security threats.

The goal of this analysis was to:

- Identify suspicious elements within email messages
- Perform email header analysis using security tools
- Detect authentication failures (SPF, DKIM, DMARC)
- Identify social engineering techniques used by attackers
- Classify the risk level of phishing emails
- Provide security awareness and prevention recommendations

The analysis was conducted using a **read-only investigation methodology**, meaning no malicious links or attachments were executed.

---

## Email Samples Analyzed

Five suspicious email samples were analyzed during this task.

| Email Sample | Category | Description |
|--------------|----------|-------------|
| Email 1 | Adult Content Phishing | Curiosity-based phishing using adult content |
| Email 2 | Binance Account Verification | Fake account verification request |
| Email 3 | Promotional Spam | Fake promotional offer with suspicious links |
| Email 4 | MetaMask Alert | Cryptocurrency wallet phishing attempt |
| Email 5 | Fake Order Confirmation | Image-based phishing email |

---

## 🛠 Tools Used

The following cybersecurity tools were used during the investigation:

- **Google Admin Toolbox – Message Header Analyzer**
- **MXToolBox Header Analyzer**
- **Manual Email Content Analysis**

These tools helped analyze authentication mechanisms, sender information, and suspicious message characteristics.

---

## Risk Classification Overview

| Risk Level | Count |
|-------------|-------|
| High | 4 |
| Medium | 1 |
| Low | 0 |

Most analyzed emails were classified as **High Risk** because they contained phishing indicators such as domain mismatches, malicious links, and social engineering tactics.

---

# Key Findings Summary

## 1. Suspicious External Links

Several emails contained links directing users to **unknown or unrelated domains**.

### Examples
- safecloud.link  
- zzdzw.com  
- laredouteshop.com  
- ninafernandes.com.br  
- lnkd.in redirect links  

### Impact
- Redirects users to phishing websites  
- Possible credential theft  
- Malware distribution  

**Risk Level:** High

### Remediation

- Avoid clicking links from unknown senders  
- Hover over links to inspect the real destination  
- Use email filtering and URL reputation checks  

---

## 2. Sender Domain Mismatch

Many emails displayed sender domains different from the actual sending infrastructure.

### Examples
- Binance email using unrelated return path domain  
- MetaMask email sent from **mymts.net** domain  
- Promotional emails using multiple unrelated domains  

### Impact

Indicates **spoofing or impersonation attempts**

**Risk Level:** High

### Remediation

- Verify sender domain authenticity  
- Use email authentication technologies (**SPF, DKIM, DMARC**)  
- Implement anti-spoofing email policies  

---

## 3. Email Authentication Failures

Some emails failed authentication checks.

### Detected Issues
- **SPF:** Fail or None  
- **DKIM:** Missing signatures  
- **DMARC:** Fail  

### Impact

- Sender identity cannot be verified  
- Increased probability of phishing activity  

**Risk Level:** High

### Remediation

- Configure **SPF records** correctly  
- Enable **DKIM email signing**  
- Implement **DMARC policies** for domain protection  

---

## 4. Social Engineering Techniques

Attackers used psychological tactics to manipulate recipients.

### Common Techniques Observed
- Fear-based alerts (account disabled)  
- Curiosity-based content (adult content email)  
- Urgency tactics ("verify within 72 hours")  
- Attractive offers (400% bonus promotions)

### Impact

Encourages users to click malicious links quickly.

**Risk Level:** Medium to High

### Remediation

- Train users on **phishing awareness**  
- Avoid reacting quickly to urgent messages  
- Always verify suspicious requests independently  

---

## 5. Requests for Sensitive Information

The MetaMask phishing email requested a **12-word wallet recovery phrase**.

### Impact
- Full compromise of cryptocurrency wallet  
- Permanent loss of funds  

Legitimate services **never request private keys or recovery phrases via email.**

**Risk Level:** High

### Remediation

- Never share wallet recovery phrases  
- Access accounts only via official websites or apps  
- Enable **Two-Factor Authentication (2FA)**  

---

## 6. Hidden Links Inside Images

Some emails contained **clickable images instead of visible text links**.

### Impact

- Users cannot easily verify the destination URL  
- Increases phishing success rate  

**Risk Level:** Medium

### Remediation

- Disable automatic loading of remote images  
- Hover over image links before clicking  
- Use email security scanners  

---

# Security Awareness Recommendations

To reduce phishing risks, organizations should implement the following practices.

## Recommended Practices

- Verify sender email addresses carefully  
- Inspect links before clicking  
- Use **Multi-Factor Authentication (MFA)**  
- Enable spam filtering and email security gateways  
- Report suspicious emails to security teams  

## Actions to Avoid

- Do not click links from unknown emails  
- Do not download suspicious attachments  
- Never share personal or financial information through email  
- Avoid entering credentials on unknown websites  

---

# Conclusion

Phishing emails remain one of the **most common and effective cyberattack techniques** used by attackers.

This analysis demonstrated that phishing emails often use:

- Domain impersonation  
- Malicious links  
- Authentication bypass attempts  
- Social engineering tactics  

Understanding these indicators helps improve **email security awareness and threat detection capabilities**.
