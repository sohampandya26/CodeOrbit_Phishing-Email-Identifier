# Phishing Email Identifier — Checklist & Sample Analysis

**CodeOrbit Tech Cyber Security Internship — Task 3 of 6**

---

## 1. Overview

Phishing is a form of social engineering in which attackers impersonate
trusted individuals, companies, or services to trick users into performing
unsafe actions.

These actions may include:

- Clicking malicious or suspicious links
- Opening harmful attachments
- Revealing passwords, OTPs, or personal information
- Sharing banking or payment information
- Sending money or gift-card codes
- Installing malicious software

This document provides a practical checklist for identifying common phishing
indicators and applies the checklist to five fictional sample emails.

> **Educational Disclaimer:**  
> All email addresses, domains, messages, names, and links used in the
> examples below are fictional and are provided strictly for cybersecurity
> education and awareness. They do not represent real communications from
> any organization.

---

# 2. Phishing Red Flag Checklist

When reviewing a suspicious email, check the following indicators.

### 2.1 Urgent or Threatening Language

Phishing emails often create a sense of urgency or fear to prevent the
recipient from thinking carefully before taking action.

**Examples:**

- "Act immediately"
- "Your account will be suspended"
- "You have only 24 hours"
- "Failure to respond will result in permanent closure"

**Red Flag:** Artificial deadlines or threats designed to pressure the
recipient into acting quickly.

---

### 2.2 Generic or Unusual Greetings

Phishing emails often use generic greetings.

**Examples:**

- "Dear Customer"
- "Dear User"
- "Dear Account Holder"

> **Important:** A generic greeting alone does not prove that an email is
> phishing. It should be evaluated together with other indicators.

---

### 2.3 Suspicious or Mismatched Links

Attackers may use links that redirect users to fraudulent websites or domains
that resemble legitimate organizations.

Look for:

- Misspelled domains
- Extra words or unexpected subdomains
- Unusual domain extensions
- Shortened URLs that hide the destination
- Links whose visible text differs from the actual destination

**Example:**

```text
Expected:
https://example-bank.com

Suspicious:
https://example-bank-security.com
```

> **Safety Tip:** Do not click a suspicious link to investigate it. Hover
> over the link when possible to inspect its destination, or navigate to the
> organization's official website manually.

---

### 2.4 Unknown or Spoofed Sender Addresses

Check the **actual email address**, not only the display name.

```text
Display Name: Your Bank Security Team
Email: security@random-example-domain.com
```

The display name may look trustworthy while the actual domain is unrelated.

**Red Flag:** The sender's domain does not match the organization it claims
to represent.

---

### 2.5 Poor Spelling, Grammar, or Formatting

Some phishing emails contain:

- Frequent spelling mistakes
- Unusual grammar
- Strange capitalization
- Inconsistent fonts or formatting
- Unprofessional wording

> **Important:** Professional-looking emails can also be phishing. Good
> grammar does not make an email trustworthy.

---

### 2.6 Unexpected Attachments

Unexpected attachments should be treated cautiously, especially when they
are executable, compressed, or macro-enabled files.

Examples include:

```text
.exe
.zip
.rar
.iso
.xlsm
.docm
```

**Red Flag:** An unexpected attachment combined with urgency or a request to
open or enable content.

---

### 2.7 Requests for Sensitive Information

Be suspicious when an email unexpectedly asks for:

- Passwords
- OTPs
- Banking information
- Credit/debit card details
- Government identification
- Account recovery codes
- Personal documents

Legitimate organizations generally should not ask users to disclose
passwords or OTPs through email.

---

### 2.8 Offers That Are Too Good to Be True

Unexpected offers involving large amounts of money, prizes, refunds, or
inheritances are common social-engineering techniques.

Examples:

- "You have won $500,000"
- "Claim your unexpected refund"
- "You have inherited money"

**Red Flag:** An unsolicited reward requiring personal information,
payment, or immediate action.

---

### 2.9 Unusual Requests From Known Contacts

Attackers may impersonate managers, executives, friends, or coworkers.

Be especially cautious when the message:

- Requests money or gift cards
- Requests secrecy
- Bypasses normal company procedures
- Creates unusual urgency
- Requests sensitive information

**Red Flag:** The request is unusual for the sender or does not follow the
normal process.

---

# 3. Sample Email Analysis

