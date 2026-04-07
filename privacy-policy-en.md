---
layout: default
title: Privacy Policy
permalink: /privacy-policy-en/
lang: en
alt_url: /privacy-policy/
alt_label: 한국어
---


> **App Name**: Cleio
> **Bundle ID**: io.cleio.app
> **Operator**: Kidae Lee (이기대)
> **Contact**: kdwara@icloud.com
> **Address**: 7, Yangdal-ro, Gwangmyeong-si, Gyeonggi-do, Republic of Korea
> **Business Registration No.**: 611-48-01233
> **Version**: 1.0
> **Effective Date**: 2026-05-01
>
> This document is a translation provided for convenience only. The Korean-language version is the authoritative original. In case of any conflict between this translation and the Korean original, the Korean original shall prevail.

---

## Table of Contents

1. [Overview](#article-1-overview)
2. [Data We Collect](#article-2-data-we-collect)
3. [Purposes of Processing](#article-3-purposes-of-processing)
4. [Retention Periods](#article-4-retention-periods)
5. [Third-Party Disclosure](#article-5-third-party-disclosure)
6. [Outsourced Processing](#article-6-outsourced-processing)
7. [International Data Transfers](#article-7-international-data-transfers)
8. [Your Rights and How to Exercise Them](#article-8-your-rights-and-how-to-exercise-them)
9. [Data Deletion and Destruction](#article-9-data-deletion-and-destruction)
10. [Automatic Data Collection](#article-10-automatic-data-collection)
11. [App Permissions](#article-11-app-permissions)
12. [Children's Privacy](#article-12-childrens-privacy)
13. [Data Security](#article-13-data-security)
14. [Privacy Officer](#article-14-privacy-officer)
15. [Changes to This Policy](#article-15-changes-to-this-policy)
16. [Contact and Remediation Bodies](#article-16-contact-and-remediation-bodies)

---

## Article 1. Overview

Cleio (the "App") is an iOS application operated by Kidae Lee (the "Operator") that provides voice recording, real-time speech-to-text transcription, speaker diarization, and AI summarization. This Privacy Policy explains how the Operator collects, uses, stores, and protects your personal information when you use the App.

By using the App, you acknowledge that you have read and understood this Privacy Policy. If you do not agree with its terms, please do not use the App.

---

## Article 2. Data We Collect

### 2.1 Data You Create Directly

| Data | Purpose | Storage | External Transfer | Retention |
|------|---------|---------|-------------------|-----------|
| Audio recordings (M4A) | Core service — voice recording | Local device + iCloud (Pro) | None | Until deleted by user |
| Transcription text | Speech-to-text conversion results | Local (SwiftData) + iCloud (Pro) | OpenAI API (Pro only, text correction/summarization; text only) | Until deleted by user |
| AI summary text | Meeting/conversation summaries | Local (SwiftData) + iCloud (Pro) | OpenAI API (Pro only, summarization; text only) | Until deleted by user |
| Speaker diarization results | Per-utterance speaker identification | Local (SwiftData) | None | Until deleted by user |
| App settings | User preferences | UserDefaults + iCloud KVS (Pro) | None | Until app deletion |

**Audio files are never transmitted to external servers under any circumstances.** Only text is sent to the OpenAI API.

### 2.2 Automatically Collected Data

| Data | SDK | Purpose | Destination |
|------|-----|---------|-------------|
| App usage events | Firebase Analytics | Service improvement | Google LLC (United States) |
| Crash logs | Firebase Crashlytics | Stability improvement | Google LLC (United States) |
| App performance metrics | Firebase Performance | Performance monitoring | Google LLC (United States) |
| Subscription status | StoreKit 2 | Payment management | Apple Inc. (United States) |

Automatically collected data does not include recording content or transcription text.

---

## Article 3. Purposes of Processing

The Operator processes personal information for the following purposes.

1. **Core Service Delivery** — Audio recording, speech-to-text transcription, speaker diarization, and AI summarization.
2. **Pro Subscription Features** — OpenAI-powered text correction and GPT summarization, iCloud synchronization, and export capabilities (Markdown/PDF).
3. **Service Improvement** — Analysis of anonymized usage patterns to enhance features and user experience.
4. **Stability and Performance** — Collection of crash reports and performance metrics to maintain and improve app reliability.
5. **Payment Processing** — Managing subscription status through Apple's StoreKit.
6. **User Preferences** — Storing and synchronizing app settings across devices (Pro).

---

## Article 4. Retention Periods

Personal information is retained until the purpose of collection is fulfilled.

| Data Category | Retention Period | Destruction Method |
|---------------|-----------------|-------------------|
| Audio recordings | Until deleted by user within the App | Removed from local storage and iCloud |
| Transcription text, AI summaries, speaker diarization results | Until deleted by user within the App | Removed from SwiftData and iCloud |
| App settings | Until app is deleted from device | Cleared on app uninstallation |
| Firebase Analytics data | Per Google's data retention policy (default: 14 months) | Automatic expiration |
| Firebase Crashlytics data | Per Google's data retention policy (default: 90 days) | Automatic expiration |
| OpenAI API transmitted data | Deleted within 30 days per OpenAI's API data policy; not used for model training | Automatic deletion by OpenAI |

If retention is required by law, the relevant data is stored separately and destroyed after the statutory retention period expires.

---

## Article 5. Third-Party Disclosure

As a general rule, the Operator does not provide personal information to third parties. Exceptions include:

- When the user has given prior consent;
- When required by law or upon a lawful request from a law enforcement authority.

**The Operator does not sell, rent, or trade personal information to any third party.**

---

## Article 6. Outsourced Processing

The Operator entrusts certain data processing to the following service providers for the purpose of delivering the Service. These providers process data solely on the Operator's behalf and under the Operator's instructions.

| Processor | Entrusted Task | Retention | Contact |
|-----------|---------------|-----------|---------|
| OpenAI, Inc. (United States) | Pro: transcription text correction and AI summarization (text only; no audio) | Deleted within 30 days; not used for model training | privacy@openai.com |
| Google LLC (United States) | Firebase analytics, crash reporting, performance monitoring | Per Google's retention policy | https://firebase.google.com/support/privacy |
| Apple Inc. (United States) | StoreKit payment processing, iCloud storage (Pro) | Per Apple's retention policy | https://www.apple.com/privacy |

The Operator maintains written agreements with processors governing data protection obligations and oversees their compliance.

---

## Article 7. International Data Transfers

Your personal information may be transferred to and processed in countries outside your country of residence as follows.

| Recipient | Country | Data Transferred | Purpose | Legal Basis |
|-----------|---------|-----------------|---------|-------------|
| OpenAI, Inc. | United States | Transcription text, summary input text (Pro users only) | Text correction and GPT summarization | Performance of service contract |
| Google LLC | United States | Anonymized app usage events, crash logs, performance metrics | Analytics, stability, and performance monitoring | Performance of service contract |
| Apple Inc. | United States | Payment information, iCloud-synced data (Pro) | Payment processing and cloud storage | Performance of service contract |

These transfers are conducted in compliance with Article 28-8 of the Korean Personal Information Protection Act (PIPA) regarding cross-border data transfers.

---

## Article 8. Your Rights and How to Exercise Them

You (or your legal representative) may exercise the following rights.

1. Request access to your personal information
2. Request correction or deletion of your personal information
3. Request suspension of processing of your personal information
4. Withdraw consent

**How to exercise your rights**

- You can delete recordings and associated data directly within the App.
- You can revoke microphone permission at any time through your device settings.
- You may submit a request by email to kdwara@icloud.com. The Operator will process the request without undue delay and no later than **10 days** from receipt.

During the period in which a correction or deletion request is being processed, the Operator will not use or disclose the relevant personal information.

---

## Article 9. Data Deletion and Destruction

Personal information for which the purpose of collection has been fulfilled is destroyed without delay.

**Destruction methods**

- **Local device data**: Users may delete recordings and associated data directly within the App. Uninstalling the App removes all locally stored data (SwiftData, UserDefaults).
- **iCloud data (Pro)**: Deleted when the user deletes data within the App or disables iCloud sync. Users may also delete data directly from their device's iCloud settings.
- **Electronic files**: Deleted using methods that make recovery impossible (secure deletion).

---

## Article 10. Automatic Data Collection

Cleio does not use cookies or web-based tracking technologies. However, the following SDKs automatically collect data for service improvement purposes.

- **Firebase Analytics**: Collects anonymized app usage events (e.g., screen views, feature usage frequency). The App does not currently provide an in-app toggle to disable Firebase Analytics. To opt out, please contact kdwara@icloud.com.
- **Firebase Crashlytics**: Collects crash reports including device model, OS version, and stack traces. This data does not include personally identifiable content.
- **Firebase Performance**: Collects app performance metrics such as startup time and network request latency.

These SDKs are provided by Google LLC and operate under Google's Privacy Policy (https://policies.google.com/privacy).

---

## Article 11. App Permissions

Cleio requests the following device permissions.

| Permission | Purpose | Required |
|------------|---------|----------|
| Microphone | Audio recording | Required |

- Microphone permission is required for the App's core recording functionality. The App cannot function without microphone access.
- Speech-to-text (STT) is processed entirely on-device and does not require a separate speech recognition permission.
- Permissions can be managed through your device's Settings at any time.

---

## Article 12. Children's Privacy

Cleio is not directed at children under the age of **14**. The Operator does not knowingly collect personal information from children under 14.

The Operator takes the following measures to protect children's privacy.

- **App Store age rating**: The App's age rating on the App Store (15+ in Korea and Australia, A16 in Brazil, 16+ in 172 other countries) manages access by minors. The App does not implement its own age verification; users are responsible for confirming their eligibility to use the App.
- **No account registration**: The App does not require sign-up or login, so no personal information is directly collected through account creation.
- **Parent or guardian contact**: If a parent or guardian believes that a child has provided personal information, they should contact kdwara@icloud.com immediately. The Operator will delete such information without delay.

---

## Article 13. Data Security

The Operator implements the following technical and administrative safeguards to protect personal information (in accordance with Article 29 of the Enforcement Decree of the Korean Personal Information Protection Act).

**Technical Safeguards**

- **On-Device Processing**: Core features (speech-to-text transcription, speaker diarization, on-device AI summarization) operate entirely on the user's device. The on-device AI summarization uses Apple's Foundation Models framework and does not communicate with any external servers, including Apple's servers. Audio recordings and processing results are not transmitted externally unless Pro features are used.
- **Encryption in Transit**: All data transmitted to external services (OpenAI, Firebase) uses HTTPS/TLS encryption.
- **Encryption at Rest**: Data stored on the device is protected by iOS device encryption. iCloud data is protected by Apple's encryption standards.
- **Minimal Data Transmission**: Only the minimum data necessary for Pro features (text only) is transmitted to OpenAI. Audio files are never transmitted.
- **No Operator-Owned Servers**: The Operator does not operate its own servers. All user data is stored on the user's device or in their personal iCloud account.

**Administrative Safeguards**

- **Internal Management Plan**: The Operator (a sole operator) directly manages all personal information processing activities.
- **Access Control**: Only the Operator has access to personal information processing systems.
- **Vendor Monitoring**: Changes to the data processing policies of OpenAI, Google, and Apple are regularly monitored.
- **Breach Notification**: In the event of a personal information security incident, the Operator will notify affected individuals without delay.

---

## Article 14. Privacy Officer

The following person is responsible for overseeing all personal information processing matters and handling complaints and inquiries from data subjects.

| Role | Details |
|------|---------|
| Privacy Officer | Kidae Lee (이기대) |
| Email | kdwara@icloud.com |
| Responsibilities | Overseeing all personal information processing, handling data subject complaints and inquiries, and remedying any violations of data subject rights |

---

## Article 15. Changes to This Policy

The Operator may update this Privacy Policy. When changes are made:

1. The updated policy will be posted within the App.
2. The "Version" and "Effective Date" at the top of this document will be updated.
3. For changes that are unfavorable to users, prior notice of at least **30 days** will be provided via in-app notification or email before the changes take effect.

Your continued use of the App after the updated policy takes effect constitutes your acknowledgment of the changes.

---

## Article 16. Contact and Remediation Bodies

For questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact:

- **Email**: kdwara@icloud.com

You may also contact the following organizations for personal information dispute resolution.

| Organization | Contact |
|-------------|---------|
| Personal Information Dispute Mediation Committee (개인정보분쟁조정위원회) | 1833-6972 / https://www.kopico.go.kr |
| Personal Information Infringement Report Center (개인정보침해신고센터) | 118 / https://privacy.kisa.or.kr |
| Supreme Prosecutors' Office Cyber Investigation Division (대검찰청 사이버수사과) | 1301 / https://www.spo.go.kr |
| National Police Agency Cyber Bureau (경찰청 사이버수사국) | 182 / https://ecrm.cyber.go.kr |
