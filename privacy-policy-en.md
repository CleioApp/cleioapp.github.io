---
layout: default
title: Privacy Policy
permalink: /privacy-policy-en/
lang: en
alt_links:
  - { url: /privacy-policy/, label: 한국어, hreflang: ko }
  - { url: /privacy-policy-ja/, label: 日本語, hreflang: ja }
---

> **App Name**: Cleio
> **Bundle ID**: io.cleio.app
> **Operator**: Kidae Lee (이기대)
> **Contact**: kdwara@icloud.com
> **Address**: 7, Yangdal-ro, Gwangmyeong-si, Gyeonggi-do, Republic of Korea
> **Business Registration No.**: 611-48-01233
> **Version**: 1.2
> **Effective Date**: 2026-06-08
> **Last Updated**: 2026-08-13
>
> This document is a translation provided for convenience only. The Korean-language version is the authoritative original. In case of any conflict between this translation and the Korean original, the Korean original shall prevail.
>
> **Correction on 2026-08-06**: Reminders synchronization now edits and deletes items in addition to adding them, so related descriptions in Articles 2, 4, 8, and 11 have been corrected to match the actual behavior (deletion paths performed by Cleio were added, and a reference to a non-existent in-app toggle was removed). This does not change your rights or the terms of service, so the effective date remains unchanged.
>
> **Second correction on 2026-08-06**: The description of where audio files are transmitted has been corrected to match the actual behavior. Article 2 now states that audio files are stored and synced to the user's own Apple iCloud when a Pro subscriber enables iCloud sync, and the broad negation "not transmitted to third parties" has been narrowed to the parties actually negated — "the Operator's servers or OpenAI" (the same applies to Calendar event data). No processing practice has changed; only its description has been made accurate, so the effective date remains unchanged.
>
> **Correction on 2026-08-13**: Following a change to the app's UI labeling (v1.4), related terminology in this Policy has been aligned with the app's on-screen "usage" label (Articles 6, 7, and 13). The actual scope of outsourced processing and security measures is unchanged, so the effective date remains unchanged.
>
> **Key changes in v1.2**: Added multilingual meeting translation (Pro), two-way Reminders (EventKit) sync, disclosure of Calendar (EventKit) automatic event matching, iPhone storage optimization (Pro+iCloud), and disclosure of Firebase Cloud Functions backend infrastructure.

---

## Table of Contents