The following five fictional emails demonstrate different phishing
techniques.

---

## Sample 1 — Fake Bank Security Alert

### Email Details

**From:**

```text
security@bank-of-lndia-alerts.com
```

**Subject:**

```text
URGENT: Your Account Will Be Suspended in 24 Hours
```

**Body:**

> Dear Customer,
>
> We detected unusual activity on your account. Click here to verify your
> identity immediately or your account will be permanently locked:
>
> http://bit.ly/verify-now-2026

### Red Flags Identified

- **Urgent and threatening language** — "URGENT" and a 24-hour deadline
- **Generic greeting** — "Dear Customer"
- **Suspicious sender domain** — the domain does not establish that it
  belongs to a legitimate bank
- **Shortened URL** — the destination is hidden behind a URL shortener
- **Credential/identity verification request** — encourages the recipient
  to verify through an email link
- **Fear-based pressure** — threatens permanent account locking

### Verdict

**Likely Phishing**

---

## Sample 2 — Fake Lottery Prize

### Email Details

**From:**

```text
promotions@intl-lucky-draw.net
```

**Subject:**

```text
Congratulations! You've Won $500,000
```

**Body:**

> You have been selected as our lucky winner!
>
> To claim your prize, reply with your full name, bank account number, and
> a copy of your ID within 48 hours.

### Red Flags Identified

- **Unsolicited prize** — no evidence that the recipient entered the draw
- **Too-good-to-be-true offer** — extremely large monetary reward
- **Request for sensitive information** — bank account details and identity
  documents
- **Artificial deadline** — 48-hour response requirement
- **Unknown sender/domain** — no established connection to the recipient

### Verdict

**Likely Phishing / Prize Scam**

---

## Sample 3 — Fake IT Helpdesk

### Email Details

**From:**

```text
it-support@yourcompany-helpdesk.co
```

**Subject:**

```text
Password Expiry Notice
```

**Body:**

> Your password expires today.
>
> Reset it within 2 hours using the link below to avoid losing access:
>
> [Reset Password]

### Red Flags Identified

- **Urgency** — password supposedly expires immediately
- **Short deadline** — only two hours to respond
- **Suspicious sender domain** — the domain does not match a verified
  company domain
- **Pressure to use an email link** — encourages password-related action
  directly from the message
- **Potential credential theft** — the reset link could lead to a fake
  login page

### Verdict

**Likely Phishing**

### Safe Alternative

Instead of clicking the link, open the organization's known official
website, application, or password-management portal manually.

---

## Sample 4 — Fake Delivery Notification

### Email Details

**From:**

```text
delivery-notify@parcel-tracking-help.com
```

**Subject:**

```text
We Missed Your Delivery — Reschedule Now
```

**Attachment:**

```text
Invoice_2598.zip
```

### Red Flags Identified

- **Unexpected attachment** — a compressed `.zip` file
- **Unfamiliar sender domain**
- **Urgent call to action** — "Reschedule Now"
- **Possible social engineering** — attempts to make the recipient believe
  they are waiting for a delivery
- **Lack of verifiable order information** — no trusted order or tracking
  reference is provided

### Verdict

**Likely Phishing / Delivery Scam**

### Safe Alternative

If a delivery is expected, verify it through the retailer or courier's
official website or application rather than opening the attachment.

---

## Sample 5 — Spoofed Executive Request

### Email Details

**From:**

```text
"CEO Name" <ceo@yourcompany.com>
```

**Reply-To:**

```text
different-address@example.com
```

**Subject:**

```text
Quick Favor Needed
```

**Body:**

> Are you at your desk?
>
> I need you to buy gift cards for a client and send me the codes.
> Keep this between us for now.

### Red Flags Identified

- **Unusual financial request** — asks the employee to purchase gift cards
- **Request for secrecy** — "Keep this between us"
- **Urgency** — "Quick Favor Needed"
- **Reply-To mismatch** — reply address differs from the displayed sender
- **Impersonation** — attempts to appear as a company executive
- **Out-of-process request** — bypasses normal purchasing procedures

### Verdict

**Likely Phishing / Business Email Compromise Attempt**

---

# 4. Comparative Analysis

