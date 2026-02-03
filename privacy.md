# Privacy Policy

**Last Updated:** 02/03/2026 [M/D/Y]
**Version:** 1.0.0

## 1. Introduction

This Privacy Policy describes how SuperBackupBot3000 ("the Service," "the Bot," "we," "us," or "our") collects, uses, stores, and protects your personal information when you use our Discord bot service.

We are committed to protecting your privacy and ensuring you understand how your data is handled. Please read this policy carefully.

**Controller Identity:**  
Recovery Bot 3000  
Email: recover3000botaddress@keemail.me

## 2. Information We Collect

### 2.1 Information You Provide Through Authorization

When you authorize our bot through Discord's OAuth2 system, we collect:

| Data Type | Purpose | Legal Basis |
|-----------|---------|-------------|
| Discord User ID | Identify your account | Consent |
| Discord Username | Display purposes | Consent |
| Discord Discriminator | Display purposes | Consent |
| Global Display Name | Display purposes | Consent |
| OAuth2 Access Token | Add you to servers | Consent |
| OAuth2 Refresh Token | Maintain authorization | Consent |

### 2.2 Information Collected Automatically

When you interact with our Service, we automatically collect:

| Data Type | Purpose | Retention |
|-----------|---------|-----------|
| IP Address (hashed) | Security, abuse prevention | 90 days |
| Consent Timestamps | Legal compliance | Duration of account + 4 years |
| Authorization Events | Audit trail | 1 year |
| Usage Timestamps | Service operation | Duration of account |

### 2.3 Information We Do NOT Collect

We do not collect:
- Message content from Discord
- Your email address
- Payment information
- Location data (beyond IP-derived country)
- Contacts or friends lists
- Server messages or content

## 3. How We Use Your Information

We use your information for the following purposes:

### 3.1 Service Operation
- Adding you to Discord servers when administrators initiate recovery
- Maintaining your authorization status
- Refreshing expired tokens

### 3.2 Security and Abuse Prevention
- Detecting and preventing fraudulent or abusive use
- Enforcing our Terms of Service
- Protecting against unauthorized access

### 3.3 Legal Compliance
- Responding to legal requests
- Maintaining audit trails
- Fulfilling data subject requests

### 3.4 Service Improvement
- Analyzing usage patterns (aggregated, non-identifying)
- Debugging and fixing issues

**We do NOT:**
- Sell your personal data
- Share your data for advertising purposes
- Use your data for profiling or automated decision-making
- Transfer your data to third parties except as described herein

## 4. Legal Basis for Processing (GDPR)

For users in the European Economic Area (EEA) and UK, we process your data under the following legal bases:

| Processing Activity | Legal Basis | GDPR Article |
|---------------------|-------------|--------------|
| OAuth token storage | Consent | Art. 6(1)(a) |
| Adding to servers | Consent | Art. 6(1)(a) |
| Security logging | Legitimate Interest | Art. 6(1)(f) |
| Legal compliance | Legal Obligation | Art. 6(1)(c) |

You may withdraw consent at any time by using the `!deletemydata` command or contacting us. Withdrawal does not affect the lawfulness of processing before withdrawal.

## 5. Data Storage and Security

### 5.1 Encryption
All OAuth2 tokens are encrypted using AES-256 encryption (Fernet/cryptography library) before storage. Encryption keys are stored separately from the encrypted data.

### 5.2 Storage Location
Your data is stored on servers located in SE, Stockholm. For international transfers, see Section 8.

### 5.3 Security Measures
We implement appropriate technical and organizational measures including:
- Encryption at rest and in transit
- Access controls and authentication
- Regular security reviews
- Audit logging
- Secure key management

### 5.4 Data Breach Procedures
In the event of a data breach that poses a risk to your rights:
- We will notify relevant supervisory authorities within 72 hours
- We will notify affected users without undue delay
- We will document all breaches and remediation actions

## 6. Data Retention

We retain your data for the following periods:

| Data Category | Retention Period | Reason |
|---------------|------------------|--------|
| OAuth tokens | Until you revoke or delete | Service operation |
| Account data | Duration of authorization | Service operation |
| Consent records | 4 years after deletion | Legal compliance (CCPA) |
| Security logs | 1 year | Security, abuse prevention |
| Deletion request records | 4 years | Legal compliance |

After retention periods expire, data is securely deleted.

## 7. Your Rights

### 7.1 Rights for All Users

All users have the right to:
- **Access** your data (`!mydata` command)
- **Delete** your data (`!deletemydata` command)
- **Revoke** authorization at any time
- **Contact us** with privacy concerns

### 7.2 Additional Rights for EEA/UK Users (GDPR)

