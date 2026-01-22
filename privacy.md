---
layout: null
---

# Expensley Privacy Policy

**Effective Date:** January 25, 2026  
**Last Updated:** January 25, 2026

**App Name:** Expensley (iOS app for iPhone/iPad)  
**Data Controller / Provider:** Mohamad Shybly (Einzelunternehmen / Sole Proprietorship, registered in Germany)  
**Contact Email:** mhd.shibly@hotmail.com  
**Terms of Service:** https://mhdsysy.github.io/terms

---

## Key Points Summary

- **Your financial data stays on your device** — we cannot access it
- **No account required** — no email, name, or personal details collected
- **AI features use temporary cloud processing** — data is not stored on our servers
- **No ads, no analytics, no tracking** — we don't sell or share your data
- **You control your data** — uninstalling the app deletes all local data
- **Compliant with GDPR, CCPA, and international privacy laws**

---

## 1. Overview

Expensley is designed with privacy as a core principle. Your financial data stays on your device, and we minimize data collection to only what's necessary to provide our services.

This privacy policy explains what data we collect, how we use it, and your rights regarding your information. It applies to users worldwide, including the EU/EEA, UK, USA, Canada, Australia, New Zealand, Switzerland, and UAE.

---

## 2. Data Controller Information

For the purposes of applicable data protection laws (including GDPR), the data controller is:

**Mohamad Shybly**  
Einzelunternehmen (Sole Proprietorship)  
Registered in Germany  
Email: mhd.shibly@hotmail.com

---

## 3. Data We Collect & Process

### 3.1 Local Data (On Your Device Only)

The following data is stored **exclusively on your device** and is never transmitted to our servers:

| Data Type | Description |
|-----------|-------------|
| **Transactions** | All your expense and income records |
| **Budgets** | Your budget configurations and spending limits |
| **Savings Goals** | Your savings targets and progress |
| **User Preferences** | Currency settings, starting balance, and app configuration |
| **Category Patterns** | Learned categorization preferences based on your corrections |

This data is stored using Apple's Core Data framework and is protected by your device's security features (passcode, Face ID, Touch ID). **We cannot access, read, or recover this data.**

### 3.2 Cloud-Processed Data (Temporary, Not Stored)

When you use AI-powered features, data is temporarily processed through our secure cloud service:

#### Natural Language Input
When you type expenses like "coffee 5" or "uber 15", the text is sent to our API for parsing.

- **What is sent:** The text you type
- **What is NOT sent:** Your transaction history, balances, or other financial data
- **Legal basis (GDPR):** Performance of contract / Legitimate interest

#### Receipt & Document Scanning
When you scan receipts or documents, the image is sent for text extraction and parsing.

- **What is sent:** The scanned image
- **What is NOT sent:** Your other transactions, personal data, or financial history
- **Processing Pipeline:**
  1. Image is sent to Google Document AI for OCR (text extraction)
  2. Extracted text is processed by Claude AI to identify transaction details
  3. Structured result (merchant, amount, category) is returned to your device
  4. **Images are NOT stored** — they are processed in memory and immediately discarded
- **Legal basis (GDPR):** Performance of contract / Legitimate interest

#### Currency Exchange Rates
When you change currencies, we fetch current exchange rates.

- **What is sent:** Currency codes only (e.g., "USD", "EUR")
- **What is NOT sent:** Your balances or transaction data
- **Legal basis (GDPR):** Performance of contract

### 3.3 Device Identification

#### Rate Limiting & Abuse Prevention
To prevent abuse and enforce fair usage limits, we generate a random identifier stored locally on your device:

- Is a randomly generated UUID (not linked to your Apple ID or personal identity)
- Is used solely for rate limiting and subscription validation
- Cannot be used to identify you personally
- Is stored locally in your device's UserDefaults
- **Legal basis (GDPR):** Legitimate interest (service security and abuse prevention)

#### Apple App Attest
We use Apple's App Attest service to verify that requests come from legitimate app installations. This helps protect against API abuse and fraud. App Attest verification is handled entirely by Apple's secure enclave and does not expose personal information.

---

## 4. What We Do NOT Collect

