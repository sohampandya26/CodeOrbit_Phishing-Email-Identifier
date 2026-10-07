# CodeOrbit Tech Cyber Security Internship
## Task 3 — Phishing Email Identifier

**Batch:** IND1  
**Task:** 3 of 6  
**Project:** Phishing Email Identifier  
**Author:** Soham Pandya

---

## 1. Executive Summary

Phishing is a social-engineering technique in which attackers impersonate
trusted individuals, organizations, or services to manipulate users into
performing unsafe actions.

This project was developed to demonstrate how common phishing indicators
can be identified through a structured checklist and practical email
analysis.

Five fictional email scenarios were examined:

1. Fake Bank Security Alert
2. Fake Lottery Prize
3. Fake IT Helpdesk
4. Fake Delivery Notification
5. Spoofed Executive Request

The analysis focused on sender information, urgency, links, attachments,
requests for sensitive information, impersonation, and unusual actions.

The project concludes that effective phishing detection requires users to
evaluate the **sender, message content, links, attachments, requested
actions, and overall context together**, rather than relying on a single
warning sign.

---

# 2. Introduction

Phishing attacks are among the most common forms of social engineering.
Instead of directly attacking a technical system, attackers often target
human decision-making by creating urgency, fear, curiosity, trust, or
financial incentives.

A phishing email may appear to come from a bank, company, delivery service,
IT department, manager, executive, or another trusted source.

Common objectives include:

- Stealing login credentials
- Obtaining OTPs or account recovery codes
- Collecting personal or financial information
- Delivering malware
- Redirecting users to fraudulent websites
- Convincing victims to make payments
- Performing business email compromise or impersonation

The purpose of this task was to understand these techniques and create a
simple, practical method for recognizing suspicious emails.

---

# 3. Project Objectives

The main objectives of the project were:

- Identify common phishing indicators.
- Understand how social engineering is used in email attacks.
- Analyze suspicious sender addresses and domains.
- Identify misleading or suspicious links.
- Recognize dangerous or unexpected attachments.
- Detect requests for sensitive information.
- Analyze unusual financial or administrative requests.
- Demonstrate safe email-handling practices.
- Create clear cybersecurity awareness documentation.

---

# 4. Methodology

The project followed a checklist-based analysis approach.

Each sample email was evaluated using the following criteria:

| Category | Analysis |
|---|---|
| Sender | Is the sender known and does the domain appear legitimate? |
| Subject | Does the subject create unnecessary urgency or fear? |
| Greeting | Is the recipient addressed appropriately or generically? |
| Links | Are URLs suspicious, shortened, or misleading? |
| Attachments | Is an unexpected or potentially dangerous file attached? |
| Information Requests | Is sensitive information being requested? |
| Financial Requests | Is money, gift cards, or payment information requested? |
| Urgency | Is the recipient pressured to act immediately? |
| Impersonation | Is someone or an organization being impersonated? |
| Context | Does the request make sense for the situation? |

The indicators were then compared across all five examples.

---

# 5. Sample Email Analysis

## Sample 1 — Fake Bank Security Alert

**Primary technique:** Account-security impersonation

### Observed Indicators

- Urgent account-suspension threat
- Generic greeting
- Suspicious sender domain
- Shortened URL
- Identity-verification request
- Pressure to act within 24 hours

### Assessment

The email attempts to create fear by claiming that the account will be
permanently locked. The shortened URL also prevents the recipient from
immediately seeing the final destination.

**Verdict:** Likely Phishing

---

## Sample 2 — Fake Lottery Prize

**Primary technique:** Prize/reward scam

### Observed Indicators

- Unsolicited prize claim
- Extremely large financial reward
- Request for bank account information
- Request for identity documents
- Artificial 48-hour deadline

### Assessment

The message uses an unrealistic financial reward to encourage the recipient
to provide sensitive information.

**Verdict:** Likely Phishing / Prize Scam

---

## Sample 3 — Fake IT Helpdesk

**Primary technique:** Credential harvesting

### Observed Indicators

- Password-expiry warning
- Two-hour deadline
- Suspicious sender domain
- Password-reset link
- Potential fake login page

### Assessment

The message attempts to make the recipient click a password-reset link
under time pressure. A legitimate user should instead access the known
company portal manually.

**Verdict:** Likely Phishing

---

## Sample 4 — Fake Delivery Notification

**Primary technique:** Malicious attachment / delivery scam

### Observed Indicators

- Unexpected ZIP attachment
- Unfamiliar sender domain
- Urgent rescheduling request
- Lack of verifiable order information

### Assessment

The attachment is a significant warning sign, particularly because the
recipient is encouraged to interact with it as part of an urgent delivery
request.

**Verdict:** Likely Phishing / Delivery Scam

---

## Sample 5 — Spoofed Executive Request

**Primary technique:** Executive impersonation / Business Email Compromise

### Observed Indicators

- Executive impersonation
- Urgent request
- Gift-card purchase request
- Request for secrecy
- Reply-To address mismatch
- Bypassing normal organizational procedures

### Assessment

The request combines impersonation, secrecy, urgency, and financial
pressure. These characteristics are commonly associated with business
email compromise and executive impersonation scams.