If you are in the EEA or UK, you additionally have the right to:

| Right | Description | How to Exercise |
|-------|-------------|-----------------|
| **Access** (Art. 15) | Obtain a copy of your data | `!mydata` command |
| **Rectification** (Art. 16) | Correct inaccurate data | Contact us |
| **Erasure** (Art. 17) | Delete your data | `!deletemydata` command |
| **Restriction** (Art. 18) | Limit processing | Contact us |
| **Portability** (Art. 20) | Receive data in machine-readable format | `!mydata` command (JSON) |
| **Object** (Art. 21) | Object to processing | Contact us |
| **Withdraw Consent** (Art. 7) | Withdraw consent anytime | `!deletemydata` or contact us |
| **Lodge Complaint** | Complain to supervisory authority | See Section 7.4 |

### 7.3 Additional Rights for California Users (CCPA)

If you are a California resident, you have the right to:
- **Know** what personal information we collect
- **Delete** your personal information
- **Non-discrimination** for exercising your rights

**We do not sell personal information.** Therefore, there is no need to opt-out of sale.

### 7.4 How to Exercise Your Rights

**Self-Service (Recommended):**
- Export data: Use `!mydata` in any server with our bot
- Delete data: Use `!deletemydata` in any server with our bot

**Contact Us:**
- Email: recover3000botaddress@keemail.me
- Response time: Within 30 days (may extend to 90 days for complex requests)
- Verification: We may need to verify your identity via Discord

**Supervisory Authority:**
EEA/UK users may lodge complaints with their local Data Protection Authority. A list is available at: https://edpb.europa.eu/about-edpb/about-edpb/members_en

## 8. International Data Transfers

Our servers are located in Sweden. If you are located outside this country, your data will be transferred internationally.

### 8.1 Transfer Mechanisms

For transfers from the EEA/UK, we rely on:
- **EU-US Data Privacy Framework** (for US transfers where applicable)
- **Standard Contractual Clauses** (where DPF doesn't apply)

### 8.2 Adequacy

We ensure that any international transfers provide an adequate level of protection for your data as required by applicable law.

## 9. Third-Party Services

### 9.1 Discord
We interact with Discord's API to provide our Service. Discord has its own Privacy Policy: https://discord.com/privacy

### 9.2 Hosting Providers
Our servers are hosted by an undisclosed host (contact support for further information). They act as a data processor under our instructions.

### 9.3 No Other Third Parties
We do not share your data with any other third parties except:
- When required by law
- To protect our rights or safety
- With your explicit consent

## 10. Children's Privacy

### 10.1 Age Requirement
Our Service is not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13.

### 10.2 COPPA Compliance
If we learn that we have collected personal information from a child under 13, we will delete that information immediately.

### 10.3 Parental Rights
If you are a parent or guardian and believe your child has provided us with personal information, please contact us immediately.

## 11. Cookies and Tracking

### 11.1 Our Website
Our OAuth consent page does not use cookies for tracking. We use only essential session data to complete the authorization process.

### 11.2 Discord
Any cookies or tracking used by Discord are governed by Discord's Privacy Policy.

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be indicated by updating the "Last Updated" date.

**Material Changes:** For significant changes affecting your rights, we will:
- Update the consent version number
- Notify users via Discord announcement
- Require re-consent if legally necessary

**Continued Use:** Your continued use of the Service after changes constitutes acceptance of the updated policy.

## 13. Contact Us

For privacy-related questions, requests, or concerns:

**Email:** recover3000botaddress@keemail.me  
**Discord:** https://discord.gg/nn32uPVeFX  
**Response Time:** Unable to be certain

For EU users, you may also contact our representative (if applicable):
[EU REPRESENTATIVE DETAILS - if you have one, otherwise remove this section]

## 14. Additional Disclosures

### 14.1 Do Not Track
We do not track users across third-party websites and therefore do not respond to Do Not Track signals.

### 14.2 Analytics
We may collect aggregated, non-identifying analytics (such as total user counts). This data cannot be used to identify individual users.

### 14.3 Law Enforcement
We may disclose your information if required by law or in response to valid legal process. Where permitted, we will notify you of such requests.

---

## Summary of Key Points

| Topic | Summary |
|-------|---------|
| **What we collect** | Discord ID, username, OAuth tokens |
| **Why we collect it** | To add you to servers during recovery |
| **How we protect it** | AES-256 encryption, access controls |
| **How long we keep it** | Until you delete it |
| **Your rights** | Access, delete, export, object |
| **Do we sell data?** | No, never |
| **Contact** | recover3000botaddress@keemail.me |

---

By using our Service, you acknowledge that you have read and understood this Privacy Policy.