| Sample | Primary Technique | Key Red Flags | Verdict |
|---|---|---|---|
| 1 | Fake Bank Alert | Urgency, suspicious domain, shortened URL, verification request | Phishing |
| 2 | Fake Lottery | Fake prize, sensitive-data request, deadline | Phishing |
| 3 | Fake IT Helpdesk | Fake domain, urgency, suspicious password-reset link | Phishing |
| 4 | Fake Delivery | ZIP attachment, unfamiliar sender, urgency | Phishing |
| 5 | Spoofed CEO | Impersonation, secrecy, gift cards, Reply-To mismatch | Phishing |

---

# 5. Findings

The five examples demonstrate several recurring phishing techniques.

### 5.1 Urgency and Emotional Pressure

All five examples attempt to encourage immediate action.

Examples include:

- Account suspension within 24 hours
- A 48-hour prize claim deadline
- Password expiration within two hours
- "Reschedule Now"
- An urgent executive request

Creating urgency reduces the likelihood that the recipient will stop and
verify the request.

---

### 5.2 Suspicious Sender Information

Several examples use sender domains that do not establish a legitimate
relationship with the organization being impersonated.

This demonstrates why users should inspect the complete sender address rather
than trusting the display name.

---

### 5.3 Requests for Sensitive Information or Payment

Two examples directly request sensitive information or financial action:

- Sample 2 requests banking information and identification.
- Sample 5 requests the purchase of gift cards and transfer of their codes.

These are strong warning signs when the request is unexpected.

---

### 5.4 Links and Attachments

The examples demonstrate two common delivery methods:

- Suspicious links
- Unexpected attachments

A phishing email may use either technique to direct the recipient toward
credential theft, malware, or another fraudulent action.

---

### 5.5 Impersonation and Social Engineering

Attackers often impersonate organizations, IT departments, delivery
services, banks, or executives.

The technical appearance of an email is therefore not enough to establish
trust. The recipient should also consider whether the request itself makes
sense.

---

# 6. How to Respond to a Suspicious Email

If an email appears suspicious:

1. **Do not click suspicious links.**
2. **Do not open unexpected attachments.**
3. **Do not reply with passwords, OTPs, or financial information.**
4. **Check the complete sender address.**
5. **Inspect the destination of links without opening them.**
6. **Verify unusual requests through a separate trusted channel.**
7. **Navigate to the organization's official website manually when needed.**
8. **Report the message using the organization's phishing-reporting process.**
9. **If you already clicked or submitted information, change affected
   credentials and contact the relevant organization immediately.**

---

# 7. Quick 30-Second Phishing Check

```text
┌─────────────────────────────────────────────┐
│          30-SECOND PHISHING CHECK           │
├─────────────────────────────────────────────┤
│ 1. Do I recognize the sender?               │
│ 2. Does the actual domain look legitimate?  │
│ 3. Is the email creating unusual urgency?   │
│ 4. Is there a suspicious link?              │
│ 5. Is there an unexpected attachment?       │
│ 6. Is sensitive information requested?      │
│ 7. Is the request unusual or secretive?     │
│ 8. Can I verify it independently?           │
└─────────────────────────────────────────────┘
```

If multiple warning signs are present, **do not interact with the email
until its legitimacy has been independently verified.**

---

# 8. Key Takeaways

The most important defensive habits are:

- Check the **actual sender address**, not just the display name.
- Be cautious with **urgent or threatening messages**.
- Inspect suspicious links before interacting with them.
- Never provide **passwords or OTPs** through an email request.
- Treat unexpected attachments with caution.
- Be suspicious of unexpected prizes, refunds, or financial opportunities.
- Verify unusual requests from executives or known contacts through another
  communication channel.
- When in doubt, access the organization's official website or application
  directly rather than using links provided in the email.

---

# 9. Conclusion

Phishing attacks rely heavily on social engineering techniques such as
urgency, fear, curiosity, impersonation, and financial incentives.

No single warning sign can prove that an email is malicious. However, when
multiple indicators appear together, the risk becomes significantly higher.

By checking the sender, links, attachments, requested information, and
overall context before taking action, users can reduce their risk of
falling victim to phishing attacks.

---

## Disclaimer

All email addresses, domains, links, names, and messages in this document
are fictional examples created for cybersecurity education and awareness.

This project does not contain real phishing campaigns or credentials and
should not be used to impersonate real organizations or individuals.

---

**CodeOrbit Tech Cyber Security Internship — Batch IND1 — Task 3 of 6**