**Verdict:** Likely Phishing / BEC Attempt

---

# 6. Comparative Results

| Sample | Main Attack Technique | Major Indicators | Result |
|---|---|---|---|
| 1 | Bank impersonation | Urgency, suspicious domain, shortened link | Phishing |
| 2 | Prize scam | Fake reward, sensitive-data request, deadline | Phishing |
| 3 | Credential harvesting | Fake domain, password-reset link, urgency | Phishing |
| 4 | Delivery scam | ZIP attachment, unfamiliar sender, urgency | Phishing |
| 5 | Executive impersonation | Secrecy, gift cards, Reply-To mismatch | Phishing |

---

# 7. Key Findings

## 7.1 Urgency Was a Recurring Technique

All five fictional samples attempted to encourage immediate action.

Examples included:

- "Suspended in 24 hours"
- "Within 48 hours"
- "Your password expires today"
- "Reschedule Now"
- "Quick Favor Needed"

Urgency is commonly used to reduce the time available for verification.

---

## 7.2 Sender Verification Is Important

Several examples used domains that did not establish a legitimate
relationship with the organization being impersonated.

The analysis demonstrates why users should check the complete email address
rather than trusting only the display name.

---

## 7.3 Sensitive Information and Financial Requests Are High-Risk Indicators

The examples included requests for:

- Bank account information
- Identity documents
- Gift cards
- Authentication-related information

Unexpected requests of this type should be independently verified before
any action is taken.

---

## 7.4 Links and Attachments Can Be Delivery Mechanisms

The samples demonstrated two common methods:

- Suspicious links that may lead to fraudulent websites
- Unexpected attachments that may contain malicious content

Users should avoid interacting with these elements until their legitimacy
has been verified.

---

## 7.5 Social Engineering Is Central to Phishing

The examples relied on different psychological techniques:

| Technique | Example |
|---|---|
| Fear | Account suspension |
| Urgency | Short deadlines |
| Greed | Large lottery prize |
| Trust | IT department impersonation |
| Authority | CEO impersonation |
| Curiosity / expectation | Delivery notification |

This shows that phishing is not purely a technical problem. Human behavior
and decision-making are major parts of the attack surface.

---

# 8. Recommended Defensive Practices

Users can reduce phishing risk by following these practices:

1. Check the complete sender email address.
2. Do not trust the display name alone.
3. Avoid clicking unexpected links.
4. Inspect suspicious URLs before interacting with them.
5. Do not open unexpected attachments.
6. Never share passwords or OTPs through email.
7. Be cautious about unexpected financial requests.
8. Verify unusual requests using a separate trusted communication channel.
9. Navigate to official websites manually instead of using suspicious links.
10. Report suspected phishing messages through the appropriate organization
    or email provider.

---

# 9. Project Deliverables

The completed project contains the following deliverables:

```text
CodeOrbit-Phishing-Email-Identifier/
│
├── README.md
├── phishing_email_identifier.md
│
├── report/
│   └── task-3-report.md
│
└── screenshots/
    └── project-preview.png
```

### Deliverable Summary

- **README.md** — Project overview and repository documentation
- **phishing_email_identifier.md** — Complete phishing checklist and sample
  email analysis
- **task-3-report.md** — Internship task report
- **project-preview.png** — Project visual preview

---

# 10. Conclusion

This project demonstrated how phishing emails can be analyzed using a
structured set of indicators.

The five fictional examples showed that phishing messages frequently combine
multiple techniques such as urgency, impersonation, suspicious domains,
malicious or unexpected attachments, requests for sensitive information,
financial manipulation, and secrecy.

No single indicator is sufficient to determine that every suspicious email
is malicious. However, identifying multiple warning signs and independently
verifying unusual requests can significantly reduce the likelihood of
falling victim to phishing.

The most important principle is:

> **Stop, verify, and think before clicking, replying, opening an attachment,
> or sharing sensitive information.**

---

# 11. Learning Outcomes

Through this task, the following concepts were explored:

- Phishing and social engineering
- Email-based attack techniques
- Sender and domain analysis
- URL and link awareness
- Attachment safety
- Credential and information theft
- Business Email Compromise
- Executive impersonation
- Security awareness practices
- Structured cybersecurity documentation

---

# 12. Future Improvements

A future version of this project could include:

- An automated phishing-email detection tool
- URL reputation checking
- Sender-domain validation
- Email-header analysis
- Machine-learning-based classification
- A phishing-risk scoring system
- Interactive cybersecurity awareness exercises

These features could transform the documentation project into a practical
security-awareness or phishing-analysis application.

---

## 13. Disclaimer

All email addresses, domains, links, names, and scenarios used in this
report are fictional examples created strictly for cybersecurity education
and awareness.

This project does not contain real phishing campaigns, credentials, or
malicious payloads and must not be used to impersonate real organizations
or individuals or to conduct phishing or fraudulent activity.

---

**CodeOrbit Tech Cyber Security Internship — Batch IND1 — Task 3 of 6**

**Project:** Phishing Email Identifier  
**Author:** Soham Pandya
