---
title: Privacy Policy
---

# Expensley Privacy Policy

**Effective Date:** January 18, 2026  
**Last Updated:** January 18, 2026

---

## Overview

Expensley is designed with privacy as a core principle. Your financial data stays on your device, and we minimize data collection to only what's necessary to provide our services.

This privacy policy explains what data we collect, how we use it, and your rights regarding your information.

---

## Data Storage

### Local Data (On Your Device)

The following data is stored **exclusively on your device** and is never transmitted to our servers:

- **Transactions** — All your expense and income records
- **Budgets** — Your budget configurations and spending limits
- **Savings Goals** — Your savings targets and progress
- **User Preferences** — Currency settings, starting balance, and app configuration
- **Category Patterns** — Learned categorization preferences based on your corrections

This data is stored using Apple's Core Data framework and is protected by your device's security features (passcode, Face ID, Touch ID). We cannot access, read, or recover this data.

---

## Data Processing

### AI Features (Cloud Processing)

When you use certain AI-powered features, data is temporarily processed through our secure cloud service:

#### Natural Language Input
When you type expenses like "coffee 5" or "uber 15", the text you enter is sent to our API to be parsed by Claude (Anthropic's AI) into structured data. 

**What is sent:** The text you type  
**What is NOT sent:** Your transaction history, balances, or other financial data

#### Receipt & Document Scanning
When you scan receipts or documents, the image is sent to our API for text extraction and parsing.

**What is sent:** The scanned image  
**What is NOT sent:** Your other transactions, personal data, or financial history

**Processing Pipeline:**
1. Image is sent to Google Document AI for OCR (text extraction)
2. Extracted text is processed by Claude AI to identify transaction details
3. Structured result (merchant, amount, category) is returned to your device
4. **Images are NOT stored** — they are processed in memory and immediately discarded

#### Exchange Rates
When you change currencies, we fetch current exchange rates from a third-party service.

**What is sent:** Currency codes only (e.g., "USD", "EUR")  
**What is NOT sent:** Your balances or transaction data

---

## Device Identification

### Rate Limiting & Abuse Prevention

To prevent abuse and enforce fair usage limits, we generate a random identifier stored locally on your device. This identifier:

- Is a randomly generated UUID (not linked to your Apple ID or personal identity)
- Is used solely for rate limiting and subscription validation
- Cannot be used to identify you personally
- Is stored locally in your device's UserDefaults

### Apple App Attest

We use Apple's App Attest service to verify that requests come from legitimate app installations. This helps protect against API abuse and fraud. App Attest verification is handled entirely by Apple's secure enclave and does not expose personal information.

---

## Third-Party Services

Expensley uses the following third-party services for cloud features:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Anthropic (Claude AI)** | Natural language parsing, receipt data extraction | Input text, extracted receipt text |
| **Google Document AI** | OCR text extraction from images | Scanned document images |
| **Open Exchange Rates** | Currency conversion rates | Currency codes only |
| **Apple StoreKit** | Subscription management | Managed by Apple; see Apple's Privacy Policy |
| **Apple App Attest** | Device verification | Cryptographic attestation; see Apple's Privacy Policy |

These services process data according to their respective privacy policies:
- [Anthropic Privacy Policy](https://www.anthropic.com/privacy)
- [Google Cloud Privacy Policy](https://cloud.google.com/terms/cloud-privacy-notice)
- [Apple Privacy Policy](https://www.apple.com/legal/privacy/)

---

## What We Do NOT Collect

Expensley does **NOT**:

- ❌ Require account creation or login
- ❌ Link to your bank accounts
- ❌ Collect your name, email, phone number, or address
- ❌ Store your financial transactions on our servers
- ❌ Store your scanned receipts or documents
- ❌ Use advertising or analytics SDKs
- ❌ Sell or share your data with advertisers
- ❌ Track your location
- ❌ Access your contacts, photos, or other device data

---

## Data Retention

### On-Device Data
Your local data remains on your device until you delete the app or manually delete transactions. We have no access to this data.

### Cloud Processing
Data sent for AI processing (text input, scanned images) is processed in real-time and **not stored**. Our cloud infrastructure does not maintain logs of your financial information.

### Third-Party Retention
Third-party AI services (Anthropic, Google) may have their own data retention policies for processing purposes. We encourage you to review their privacy policies for details.

---

## Subscriptions

Expensley offers optional premium subscriptions managed through Apple's App Store. Subscription purchases and management are handled entirely by Apple. We receive:

- Confirmation of subscription status (active, expired, tier)
- No payment information or personal details

For subscription-related privacy information, refer to [Apple's App Store Privacy Policy](https://www.apple.com/legal/privacy/).

---

## Data Security

We protect data in transit using:

- **HTTPS/TLS encryption** for all API communications
- **Apple App Attest** for request authenticity verification
- **JWT session tokens** with expiration for API authentication

Your on-device data is protected by iOS's built-in security features, including encryption at rest.

---

## Children's Privacy

Expensley is not directed to children under 13. We do not knowingly collect personal information from children. Since no account creation is required and no personal information is collected, the app can be used by anyone.

---

## Your Rights

### Data Access & Deletion

Since all your financial data is stored locally on your device:

- **Access:** Your data is always accessible within the app
- **Export:** You can view all your transactions, budgets, and goals in the app
- **Delete:** Uninstalling the app permanently deletes all local data

### Opt-Out of Cloud Features

You can use Expensley entirely offline for basic expense tracking without using AI features. However, the following features require cloud processing:
- Natural language input parsing
- Receipt/document scanning
- AI insights and chat

---

## Changes to This Policy

We may update this privacy policy from time to time. We will notify you of significant changes by updating the "Last Updated" date at the top of this policy.

---

## Contact Us

If you have questions or concerns about this privacy policy or our data practices, please contact us at:

**Email:** [Your Support Email]  
**Website:** [Your Website URL]

---

## Summary

| Data Type | Stored | Where | Shared |
|-----------|--------|-------|--------|
| Transactions, Budgets, Goals | ✅ | Your device only | ❌ Never |
| Natural language input | ❌ | Processed, not stored | ✅ AI services (temporary) |
| Scanned images | ❌ | Processed, not stored | ✅ AI services (temporary) |
| Device identifier | ✅ | Your device only | ✅ Our API (rate limiting) |
| Subscription status | ✅ | Apple's servers | ✅ Apple only |

---

*This privacy policy is designed to be transparent and honest about our data practices. Expensley is built for people who value their financial privacy.*