1. [Overview](#article-1-overview)
2. [Data We Collect](#article-2-data-we-collect)
3. [Purposes of Processing](#article-3-purposes-of-processing)
4. [Retention Periods](#article-4-retention-periods)
5. [Third-Party Disclosure](#article-5-third-party-disclosure)
6. [Outsourced Processing](#article-6-outsourced-processing)
6-2. [Prior Consent for Cloud AI Features](#article-6-2-prior-consent-for-cloud-ai-features)
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
| Transcription text | Speech-to-text conversion results | Local (SwiftData) + iCloud (Pro) | OpenAI API (Pro text correction / summarization / translation; text only) | Until deleted by user |
| AI summary text | Meeting/conversation summaries | Local (SwiftData) + iCloud (Pro) | OpenAI API (Pro summarization; text only) | Until deleted by user |
| Action items (to-dos) | To-do items extracted from summaries | Local (SwiftData) + iCloud (Pro) + Reminders app (EventKit, when the user syncs) | None | Until deleted by user |
| Speaker diarization results | Per-utterance speaker identification | Local (SwiftData) + iCloud (Pro) | None | Until deleted by user |
| Calendar event matching data (event title, identifier, date/time) | Automatic matching of recordings with Calendar events | Local (SwiftData) + iCloud (Pro) | None | Until deleted by user |
| Translation text (Pro) | Display original/translated text for multilingual meetings | Local (SwiftData) + iCloud (Pro) | OpenAI API (when user requests translation; text only) | Until deleted by user |
| App settings | User preferences | UserDefaults + iCloud KVS (Pro) | None | Until app deletion |

**Audio files are never transmitted to the Operator's servers or to OpenAI.** If a Pro subscriber enables iCloud sync, audio files are stored and synced to the user's own Apple iCloud. Only text is sent to OpenAI, and **the user's explicit consent is always obtained before any transmission** (see **Article 6-2** for details).

**Calendar event data is read only on-device and is never transmitted to the Operator's servers.** When Calendar permission is granted, the App reads event information solely to match recordings with Calendar events, and caches only the matching event's title, identifier, and date/time on the device; for Pro subscribers this cached metadata syncs only to the user's own Apple iCloud. Denying Calendar permission does not affect core features such as recording, transcription, and summarization.

### 2.2 Automatically Collected Data

| Data | SDK | Purpose | Destination |
|------|-----|---------|-------------|
| App usage events | Firebase Analytics | Service improvement | Google LLC (United States) |
| Crash logs | Firebase Crashlytics | Stability improvement | Google LLC (United States) |
| App performance metrics | Firebase Performance | Performance monitoring | Google LLC (United States) |
| Subscription status | StoreKit 2 | Payment management | Apple Inc. (United States) |

Automatically collected data does not include recording content or transcription text.

### 2.2-A iPhone Storage Optimization (Pro, opt-in)

When the user explicitly enables "iPhone Storage Optimization," the Operator processes data as follows.

- Audio files stored locally on the device are automatically deleted and retained only in iCloud Drive (the user's personal Apple account).
- Text data (transcription, summaries, action items, etc.) is unaffected (kept both locally and in iCloud).
- Audio files are automatically downloaded from iCloud Drive when playback or analysis is required.
- This feature is exclusive to Pro subscribers and can be disabled by the user at any time.

---

## Article 3. Purposes of Processing

The Operator processes personal information for the following purposes.

1. **Core Service Delivery** — Audio recording, speech-to-text transcription, real-time speaker diarization, and AI summarization.
2. **Pro Subscription Features** — OpenAI-powered text correction, GPT summarization, and multilingual meeting translation; iCloud synchronization (real-time data and iPhone storage optimization); export capabilities (Markdown/PDF).
3. **Two-Way Reminders Synchronization (opt-in)** — Two-way sync of action items with the iOS Reminders app (EventKit).
4. **Calendar Event Automatic Matching (opt-in)** — Automatically linking recordings with Calendar (EventKit) events for easier management.
5. **Service Improvement** — Analysis of anonymized usage patterns to enhance features and user experience.
6. **Stability and Performance** — Collection of crash reports and performance metrics to maintain and improve app reliability.
7. **Payment Processing** — Managing subscription status through Apple's StoreKit.
8. **User Preferences** — Storing and synchronizing app settings across devices (Pro).

---

## Article 4. Retention Periods

Personal information is retained until the purpose of collection is fulfilled.

| Data Category | Retention Period | Destruction Method |
|---------------|-----------------|-------------------|
| Audio recordings | Until deleted by user within the App | Removed from local storage and iCloud |
| Transcription text, AI summaries, speaker diarization results, action items, translation text, calendar matching data | Until deleted by user within the App | Removed from SwiftData and iCloud |
| App settings | Until app is deleted from device | Cleared on app uninstallation |
| Firebase Analytics data | Per Google's data retention policy (default: 14 months) | Automatic expiration |
| Firebase Crashlytics data | Per Google's data retention policy (default: 90 days) | Automatic expiration |
| Firebase Cloud Functions logs (OpenAI proxy, payment verification) | Per Google Cloud Logging default retention (30 days); no personally identifying content | Automatic expiration |
| OpenAI API transmitted data (text correction, summarization, translation) | Deleted within 30 days per OpenAI's API data policy; not used for model training | Automatic deletion by OpenAI |
| Reminders (EventKit) data | Per the iOS Reminders app's retention policy | Deleted when the user removes the item in the Reminders app, or when the user excludes it during a sync or deletes the action item in Cleio |

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
| OpenAI, Inc. (United States) | Pro: transcription text correction, AI summarization, multilingual translation (text only; no audio) | Deleted within 30 days; not used for model training | privacy@openai.com |
| Google LLC (United States) | Firebase analytics, crash reporting, performance monitoring, and Cloud Functions infrastructure operation (OpenAI proxy, subscription verification, usage management) | Per Google's retention policy | https://firebase.google.com/support/privacy |
| Apple Inc. (United States) | StoreKit payment processing, iCloud storage (Pro), Reminders (EventKit) data storage | Per Apple's retention policy | https://www.apple.com/privacy |

The Operator maintains agreements (or applicable standard terms, the Apple App Store agreement, and the OpenAI Data Processing Addendum) with processors governing data protection obligations and oversees their compliance.

---

## Article 6-2. Prior Consent for Cloud AI Features

The Operator provides the following Pro features that utilize OpenAI, Inc.'s (United States) GPT services.

| Feature | Transmitted Data | Recipient | Default State |
|---------|-----------------|-----------|---------------|
| Text correction (Pro) | Transcription text (STT), language settings, user term dictionary | OpenAI, Inc. (United States) | **Inactive** (default OFF) |
| AI summary (Pro) | Transcription text (STT), recording title, domain tag, summary length setting | OpenAI, Inc. (United States) | **Only when explicitly invoked by the user** |
| Multilingual meeting translation (Pro) | Transcript segment (source text), source language, target language | OpenAI, Inc. (United States) | **Only when explicitly requested by the user** |

**Not transmitted**: audio files, account identifiers (email, IDFA, etc.), device identifiers.

### Consent Process

When the user first invokes any of the features above, the App displays a **dedicated consent screen (bottom sheet)** that discloses the following:

- Data items to be transmitted and the purpose of collection
- Recipient (OpenAI, Inc.) and country (United States)
- Retention period (deleted within 30 days) and notice that OpenAI does not use the data for model training
- Notice that the feature will be unavailable if consent is declined, and that an on-device alternative is available
- Link to this Privacy Policy

**No data is transmitted to OpenAI until the user selects "Agree and Continue."** Consent for each feature (text correction, AI summary, multilingual translation) is managed **independently**, and consent status is stored only on the device (not synchronized to iCloud).

### Withdrawal of Consent

The user may withdraw consent in the following ways.

- **Text correction**: Toggle off "AI Text Correction" in Settings > AI Features.
- **AI summary**: Select **on-device summary** on the summary screen instead of Pro (cloud) summary.
- **Multilingual meeting translation**: No data is transmitted unless the user actively requests a translation. Cached translations are deleted together with the source transcription when the transcription is deleted.
- **Full withdrawal**: Cancel the Pro subscription — once canceled, all cloud AI features are deactivated, and no further data is transmitted to OpenAI.

### Cloud-Free Alternatives

The App provides the following **on-device processing** as the default, allowing core functionality to be used without consenting to the cloud AI features above.

- Speech-to-text (STT): WhisperKit (on-device processing)
- Speaker diarization: FluidAudio (on-device processing for both real-time and post-processing)
- AI summary: Apple Foundation Models (on-device processing, iOS 26.1+)
- Translation: Pro-exclusive feature; no OpenAI transmission if translation is not used

---

## Article 7. International Data Transfers

Your personal information may be transferred to and processed in countries outside your country of residence as follows.

| Recipient | Country | Data Transferred | Purpose | Legal Basis |
|-----------|---------|-----------------|---------|-------------|
| OpenAI, Inc. | United States | Transcription text, summary input text, translation input text (Pro features only, with user consent) | Text correction, GPT summarization, multilingual translation | User prior consent (Article 6-2) |
| Google LLC | United States | (a) Anonymized app usage events, crash logs, performance metrics; (b) Cloud Functions invocation logs (no personally identifying content) | Analytics, stability, and performance monitoring; backend infrastructure operation (OpenAI proxy, subscription verification, usage management) | Performance of service contract |
| Apple Inc. | United States | Payment information, iCloud-synced data (Pro), Reminders (EventKit) data | Payment processing, cloud storage, two-way iOS Reminders synchronization | Performance of service contract |

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
- You can revoke permissions such as microphone, Calendar, and Reminders at any time through your device settings.
- You may submit a request by email to kdwara@icloud.com. The Operator will process the request without undue delay and no later than **10 days** from receipt.
- Withdrawal of consent for cloud AI features (text correction, AI summary, multilingual translation) is described in the **Withdrawal of Consent** section of **Article 6-2**.
- Two-way Reminders synchronization applies only to action items you have chosen to keep in Reminders via [Sync Reminders] on the summary screen. Revoking the Reminders permission in your device settings stops all synchronization; deleting an individual item in the Reminders app stops synchronization for that item only.

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
| Calendar (EventKit) | Automatic matching of recordings with Calendar events | Optional — if declined, recording/transcription/summarization features continue to work normally; only the Calendar automatic matching feature is disabled |
| Reminders (EventKit) | Two-way action item synchronization between the App and the iOS Reminders app | Optional — if declined, transcription/summarization features continue to work; only the Reminders sync feature is disabled |

- Microphone permission is required for the App's core recording functionality. The App cannot function without microphone access.
- Speech-to-text (STT) is processed entirely on-device and does not require a separate speech recognition permission.
- Calendar permission is used only for matching recordings with Calendar events. Event data is read on-device only and is never transmitted to the Operator's servers (for Pro subscribers, the matching metadata syncs only to the user's own Apple iCloud). Core functionality of the App continues to work without it.
- The Reminders permission is used only to sync action items with the iOS Reminders app (adding, editing, and deleting). Core functionality of the App continues to work without it.
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

- **On-Device Processing Prioritized**: Core features (speech-to-text transcription, real-time speaker diarization, on-device AI summarization) operate entirely on the user's device. The on-device AI summarization uses Apple's Foundation Models framework and does not communicate with any external servers, including Apple's servers. Unless Pro cloud features (text correction, GPT summary, translation) are used, recordings, transcripts, and summary content are not transmitted to the Operator's servers or to OpenAI. However, Firebase data collected for app usage statistics and error diagnostics is transmitted regardless of subscription tier (see Article 2 and Article 10).
- **Encryption in Transit**: All data transmitted to external services (OpenAI, Firebase Cloud Functions, Apple) uses HTTPS/TLS encryption.
- **Encryption at Rest**: Data stored on the device is protected by iOS device encryption. iCloud data is protected by Apple's encryption standards.
- **Minimal Data Transmission**: Only the minimum data necessary for Pro features (text only) is transmitted to OpenAI. Audio files are never transmitted to OpenAI.
- **Backend Infrastructure (Firebase Cloud Functions)**: The Operator operates Google Firebase Cloud Functions (United States region, project `cleio-prod`) for the following purposes.
  - OpenAI API proxy (API key protection and usage management)
  - Subscription verification (Apple StoreKit JWS signature validation)
  - Usage limit management and usage logging
  - This infrastructure is invoked only for transcription/summary/translation requests, and original media such as audio files are never transmitted to it.

**Administrative Safeguards**

- **Internal Management Plan**: The Operator (a sole operator) directly manages all personal information processing activities.
- **Access Control**: Only the Operator has access to Firebase Cloud Functions and the OpenAI API console.
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