Expensley does **NOT**:

- ❌ Require account creation or login
- ❌ Link to your bank accounts
- ❌ Collect your name, email, phone number, or address
- ❌ Store your financial transactions on our servers
- ❌ Store your scanned receipts or documents
- ❌ Use advertising or analytics SDKs
- ❌ Sell or share your data with advertisers
- ❌ Track your location
- ❌ Access your contacts, photos (except user-initiated scans), or other device data
- ❌ Use cookies or tracking technologies

---

## 5. Third-Party Services

Expensley uses the following third-party services for cloud features:

| Service | Purpose | Data Shared | Location |
|---------|---------|-------------|----------|
| **Anthropic (Claude AI)** | Natural language parsing, receipt data extraction | Input text, extracted receipt text | USA |
| **Google Document AI** | OCR text extraction from images | Scanned document images (not stored) | USA |
| **Open Exchange Rates** | Currency conversion rates | Currency codes only | USA |
| **Apple StoreKit** | Subscription management | Managed by Apple | USA/Ireland |
| **Apple App Attest** | Device verification | Cryptographic attestation | USA/Ireland |

These services process data according to their respective privacy policies:
- [Anthropic Privacy Policy](https://www.anthropic.com/privacy)
- [Google Cloud Privacy Policy](https://cloud.google.com/terms/cloud-privacy-notice)
- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

---

## 6. International Data Transfers

When you use AI features, your data may be transferred to and processed in the United States by our third-party service providers (Anthropic, Google).

For EU/EEA/UK users, these transfers are made in compliance with applicable data protection laws using appropriate safeguards, such as:
- Standard Contractual Clauses (SCCs) adopted by the European Commission
- The service providers' certifications and compliance frameworks

For Swiss users, transfers comply with the Swiss Federal Act on Data Protection (revDSG/nFADP).

---

## 7. Data Retention

### On-Device Data
Your local data remains on your device until you delete the app or manually delete transactions. We have no access to this data.

### Cloud Processing
Data sent for AI processing (text input, scanned images) is processed in real-time and **not stored**. Our cloud infrastructure does not maintain logs of your financial information.

### Third-Party Retention
Third-party AI services (Anthropic, Google) may have their own data retention policies for processing purposes. We encourage you to review their privacy policies for details.

---

## 8. Data Security

We protect data in transit using:

- **HTTPS/TLS encryption** for all API communications
- **Apple App Attest** for request authenticity verification
- **JWT session tokens** with expiration for API authentication

Your on-device data is protected by iOS's built-in security features, including encryption at rest.

---

## 9. Subscriptions

Expensley offers optional premium subscriptions managed through Apple's App Store. Subscription purchases and management are handled entirely by Apple. We receive:

- Confirmation of subscription status (active, expired, tier)
- No payment information or personal details

For subscription-related privacy information, refer to [Apple's App Store Privacy Policy](https://www.apple.com/legal/privacy/).

---

## 10. Children's Privacy

Expensley is not specifically directed to children under 13. We do not knowingly collect personal information from children.

- **No account required:** The app does not request children to provide personal information
- **Parental responsibility:** Parents/guardians are responsible for supervising minors' use, especially when scanning documents that could contain personal information
- **COPPA Compliance (USA):** We do not knowingly collect personal information from children under 13
- **All ages accessible:** Since no personal information is collected, the app can be used by anyone

---

## 11. Your Privacy Rights

### 11.1 Rights for All Users

Since all your financial data is stored locally on your device:

- **Access:** Your data is always accessible within the app
- **View:** You can view all your transactions, budgets, and goals in the app
- **Delete:** Uninstalling the app permanently deletes all local data
- **Opt-Out of Cloud Features:** You can use Expensley entirely offline for basic expense tracking

### 11.2 EU/EEA & UK Users (GDPR / UK GDPR)

If you are in the European Union, European Economic Area, or United Kingdom, you have the following rights under GDPR:

| Right | Description | How to Exercise |
|-------|-------------|-----------------|
| **Access** | Request a copy of your personal data | Your data is on your device; contact us for processing records |
| **Rectification** | Correct inaccurate data | Edit directly in the app |
| **Erasure ("Right to be Forgotten")** | Request deletion of your data | Uninstall the app; contact us for processing records |
| **Restriction** | Limit how we process your data | Disable AI features; use offline mode |
| **Data Portability** | Receive your data in a portable format | Your data is on your device |
| **Object** | Object to processing based on legitimate interest | Contact us at mhd.shibly@hotmail.com |
| **Withdraw Consent** | Withdraw consent where processing is based on consent | Stop using AI features |

**Supervisory Authority:** You have the right to lodge a complaint with a data protection supervisory authority in your EU Member State. In Germany, this is the relevant Landesdatenschutzbeauftragte for your state, or the BfDI (Federal Commissioner for Data Protection).

### 11.3 California Users (CCPA/CPRA)

If you are a California resident, you have the following rights:

- **Right to Know:** What personal information we collect, use, and disclose
- **Right to Delete:** Request deletion of your personal information
- **Right to Opt-Out of Sale:** We do not sell your personal information
- **Right to Non-Discrimination:** We will not discriminate against you for exercising your rights

**Note:** Expensley is designed to operate without collecting personal information like name, email, address, location, or advertising identifiers. Where "personal information" is processed (e.g., content you choose to type or scan), it is used only to provide requested functionality.

To exercise your rights, contact: mhd.shibly@hotmail.com

### 11.4 Australia & New Zealand Users

If you are in Australia, you have rights under the Privacy Act 1988 and Australian Privacy Principles (APPs). If you are in New Zealand, you have rights under the Privacy Act 2020.

You may:
- Access your personal information
- Request correction of inaccurate information
- Make a complaint to the OAIC (Australia) or OPC (New Zealand)

### 11.5 Canada Users (PIPEDA)

Canadian users have rights under PIPEDA and applicable provincial privacy laws, including:
- Access to your personal information
- Correction of inaccurate information
- Right to withdraw consent

### 11.6 Switzerland Users (revDSG/nFADP)

Swiss users have rights under the Swiss Federal Act on Data Protection, including:
- Right to information about data processing
- Right to data portability
- Right to object to automated decision-making

### 11.7 UAE Users (PDPL)

UAE users may have rights under the UAE Personal Data Protection Law, including:
- Right to access personal data
- Right to request correction or deletion
- Right to object to processing

---

## 12. Changes to This Policy

We may update this privacy policy from time to time. We will notify you of significant changes by:
- Updating the "Last Updated" date at the top of this policy
- Providing notice within the app for material changes

Continued use of Expensley after an update means you acknowledge the updated policy.

---

## 13. Contact Us

If you have questions, concerns, or requests regarding this privacy policy or our data practices, please contact us at:

**Mohamad Shybly**  
Email: mhd.shibly@hotmail.com

For EU users: You may also contact your local data protection authority.

---

## 14. Data Summary Table

| Data Type | Stored | Where | Shared With | Retention |
|-----------|--------|-------|-------------|-----------|
| Transactions, Budgets, Goals | ✅ | Your device only | ❌ Never | Until you delete |
| Natural language input | ❌ | Processed, not stored | ✅ Anthropic (temporary) | Not retained |
| Scanned images | ❌ | Processed, not stored | ✅ Google, Anthropic (temporary) | Not retained |
| Device identifier (UUID) | ✅ | Your device only | ✅ Our API (rate limiting) | Until you delete |
| Subscription status | ✅ | Apple's servers | ✅ Apple only | Per Apple's policy |

---

## 15. Legal Basis for Processing (GDPR)

| Processing Activity | Legal Basis |
|--------------------|-------------|
| Providing core app features (local storage) | Performance of contract |
| AI text parsing | Performance of contract / Legitimate interest |
| Receipt scanning & OCR | Performance of contract / Legitimate interest |
| Currency exchange rates | Performance of contract |
| Rate limiting (device UUID) | Legitimate interest (security, abuse prevention) |
| Subscription management | Performance of contract (via Apple) |

---

*This privacy policy is designed to be transparent and honest about our data practices. Expensley is built for people who value their financial privacy.*
