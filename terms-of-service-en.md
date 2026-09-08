---
layout: default
title: Terms of Service
permalink: /terms-of-service-en/
lang: en
alt_links:
  - { url: /terms-of-service/, label: 한국어, hreflang: ko }
  - { url: /terms-of-service-ja/, label: 日本語, hreflang: ja }
---

> **Version**: 1.4
> **Effective Date**: 2026-09-09
> **Last Updated**: 2026-09-08
>
> This document is a translation provided for convenience only. The Korean-language version is the authoritative original. In case of any conflict between this translation and the Korean original, the Korean original shall prevail.
>
> **Correction on 2026-08-06**: In the description of where audio files are transmitted, the broad negation "never transmitted to OpenAI or other third parties" has been narrowed to the parties actually negated — "the Operator's servers or OpenAI" (Article 4.2 and Article 10). Because audio files are stored on the user's own Apple iCloud when a Pro subscriber enables iCloud sync, the previous wording could be read as denying even that storage. This corrects the description rather than changing any terms, so the effective date remains unchanged.
>
> **Correction on 2026-08-13**: Following a change to the app's UI labeling (v1.4), related terminology in these Terms has been aligned with the app's on-screen "usage" label (Article 4.2 and Article 10). This does not change how the monthly limit is calculated, the subscription terms, pricing, or your rights, so the effective date remains unchanged.
>
> **Key changes in v1.2**: Added multilingual meeting translation (Pro), two-way Reminders (EventKit) synchronization, disclosure of Calendar (EventKit) automatic event matching, iPhone storage optimization (Pro), and disclosure of Firebase Cloud Functions backend infrastructure.
>
> **v1.4 (2026-09-09)**: Added System Audio Capture (Pro, macOS only) to the Pro plan — a feature that captures the audio of another app the user directly selects on the "New Recording" screen, and additionally records the microphone if the user turns on "Include My Voice" (Article 4.2, Article 7, Article 10, and Article 14 amended). The app captured may include the voices of third parties, such as call or meeting participants, and Article 7 now states that compliance with applicable law when recording those third parties is the user's responsibility. This feature is included in the first release of the macOS version of Cleio (v1.5.0) and has not been made available to any user before that release. Because this is a substantive addition to the list of Pro features and to user responsibilities, it is reflected as a version increment (1.3 → 1.4) rather than a mere correction, with the effective date updated to 2026-09-09.
>
> **v1.3 (2026-09-04)**: Added Apple Private Cloud AI summarization (built on Apple Inc.'s Private Cloud Compute technology) to the Pro plan — an opt-in feature the user selects directly in Settings; the default remains GPT (Article 4.2, Article 6, and Article 10 amended). As of this amendment, this feature has not been made available to any user (it has not yet shipped to the App Store) and will operate only once the app version containing it is actually released. Because this is a substantive addition to the list of Pro features and to how data is processed, it is reflected as a version increment (1.2 → 1.3) rather than a mere correction, with the effective date updated to 2026-09-04.
>
> **Correction on 2026-09-08**: The effective date has been adjusted from 2026-09-04 to **2026-09-09** to match the actual publication date. The amendments above had not been published and therefore never took effect as of 2026-09-04; their substance is unchanged.

---

## Operator Information

| Item | Details |
|------|---------|
| Service Name | Cleio |
| Operator | Kidae Lee (이기대) |
| Contact | kdwara@icloud.com |
| Address | 7, Yangdal-ro, Gwangmyeong-si, Gyeonggi-do, Republic of Korea |
| Business Registration No. | 611-48-01233 |

---

## Table of Contents

1. [General Provisions](#article-1-general-provisions)
2. [Eligibility](#article-2-eligibility)
3. [Account and Authentication](#article-3-account-and-authentication)
4. [Service Description and Plans](#article-4-service-description-and-plans)
5. [Subscription and Payment](#article-5-subscription-and-payment)
6. [User Content and Ownership](#article-6-user-content-and-ownership)
7. [Recording and Legal Compliance](#article-7-recording-and-legal-compliance)
8. [AI-Generated Content Disclaimer](#article-8-ai-generated-content-disclaimer)
9. [Prohibited Conduct](#article-9-prohibited-conduct)
10. [Data Processing and Privacy](#article-10-data-processing-and-privacy)
11. [Intellectual Property](#article-11-intellectual-property)
12. [Service Modification and Termination](#article-12-service-modification-and-termination)
13. [Disclaimer of Warranties](#article-13-disclaimer-of-warranties)
14. [Limitation of Liability](#article-14-limitation-of-liability)
15. [Governing Law and Dispute Resolution](#article-15-governing-law-and-dispute-resolution)
16. [General Provisions](#article-16-general-provisions)
17. [Contact Information](#article-17-contact-information)

---

## Article 1. General Provisions

These Terms of Service (the "Terms") govern your use of the Cleio mobile application (the "App" or "Service") operated by Kidae Lee (the "Operator"). Cleio is an iOS and macOS application that provides voice recording, speech-to-text transcription, speaker diarization, and AI summarization.

By downloading, installing, or using the App, you agree to be bound by these Terms. If you do not agree to these Terms, you must not use the App.

The Operator may update these Terms as necessary. When changes are made, you will be notified at least **30 days** before the effective date via in-app notification or email. Changes that are unfavorable to users will also be notified at least **30 days** before taking effect. Your continued use of the App after the effective date of any changes constitutes your acceptance of the revised Terms.

---

## Article 2. Eligibility

1. You must be at least **14 years of age** to use the App. Users under 14 may not use the App.
2. If you are under 18 years of age, you must have the consent of your parent or legal guardian.
3. Users whose access is restricted under applicable law may not use the App.

---

## Article 3. Account and Authentication

1. The App uses your Apple ID for authentication. No separate account registration is required.
2. You are responsible for maintaining the security of your Apple ID and for all activities that occur under your account.
3. The Operator does not store or manage your Apple ID credentials.

---

## Article 4. Service Description and Plans

### 4.1 Free Plan

The Free plan provides unlimited access to the following features.

- Voice recording (M4A format)
- On-device speech-to-text transcription (powered by WhisperKit)
- On-device speaker diarization (powered by FluidAudio)
- On-device AI summarization (powered by Apple Foundation Models)

All audio processing under the Free plan occurs entirely on your device. No audio or text data is transmitted to external servers.

### 4.2 Pro Plan (Subscription)

The Pro plan includes all Free plan features plus:

- OpenAI GPT-powered AI summarization (text only transmitted; no audio transmitted)
- Apple Private Cloud AI summarization (when directly selected by the user in Settings; text only transmitted; no audio transmitted — see Article 6-3 of the Privacy Policy)
- OpenAI-powered transcription text correction (text only transmitted)
- OpenAI-powered multilingual meeting translation (text segments only transmitted)
- iCloud synchronization (real-time data and iPhone storage optimization)
- Export capabilities (Markdown/PDF)
- MCP Local Integration (macOS only, default OFF) — lets another program you connect directly on this Mac query your recording library and edit its title, folder, domain, and action-item completion (audio files not provided — see Article 6-4 of the Privacy Policy)
- System Audio Capture (macOS only) — captures the audio of another app you directly select on the "New Recording" screen, and additionally records the microphone if you turn on "Include My Voice" (see Article 6-5 of the Privacy Policy)

Under the Pro plan, transcribed text (not audio files) may be transmitted to OpenAI's API, or, when the user directly selects it in Settings, to Apple Private Cloud, for processing. **Audio files are never transmitted to the Operator's servers, to OpenAI, or to Apple** (if a Pro subscriber enables iCloud sync, audio files are stored on the user's own Apple iCloud).

**Usage Limits**

OpenAI-powered AI summarization, text correction, and multilingual translation within the Pro plan are subject to a monthly usage limit. When you reach the usage limit, these features become unavailable until your usage resets at the start of the next billing cycle. Apple Private Cloud AI summarization (when directly selected by the user) is subject to a separate limit that Apple sets on its own; the exact reset cycle is not publicly disclosed. On-device features (speech-to-text transcription, speaker diarization, and on-device AI summarization) are always available regardless of usage.

**Pricing**

- Monthly: KRW 6,600
- Annual: KRW 55,000

Prices may vary by region and currency. The applicable price will be displayed in the App Store at the time of purchase.

---

## Article 5. Subscription and Payment

1. **Payment Processing.** All payments are processed through the Apple App Store. The Operator does not directly collect or store your payment information.

2. **Auto-Renewal.** Pro subscriptions automatically renew at the end of each billing period (monthly or annual) unless canceled at least 24 hours before the end of the current period.

3. **Cancellation.** You may cancel your subscription at any time through your Apple ID account settings (Settings > Apple ID > Subscriptions). Cancellation takes effect at the end of the current billing period. You will retain access to Pro features until the end of the paid period.

4. **Refunds.** Refund requests are handled by Apple in accordance with Apple's refund policies. Your right to withdraw pursuant to applicable consumer protection laws is guaranteed. Please contact Apple Support for refund inquiries.

5. **Downgrade.** Upon expiration of a Pro subscription, your account reverts to the Free plan. Your recordings and data are preserved on your device, but Pro-exclusive features (OpenAI processing, iCloud sync, export) will become unavailable.

---

## Article 6. User Content and Ownership

1. **Ownership.** All recordings, transcriptions, summaries, and other content you create using the App (collectively "User Content") belong to you. The Operator does not claim ownership of your User Content.

2. **Limited License.** You grant the Operator a limited, non-exclusive license to process your User Content solely for the purpose of providing the Service (e.g., transmitting text to AI services for Pro features). This license terminates when you delete your content or stop using the Service.

3. **No Training Use.** The Operator does not use your User Content to train AI models. Text transmitted to OpenAI for Pro features is processed in accordance with OpenAI's API data usage policies, which do not use API inputs for model training. Text transmitted to Apple Private Cloud, when you directly select it in Settings, is processed in accordance with Apple's published policies (see Article 6-3 of the Privacy Policy for details).

4. **User Responsibility.** You are solely responsible for your User Content and for ensuring you have obtained all necessary rights and consents to record, store, and process such content.

---

## Article 7. Recording and Legal Compliance

1. **User Responsibility.** You are solely responsible for complying with all applicable laws and regulations regarding audio recording in your jurisdiction.

2. **Third-Party Voices.** Recordings may include the voices of third parties. It is your responsibility to obtain the consent of any person whose voice is recorded, as required by applicable law. Under the Korean Protection of Communications Secrets Act, recording a conversation between others without being a party to that conversation is prohibited without consent.

3. **System Audio Capture (Pro, macOS Only).** The same responsibilities and principles in paragraphs 1 and 2 above apply equally when you use System Audio Capture to capture the audio of another app, such as a call or video conferencing app. Consent requirements for recording calls and meetings vary by country and region, and in some jurisdictions (for example, two-party consent requirements in certain U.S. states) recording without the consent of all participants may be unlawful. You are responsible for disclosing that a recording is being made to the participants of the call or meeting you capture, and for obtaining any consent required under applicable local law. The App's visual indicator during recording (menu bar and recording screen) may help with this disclosure but does not substitute for any legally required consent.

4. **No Legal Advice.** The App does not provide legal advice. If you are uncertain about the legality of recording in your situation, please consult a legal professional.

---

## Article 8. AI-Generated Content Disclaimer

1. **No Guarantee of Accuracy.** Speech-to-text transcription, speaker diarization, and AI-generated summaries are produced by automated systems and may contain errors or inaccuracies. The Operator does not guarantee the accuracy, completeness, or reliability of any AI-generated output.

2. **Not a Substitute for Professional Records.** AI-generated content is provided for convenience and informational purposes only. It must not be used as a substitute for professional transcripts, legal records, medical documentation, or any other use requiring verified accuracy.

3. **User Verification.** You are responsible for reviewing and verifying all AI-generated content before relying on it for any important purpose.

---

## Article 9. Prohibited Conduct

You agree not to:

1. Record the voices of others without obtaining the consent required by applicable law;
2. Use the App for any illegal, fraudulent, or harmful purpose;
3. Attempt to reverse-engineer, decompile, disassemble, or otherwise derive the source code of the App;
4. Circumvent, disable, or interfere with any security or access-control features of the App;
5. Use the App to harass, threaten, defame, or violate the rights of others;
6. Use the App in any manner that could damage, overburden, or impair the Service;
7. Distribute, sublicense, or resell access to the App or its features to any third party;
8. Use automated means to access or interact with the App, except as explicitly permitted.
9. Share your MCP Local Integration access token with others, or allow anyone other than yourself to use it to access your library.

Violation of these Terms may result in the suspension or termination of your access to the Service.

---

## Article 10. Data Processing and Privacy

1. **On-Device Processing (Free Plan).** Under the Free plan, all audio processing, transcription, real-time speaker diarization, and summarization occur entirely on your device. No audio or text data is transmitted to external servers.

2. **Cloud Processing (Pro Plan).** Under the Pro plan, transcribed text may be transmitted to OpenAI's API for enhanced summarization, text correction, and multilingual translation. In addition, when you directly select it in Settings, AI summarization may be processed via Apple Private Cloud (built on Apple Inc.'s Private Cloud Compute technology) — this path is transmitted directly from your device to Apple's servers without passing through the Operator's backend, and is subject to a separate usage limit set by Apple. Audio files are never transmitted to the Operator's servers, to OpenAI, or to Apple. See Articles 6-2 and 6-3 of the Privacy Policy for details.

3. **Two-Way Reminders Synchronization (opt-in).** Action items may be synchronized two-way with the iOS Reminders app (EventKit). This feature requires Reminders permission; core functionality (recording, transcription, summarization) continues to work without this permission.

4. **Calendar Event Automatic Matching (opt-in).** Recordings may be automatically matched with events in the iOS Calendar app (EventKit). This feature requires Calendar permission. Event data is processed on-device only and is never transmitted to the Operator's servers (for Pro subscribers, the matching metadata syncs only to the user's own Apple iCloud). Core functionality (recording, transcription, summarization) continues to work without this permission.

5. **Analytics and Crash Reporting.** The App uses Firebase Analytics and Crashlytics to collect anonymized usage data and crash reports for the purpose of improving the Service. This data does not include recordings or transcription content. The App does not currently provide an in-app toggle to disable Firebase Analytics; to opt out, please contact kdwara@icloud.com.

6. **Backend Infrastructure.** The Operator operates Google Firebase Cloud Functions (United States region, project `cleio-prod`) for backend functions including OpenAI API proxy, subscription verification, and usage management. This infrastructure is invoked only when Pro cloud features are requested. Apple Private Cloud AI summarization does not pass through this infrastructure; it is transmitted directly from your device to Apple's servers.

7. **iCloud Sync (Pro Plan).** Pro subscribers may use iCloud synchronization and iPhone storage optimization. Data is stored on Apple's iCloud infrastructure, governed by Apple's privacy policies.

8. **MCP Local Integration (Pro, User's Choice, macOS only).** You may allow another program you connect directly on this Mac to query your recording library (transcripts, summaries, action items, folder list, etc.; audio files excluded) and edit a limited set of items. The default is OFF, and access is protected by a server that responds only to this Mac and an access token known only to you. How a program you connect subsequently handles that data is outside the Operator's control and is governed by that program's own terms and privacy policy. See Article 6-4 of the Privacy Policy for details.

9. **System Audio Capture (Pro, User's Choice, macOS Only).** You may capture the audio output of another app you directly select on the "New Recording" screen, and the microphone is additionally recorded if you turn on "Include My Voice." Captured audio is processed the same way as microphone recordings — by default it is stored and processed only on this Mac, and is stored and synced to your own Apple iCloud Drive only if you, as a Pro subscriber, have enabled iCloud sync. A persistent visual indicator is shown in the menu bar and the recording screen while capture is in progress. The app you capture may include the voices of third parties, such as call or meeting participants, and complying with applicable law in that regard is your responsibility under Article 7. See Article 6-5 of the Privacy Policy for details.

10. **Privacy Policy.** For detailed information about our data practices, please refer to the Privacy Policy available within the App.

---

## Article 11. Intellectual Property

1. **Operator's Rights.** The App, including its design, code, features, and trademarks, is the intellectual property of the Operator and is protected by applicable law. These Terms do not grant you any rights to the Operator's intellectual property except the limited right to use the App in accordance with these Terms.

2. **Open-Source Components.** The App incorporates open-source software components, each subject to their respective licenses. A list of such components and their licenses is available in the App settings.

---

## Article 12. Service Modification and Termination

1. **Service Modification.** The Operator may modify, update, or discontinue any part of the Service. For material changes unfavorable to users, the prior notice period set out in Article 1 will be observed.

2. **Termination by Operator.** The Operator may suspend or terminate your access to the Service if you violate these Terms or if required to do so by law.

3. **Termination by You.** You may stop using the App at any time by deleting it from your device. If you have an active subscription, you must also cancel it separately through your Apple ID settings to avoid further charges.

4. **Effect of Termination.** Upon termination, your right to use the App ceases. Data stored on your device remains accessible to you.

---

## Article 13. Disclaimer of Warranties

To the extent permitted by applicable law, the App is provided "as is" without warranties of any kind, whether express or implied.

The Operator does not warrant that:

1. The App will be uninterrupted, timely, secure, or error-free;
2. The results obtained from use of the App (including transcriptions, speaker diarization, and AI summaries) will be accurate or reliable;
3. Any defects in the App will be corrected.

---

## Article 14. Limitation of Liability

To the extent permitted by applicable law, the Operator shall not be liable for any indirect, incidental, or consequential damages arising out of or in connection with:

1. Your use of or inability to use the App;
2. Any inaccuracy in transcription, speaker diarization, or AI-generated summaries;
3. Any unauthorized access to or alteration of your data;
4. Any third-party services accessed through the App;
5. The way a program you have directly connected via MCP Local Integration uses, stores, or retransmits data obtained through that feature, and any resulting consequences;
6. Any failure by you to comply with applicable law in recording or processing the voices of third parties through System Audio Capture (macOS, Pro);
7. Any other matter relating to the App.

The Operator's liability is limited to the extent permitted by applicable law. Nothing in this article limits your rights under mandatory consumer protection laws.

---

## Article 15. Governing Law and Dispute Resolution

1. These Terms shall be governed by the laws of the Republic of Korea.

2. Any dispute arising out of or in connection with these Terms shall first be attempted to be resolved through good-faith negotiation between the Operator and the user.

3. If negotiation fails, the Seoul Central District Court shall have jurisdiction. If applicable law designates a different court of jurisdiction, that provision shall prevail.

---

## Article 16. General Provisions

1. **Entire Agreement.** These Terms, together with the Privacy Policy, constitute the entire agreement between you and the Operator regarding the use of the App.

2. **Severability.** If any provision of these Terms is found to be invalid or unenforceable, the remaining provisions shall remain in full force and effect.

3. **Waiver.** The Operator's failure to enforce any right or provision of these Terms shall not constitute a waiver of that right or provision.

4. **Assignment.** The Operator may assign its rights and obligations under these Terms without your consent. You may not assign your rights or obligations without the Operator's prior written consent.

5. **Force Majeure.** The Operator shall not be liable for any failure or delay in performance due to causes beyond its reasonable control, including natural disasters, acts of government, or disruptions to third-party services.

---

## Article 17. Contact Information

For questions or concerns about these Terms, please contact:

- **Email**: kdwara@icloud.com
