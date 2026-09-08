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
> **Version**: 1.5
> **Effective Date**: 2026-09-09
> **Last Updated**: 2026-09-08
>
> This document is a translation provided for convenience only. The Korean-language version is the authoritative original. In case of any conflict between this translation and the Korean original, the Korean original shall prevail.
>
> **Correction on 2026-08-06**: Reminders synchronization now edits and deletes items in addition to adding them, so related descriptions in Articles 2, 4, 8, and 11 have been corrected to match the actual behavior (deletion paths performed by Cleio were added, and a reference to a non-existent in-app toggle was removed). This does not change your rights or the terms of service, so the effective date remains unchanged.
>
> **Second correction on 2026-08-06**: The description of where audio files are transmitted has been corrected to match the actual behavior. Article 2 now states that audio files are stored and synced to the user's own Apple iCloud when a Pro subscriber enables iCloud sync, and the broad negation "not transmitted to third parties" has been narrowed to the parties actually negated — "the Operator's servers or OpenAI" (the same applies to Calendar event data). No processing practice has changed; only its description has been made accurate, so the effective date remains unchanged.
>
> **Correction on 2026-08-13**: Following a change to the app's UI labeling (v1.4), related terminology in this Policy has been aligned with the app's on-screen "usage" label (Articles 6, 7, and 13). The actual scope of outsourced processing and security measures is unchanged, so the effective date remains unchanged.
>
> **Correction on 2026-09-03**: The cloud AI features (text correction, AI summary, multilingual translation) no longer present a separate prior-consent screen (bottom sheet), so Articles 2, 6-2, and 7 have been corrected to describe the actual behavior (a Settings toggle or direct invocation of the feature). Reminders synchronization is now also offered in the Mac app in the same way, so "iOS Reminders" has been changed to "the Reminders app". No processing practice has changed; only its description has been made accurate, so the effective date remains unchanged.
>
> **Key changes in v1.2**: Added multilingual meeting translation (Pro), two-way Reminders (EventKit) sync, disclosure of Calendar (EventKit) automatic event matching, iPhone storage optimization (Pro+iCloud), and disclosure of Firebase Cloud Functions backend infrastructure.
>
> **v1.5 (2026-09-09)**: Introduced System Audio Capture (Pro, macOS only) — an opt-in feature that captures another app's audio output directly, as the app's own output signal rather than a re-recording through the microphone, when the user selects that app on the "New Recording" screen; the microphone can additionally be recorded at the same time if the user turns on "Include My Voice" (Articles 2, 3, 6, **6-5 (new)**, 8, 11, and 13 amended). The app the user chooses to capture may include the voices of third parties, such as call or meeting participants, and Article 6-5 states that compliance with applicable law when recording those third parties is the user's responsibility. Captured audio is processed through the same path as microphone recordings — by default it is stored and processed only on this Mac, and is stored and synced to the user's own Apple iCloud Drive only if a Pro subscriber has enabled iCloud sync. A persistent visual indicator is shown in the menu bar and the recording window while capture is in progress. This feature is included in the first release of the macOS version of Cleio (v1.5.0) and has not been made available to any user before that release. Because this amendment adds a new capture path and processing purpose, it is reflected as a version increment (1.4 → 1.5) rather than a mere correction, with the effective date updated to 2026-09-09.
>
> **v1.4 (2026-09-04)**: Introduced MCP Local Integration (Pro, macOS only) — an opt-in feature that lets another program the user connects directly on this Mac query the user's own recording library and modify a limited set of items in it (a recording's title, its folder, its domain, and an action item's completion state); its default state is inactive (OFF) (Articles 2, 3, 5, 6, **6-4 (new)**, 8, and 13 amended). Audio files and their storage paths are not made available through this channel. Article 6-4 states that the recipient here is not the Operator or a processor selected by the Operator, but a program the user has chosen and connected themselves, and that the program's subsequent processing is outside the Operator's control. As of this amendment, this feature has not been made available to any user (it has not yet shipped to the App Store) and will operate only once the app version containing it is actually released. Because this amendment adds a new processing purpose and a new channel through which data is made available, it is reflected as a version increment (1.3 → 1.4) rather than a mere correction.
>
> **v1.3 (2026-09-04)**: Introduced Apple Private Cloud AI summarization (built on Apple Inc.'s Private Cloud Compute technology) — an opt-in feature Pro subscribers select directly in Settings; the default remains GPT (Articles 2, 3, 4, 6, **6-3 (new)**, 7, 8, and 13 amended). As of this amendment, this feature has not been made available to any user (it has not yet shipped to the App Store) and will operate only once the app version containing it is actually released. Because this amendment adds a new processing purpose, an expanded scope of outsourced processing, and a new category of international data transfer, it is reflected as a version increment (1.2 → 1.3) rather than a mere correction, with the effective date updated to 2026-09-04.
>
> **Correction on 2026-09-08**: The effective date has been adjusted from 2026-09-04 to **2026-09-09** to match the actual publication date. The amendments above had not been published and therefore never took effect as of 2026-09-04; their substance is unchanged.

---

## Table of Contents

1. [Overview](#article-1-overview)
2. [Data We Collect](#article-2-data-we-collect)
3. [Purposes of Processing](#article-3-purposes-of-processing)
4. [Retention Periods](#article-4-retention-periods)
5. [Third-Party Disclosure](#article-5-third-party-disclosure)
6. [Outsourced Processing](#article-6-outsourced-processing)
6-2. [Prior Consent for Cloud AI Features](#article-6-2-prior-consent-for-cloud-ai-features)
6-3. [Apple Private Cloud Summarization](#article-6-3-apple-private-cloud-summarization)
6-4. [MCP Local Integration](#article-6-4-mcp-local-integration)
6-5. [System Audio Capture](#article-6-5-system-audio-capture)
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

Cleio (the "App") is an iOS and macOS application operated by Kidae Lee (the "Operator") that provides voice recording, real-time speech-to-text transcription, speaker diarization, and AI summarization. This Privacy Policy explains how the Operator collects, uses, stores, and protects your personal information when you use the App.

By using the App, you acknowledge that you have read and understood this Privacy Policy. If you do not agree with its terms, please do not use the App.

---

## Article 2. Data We Collect

### 2.1 Data You Create Directly

| Data | Purpose | Storage | External Transfer | Retention |
|------|---------|---------|-------------------|-----------|
| Audio recordings (M4A) | Core service — voice recording | Local device + iCloud (Pro) | None | Until deleted by user |
| System audio capture (macOS, Pro) | Captures another app's audio, chosen directly by the user on the "New Recording" screen (Article 6-5) | Local device + iCloud Drive (Pro, if iCloud sync is on) | None | Until deleted by user |
| Transcription text | Speech-to-text conversion results | Local (SwiftData) + iCloud (Pro) | OpenAI API (Pro text correction / summarization / translation; text only); a program the user has connected, if MCP Local Integration is on (Article 6-4) | Until deleted by user |
| AI summary text | Meeting/conversation summaries | Local (SwiftData) + iCloud (Pro) | OpenAI API or Apple Private Cloud (Pro summarization, depending on the engine the user selects in Settings; text only); a program the user has connected, if MCP Local Integration is on (Article 6-4) | Until deleted by user |
| Action items (to-dos) | To-do items extracted from summaries | Local (SwiftData) + iCloud (Pro) + Reminders app (EventKit, when the user syncs) | None (except a program the user has connected, if MCP Local Integration is on — Pro, default OFF, Article 6-4) | Until deleted by user |
| Speaker diarization results | Per-utterance speaker identification | Local (SwiftData) + iCloud (Pro) | None (except a program the user has connected, if MCP Local Integration is on — Pro, default OFF, Article 6-4) | Until deleted by user |
| Calendar event matching data (event title, identifier, date/time) | Automatic matching of recordings with Calendar events | Local (SwiftData) + iCloud (Pro) | None (except that, where an automatically matched event title is used as a recording's displayed title, that title may be exposed to a connected program for users who have turned MCP Local Integration on — Article 6-4) | Until deleted by user |
| Translation text (Pro) | Display original/translated text for multilingual meetings | Local (SwiftData) + iCloud (Pro) | OpenAI API (when user requests translation; text only) | Until deleted by user |
| App settings | User preferences | UserDefaults + iCloud KVS (Pro) | None | Until app deletion |

**Audio files are never transmitted to the Operator's servers, to OpenAI, or to Apple.** If a Pro subscriber enables iCloud sync, audio files are stored and synced to the user's own Apple iCloud. Only text is sent to OpenAI or Apple Private Cloud, and **it is transmitted only when the user directly enables, selects, or invokes the relevant feature in Settings** (see **Article 6-2** for text correction/translation/GPT summarization, and **Article 6-3** for Apple Private Cloud summarization).

**Audio recorded via System Audio Capture (Pro, macOS only) may include the voices of third parties**, such as call or meeting participants. For details on where this audio is processed and the user's responsibilities, see **Article 6-5**.

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
2. **Pro Subscription Features** — OpenAI-powered text correction, GPT summarization, and multilingual meeting translation; Apple Private Cloud AI summarization (when selected by the user in Settings); iCloud synchronization (real-time data and iPhone storage optimization); export capabilities (Markdown/PDF).
3. **Two-Way Reminders Synchronization (opt-in)** — Two-way sync of action items with the Reminders app (EventKit).
4. **Calendar Event Automatic Matching (opt-in)** — Automatically linking recordings with Calendar (EventKit) events for easier management.
5. **Service Improvement** — Analysis of anonymized usage patterns to enhance features and user experience.
6. **Stability and Performance** — Collection of crash reports and performance metrics to maintain and improve app reliability.
7. **Payment Processing** — Managing subscription status through Apple's StoreKit.
8. **User Preferences** — Storing and synchronizing app settings across devices (Pro).
9. **Providing MCP Local Integration (Pro, User's Choice)** — Allowing a program the user has connected directly on this Mac to query the recording library and edit titles, folders, domains, and action item completion.
10. **Providing System Audio Capture (Pro, macOS only, User's Choice)** — Capturing the audio of another app the user selects directly on the "New Recording" screen, to support recording meetings and calls.

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
| Apple Private Cloud transmitted data (AI summarization, when selected by the user in Settings) | Per Apple's published policy — **not independently verified by the Operator** (see Article 6-3) | Not retained after processing, per Apple's published policy |
| Reminders (EventKit) data | Per the Reminders app's retention policy | Deleted when the user removes the item in the Reminders app, or when the user excludes it during a sync or deletes the action item in Cleio |

If retention is required by law, the relevant data is stored separately and destroyed after the statutory retention period expires.

---

## Article 5. Third-Party Disclosure

As a general rule, the Operator does not provide personal information to third parties. Exceptions include:

- When the user has given prior consent;
- When required by law or upon a lawful request from a law enforcement authority.

Where the user has turned on MCP Local Integration (Article 6-4) themselves, allowing a program they have connected to read and edit their data falls under "the user has given prior consent" above.

**The Operator does not sell, rent, or trade personal information to any third party.**

---

## Article 6. Outsourced Processing

The Operator entrusts certain data processing to the following service providers for the purpose of delivering the Service. These providers process data solely on the Operator's behalf and under the Operator's instructions.

| Processor | Entrusted Task | Retention | Contact |
|-----------|---------------|-----------|---------|
| OpenAI, Inc. (United States) | Pro: transcription text correction, AI summarization, multilingual translation (text only; no audio) | Deleted within 30 days; not used for model training | privacy@openai.com |
| Google LLC (United States) | Firebase analytics, crash reporting, performance monitoring, and Cloud Functions infrastructure operation (OpenAI proxy, subscription verification, usage management) | Per Google's retention policy | https://firebase.google.com/support/privacy |
| Apple Inc. (United States) | StoreKit payment processing, iCloud storage (Pro), Reminders (EventKit) data storage, Apple Private Cloud AI summarization (Pro, when directly selected by the user in Settings) | Per Apple's retention policy | https://www.apple.com/privacy |

The Operator maintains agreements (or applicable standard terms, the Apple App Store agreement, and the OpenAI Data Processing Addendum) with processors governing data protection obligations and oversees their compliance.

Apple Private Cloud AI summarization is transmitted directly from the user's device to Apple's servers, without passing through the Operator's servers. See **Article 6-3** for details.

MCP Local Integration is not an entrustment to a processor selected by the Operator; it is the user's own act of granting access to a program the user has chosen and connected. See **Article 6-4** for details.

Audio captured through System Audio Capture (Pro, macOS only) does not involve any new processor; it is processed through the same path as microphone recordings. See **Article 6-5** for details.

---

## Article 6-2. Prior Consent for Cloud AI Features

The Operator provides the following Pro features that utilize OpenAI, Inc.'s (United States) GPT services.

| Feature | Transmitted Data | Recipient | Default State |
|---------|-----------------|-----------|---------------|
| Text correction (Pro) | Transcription text (STT), language settings, user term dictionary | OpenAI, Inc. (United States) | **Inactive** (default OFF) |
| AI summary (Pro) | Transcription text (STT), recording title, domain tag, summary length setting | OpenAI, Inc. (United States) | **Only when explicitly invoked by the user** |
| Multilingual meeting translation (Pro) | Transcript segment (source text), source language, target language | OpenAI, Inc. (United States) | **Automatically runs if the auto-translate toggle is on** (default OFF), **or runs manually when the user directly requests a translation** |

**Not transmitted**: audio files, account identifiers (email, IDFA, etc.), device identifiers.

### How Consent Works

Data is transmitted to OpenAI only when the user **directly enables or invokes** one of the features below. The App does not display a dedicated consent pop-up; the action itself constitutes consent for that feature. "Prior consent" in this Article means the action below, taken before any data is transmitted.

- **Text correction**: Automatic text correction runs only after the user turns on "Auto Text Correction" in Settings > Recording & Analysis (default OFF).
- **AI summary**: Data is transmitted only when the user directly selects and runs "Pro Summary" (or "Re-summarize › Pro") on the summary screen. It never runs automatically.
- **Multilingual meeting translation**: Data is transmitted either automatically, if the user has turned on "Auto-Translate" in Settings (default OFF), or manually, when the user taps "Translate" on screen.

Before purchasing a Pro subscription, the subscription screen displays a notice describing the cloud AI features, the scope of data transmitted, and a link to this Privacy Policy. Users can review this notice and this Article before deciding whether to turn on the toggles or use the buttons described above.

Transmitted text is deleted within 30 days of transmission under OpenAI's API policy and is not used for model training (see Articles 4 and 6).

No data is transmitted to OpenAI until the user takes one of the actions above. Whether each feature (text correction, AI summary, multilingual translation) is enabled is managed **independently per feature**, and that state is stored only on the device (not synchronized to iCloud).

### Withdrawal of Consent

The user may withdraw consent in the following ways.

- **Text correction**: Toggle off "AI Text Correction" in Settings > AI Features.
- **AI summary**: Select **on-device summary** on the summary screen instead of Pro (cloud) summary.
- **Multilingual meeting translation**: Turn off "Auto-Translate" in Settings to stop automatic runs, and simply do not request a translation to prevent any data from being transmitted. Cached translations are deleted together with the source transcription when the transcription is deleted.
- **Full withdrawal**: Cancel the Pro subscription — once canceled, all cloud AI features are deactivated, and no further data is transmitted to OpenAI.

### Cloud-Free Alternatives

The App provides the following **on-device processing** as the default, allowing core functionality to be used without consenting to the cloud AI features above.

- Speech-to-text (STT): WhisperKit (on-device processing)
- Speaker diarization: FluidAudio (on-device processing for both real-time and post-processing)
- AI summary: Apple Foundation Models (on-device processing, iOS 26.1+)
- Translation: Pro-exclusive feature; no OpenAI transmission if translation is not used

---

## Article 6-3. Apple Private Cloud Summarization

The Operator provides the following Pro feature built on Apple Inc.'s (United States) Private Cloud Compute technology. In the App, this feature is displayed as **"Apple Private Cloud."** Under this Policy, and consistent with Article 6, Apple is treated as a processor for this activity.

| Feature | Transmitted Data | Recipient | Default State |
|---------|-----------------|-----------|---------------|
| AI summary (Pro) | Transcription text (STT, including speaker labels), the recording title the user has directly given it (auto-generated titles are excluded), domain tag, summary length/tone settings, language setting, recording date/time | Apple Inc. (United States) — Apple Private Cloud Compute | **Inactive** — the default remains GPT; this option is used only when the user directly selects it in Settings |

**The data the Operator transmits does not include the following**: audio files, account identifiers (email, IDFA, etc.), device identifiers. The Operator has not independently verified whether the actual transport layer of the request to Apple carries any other information.

**Availability**: This feature is available only to Pro subscribers on iOS 27 / macOS 27 or later whose device meets Apple's eligibility requirements. On devices that do not meet these requirements, this option is not displayed at all.

### How Consent Works

In Settings > AI Model > "Summary AI," the user directly chooses one of the following three options.

- **Automatic**: Tries Apple Private Cloud first, and falls back to GPT — **silently, without asking or notifying you in advance** — when it is unavailable (e.g., device/system ineligibility, usage limit reached, or the recording is long enough to require multiple calls). Because you chose "Automatic" without naming a specific engine, this GPT use (and any resulting usage deduction) is treated as within the scope of that choice. You can still confirm after the fact which engine actually produced a given summary — the summary screen shows a notice only when it was produced via Apple Private Cloud; the absence of that notice means it was produced via GPT.
- **Apple Private Cloud**: Summarizes using Apple only. If unavailable, the App does not silently fall back to GPT; instead it explains the reason and asks the user to choose again.
- **GPT**: Summarizes using OpenAI only, as before (see Article 6-2). This is the **default for all users, including existing users**.

"Prior consent" in this Article means the user's direct act of selecting "Apple Private Cloud" (or "Automatic," which may fall back to it) on the screen described above. No separate consent pop-up is displayed. No data is transmitted to Apple until the user makes this selection.

### Relationship to Domain Detection

The feature that automatically detects a summary's domain (see Article 6-2) works by transmitting the full transcript to OpenAI. **This automatic domain detection does not run for summaries processed via Apple Private Cloud** — if a domain has already been saved, that value is used; otherwise, Apple Private Cloud's own model follows its built-in instructions to infer the domain. Accordingly, the transcript of a summary processed via Apple Private Cloud is never transmitted to OpenAI.

### Whether the Backend Is Involved

Summarization via Apple Private Cloud is transmitted directly from the user's device to Apple's servers, without passing through the Operator's Google Firebase Cloud Functions backend (see Article 13). As a result, the Operator retains no call logs for this processing, and it does not deduct from Pro usage (credits).

### Usage Limits

Apple imposes its own usage limit on this feature. The information Apple provides does not include an exact remaining count or reset cycle — only a three-tier status ("plenty remaining," "approaching the limit," "limit reached") and, where available, the next reset time. Accordingly, this Policy and the App do not characterize the usage cycle as "daily" or "monthly." This limit is **separate** from the Pro usage (credits) managed by the Operator (see Articles 6-2 and 13).

### Retention — Based on Apple's Published Statements

Apple has publicly stated that it does not retain the content of requests processed by Private Cloud Compute. **This statement reflects Apple's own published policy and has not been independently verified by the Operator.** Please refer to Apple's publicly available materials for the most current information on retention and processing.

### Withdrawal of Consent

- Switching back to "GPT" or "Automatic" in Settings > AI Model > "Summary AI" stops future summaries from being sent to Apple Private Cloud.
- Canceling the Pro subscription deactivates all cloud summarization features, including this one.

### Cloud-Free Alternative

Core functionality remains available via on-device summarization (Apple Foundation Models; see Article 6-2) without consenting to this feature.

---

## Article 6-4. MCP Local Integration (Pro, User's Choice)

The Operator provides the following Pro feature ("MCP Local Integration") that lets another program the user runs directly on this Mac (the "Connected Program") query the user's own Cleio library and modify a limited set of items in it. This feature is available **only in the macOS version of Cleio**, and its default state is **inactive (OFF)**.

| | |
|---|---|
| Data made available | Recording list metadata (title, recording date/time, duration, status, folder, speaker count, domain), full transcript (per-segment speaker labels and start/end times), summary text (the version currently shown to the user), action item (to-do) list, folder list, linked calendar event details (event title, date/time, calendar name, and **attendee names**) |
| Not made available | Audio files and their storage paths, account identifiers (e.g., email), device identifiers, **calendar attendees' email addresses and RSVP status** |
| Recipient | Not the Operator or a processor selected by the Operator, but **a separate program running on this Mac that the user has chosen to connect themselves** |
| Default state | **Inactive** (default OFF) — the user must turn it on directly in Settings |

**Note on calendar attendees**: When a recording is linked to a calendar event, retrieving that recording's detail also provides the event's **attendee names**. Attendee information is not cached on the device (the calendar cache scope in Article 2 remains title, identifier, and date/time) and is read directly from the device's calendar at the time of the request. It is not provided if calendar permission is absent or the event has been deleted. **Attendees' email addresses and RSVP status are not provided** — a name is what is needed to answer "who attended," whereas an email address is a persistent identifier for a specific person. Attendees are not included in list results.

**Note on titles**: The "title" above includes not only a title the user has directly given a recording, but, when none has been given, a calendar event's title shown via automatic matching, or the system's date-based default title — whatever title is currently displayed on screen is what goes out.

**How this differs from Articles 6-2 and 6-3**: Those Articles describe processing relationships the Operator has established with named vendors (OpenAI, Apple). This feature is different — the Operator does not know, and does not choose, which program connects. Selecting a Connected Program and authorizing it by entering the access token is entirely the user's own act.

### How It Works

Turning on "MCP Local Integration" in Settings opens a server that responds only to this Mac itself (the loopback address, 127.0.0.1). No other device on the same network can reach it. Connecting requires an access token this app generates and stores in the device's Keychain; the user must enter this token into the Connected Program themselves to complete the connection. The server runs only while the app is running and stops when the app quits.

The Connected Program may request only four kinds of edits: renaming a recording, moving it to a folder, setting its domain, and toggling an action item's completion state. It cannot request any action that consumes Pro usage (credits), such as generating an AI summary, translating, or correcting text.

**Reach into the Reminders app**: If the Connected Program toggles the completion state of an action item the user has already exported to the Reminders app, that change is also applied to the corresponding item in the Reminders app (the same path as Reminders synchronization described in Article 2). This is the only case in which an edit made through this channel reaches outside the Cleio app, and it does not apply to items that have not been exported to Reminders.

### How Consent Works

"Prior consent" in this Article means the user's own act of turning on "MCP Local Integration" in Settings. No data is made available through this channel until the toggle is turned on.

### Limits on the Operator's Responsibility for Downstream Handling

The recipient on this channel is not the Operator, but **a separate program the user has chosen and connected themselves**. The Operator does not know, and has no control over, what that program is or how it subsequently stores, uses, or retransmits the data it receives — including if that program itself forwards the data to another AI service. Any processing by that program is governed by its own terms and privacy policy, not this Policy. Choosing a Connected Program and reviewing how it handles data is the user's own responsibility.

### Withdrawal of Consent

- Turning off "MCP Local Integration" in Settings immediately stops the server; no further data is made available through this channel.
- Quitting the app also stops the server — this feature runs only while the app is running.
- Regenerating the access token in Settings immediately disconnects every previously connected program.
- Canceling the Pro subscription also deactivates this feature.

### Alternative Without This Feature

This feature is off by default. Leaving it off does not affect any core functionality — recording, transcription, speaker diarization, AI summarization — or any other Pro feature.

### Security Measures

- The server responds only to this Mac itself (loopback address, 127.0.0.1); no other device on the same network can reach it.
- Requests a browser could send on the user's behalf are blocked (Origin check).
- Access requires a token stored in the device's Keychain; this token is not synchronized via iCloud.

---

## Article 6-5. System Audio Capture (Pro, macOS Only)

On the macOS version of Cleio, the Operator provides the following Pro feature ("System Audio Capture"), which captures the audio output of another app the user directly selects on the "New Recording" screen — as that app's own output signal, not as a re-recording through the microphone. This feature is provided **only on the macOS version of Cleio**; the free plan and the iOS version offer microphone recording only.

| Item | Description |
|------|-------------|
| What is captured | The audio output of a single app the user directly selects on the "New Recording" screen before starting a recording, captured at the process level using macOS's Core Audio process tap technology |
| Simultaneous microphone capture | The microphone is additionally recorded only if the user turns on "Include My Voice" |
| Processing/storage path | Captured audio is stored and processed through the **same path** as microphone recordings — everything downstream (transcription, speaker diarization, summarization, cloud AI processing) follows Articles 2, 4, 6-2, and 6-3 exactly as for any other recording |
| Default state | Not a persistent background capture — the user must directly select the app to capture each time a recording is started |

### Third-party voices (e.g., call or meeting participants) may be included

The app the user chooses to capture may be a call or video conferencing app whose output includes **the voices of other participants**. In that case, the captured audio may include **the voices of third parties** who took part in the call or meeting, in addition to the user's own voice. Complying with applicable law when recording such third parties — including disclosing that a recording is being made and obtaining any consent that law requires — is **the user's responsibility**; see Article 7 of the Terms of Service for details. The Operator has no knowledge of what the user chooses to capture and does not separately obtain consent from any third party whose voice is captured.

### Where data is stored and processed

Captured audio files, and the transcripts, speaker diarization results, and summaries generated from them, are by default stored and processed **only on this Mac**. **They are never transmitted to the Operator's servers, to OpenAI, or to Apple**, and audio files are stored and synced to the user's own Apple iCloud Drive only if a Pro subscriber has enabled iCloud sync (see Article 2). If the user directly enables, selects, or invokes text correction, GPT summarization, translation, or Apple Private Cloud summarization in Settings, the resulting text — and only that text — may be transmitted to OpenAI or Apple under Articles 6-2 and 6-3.

### Indicator while recording

While System Audio Capture is in progress, a persistent visual indicator is shown in the menu bar icon and in the recording screen (window) to show that capture is under way. Because capture can continue even when sound cannot be heard (e.g., while muted), this indicator exists so the user can always confirm, visually, whether capture is active.

### Permission required

This feature requires macOS's **"Screen & System Audio Recording"** permission, separate from microphone permission (see Article 11). If this permission is not granted, System Audio Capture does not operate; core functionality, including microphone recording, continues to work normally in that case.

### How Consent Works

"Prior consent" in this Article means the user's acts of (1) granting the "Screen & System Audio Recording" permission macOS requests the first time it is needed, and (2) directly selecting the app to capture on the "New Recording" screen, every time. This feature does not operate unless the user selects an app to capture.

### Withdrawal of Consent

- Cleio's permission can be withdrawn at any time from macOS System Settings > Privacy & Security > "Screen & System Audio Recording." After withdrawal, only microphone recording remains available.
- Canceling the Pro subscription also deactivates this feature.

### Alternative Without This Feature

Without using this feature, you can still use the App's core functionality — microphone recording, transcription, speaker diarization, and on-device AI summarization — on the free plan in the same way.

---

## Article 7. International Data Transfers

Your personal information may be transferred to and processed in countries outside your country of residence as follows.

| Recipient | Country | Data Transferred | Purpose | Legal Basis |
|-----------|---------|-----------------|---------|-------------|
| OpenAI, Inc. | United States | Transcription text, summary input text, translation input text (only when the user enables or directly invokes the relevant Pro feature in Settings) | Text correction, GPT summarization, multilingual translation | Transmitted only when the user directly enables or invokes the feature (Article 6-2) |
| Google LLC | United States | (a) Anonymized app usage events, crash logs, performance metrics; (b) Cloud Functions invocation logs (no personally identifying content) | Analytics, stability, and performance monitoring; backend infrastructure operation (OpenAI proxy, subscription verification, usage management) | Performance of service contract |
| Apple Inc. | United States | Payment information, iCloud-synced data (Pro), Reminders (EventKit) data | Payment processing, cloud storage, two-way Reminders synchronization | Performance of service contract |
| Apple Inc. | United States | Transcription text, summary input text (including any recording title the user has directly given it), domain tag, and summary length/tone/language settings (only when the user directly selects Apple Private Cloud summarization in Settings) | Apple Private Cloud AI summarization | Transmitted only because the user directly selected the feature (Article 6-3) |

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
- You can revoke permissions such as microphone, Calendar, Reminders, and (on macOS) Screen & System Audio Recording at any time through your device settings.
- You may submit a request by email to kdwara@icloud.com. The Operator will process the request without undue delay and no later than **10 days** from receipt.
- Withdrawal of consent for cloud AI features (text correction, AI summary, multilingual translation) is described in the **Withdrawal of Consent** section of **Article 6-2**; withdrawal of consent for Apple Private Cloud summarization is described in the **Withdrawal of Consent** section of **Article 6-3**.
- Withdrawal of consent for MCP Local Integration is described in the **Withdrawal of Consent** section of **Article 6-4**.
- Withdrawal of consent for System Audio Capture is described in the **Withdrawal of Consent** section of **Article 6-5**.
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
| Reminders (EventKit) | Two-way action item synchronization between the App and the Reminders app | Optional — if declined, transcription/summarization features continue to work; only the Reminders sync feature is disabled |
| Screen & System Audio Recording (macOS, TCC) | Capturing the audio of another app the user selects (Pro, System Audio Capture) | Optional — if declined, core functionality including microphone recording continues to work normally; only System Audio Capture is disabled |

- Microphone permission is required for the App's core recording functionality. The App cannot function without microphone access.
- Speech-to-text (STT) is processed entirely on-device and does not require a separate speech recognition permission.
- Calendar permission is used only for matching recordings with Calendar events. Event data is read on-device only and is never transmitted to the Operator's servers (for Pro subscribers, the matching metadata syncs only to the user's own Apple iCloud). Core functionality of the App continues to work without it.
- The Reminders permission is used only to sync action items with the Reminders app (adding, editing, and deleting). Core functionality of the App continues to work without it.
- The Screen & System Audio Recording permission is needed only to use System Audio Capture (Pro) on macOS. Core functionality of the App, including microphone recording, continues to work without it. See Article 6-5 for details.
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

- **On-Device Processing Prioritized**: Core features (speech-to-text transcription, real-time speaker diarization, on-device AI summarization) operate entirely on the user's device. The on-device AI summarization uses Apple's Foundation Models framework and does not communicate with any external servers, including Apple's servers. Separately, if a Pro subscriber directly selects **Apple Private Cloud** as the summarization engine in Settings, transcription text is transmitted to Apple's servers for processing (see Article 6-3) — this occurs only by the user's explicit choice and is an exception to the on-device processing principle above. Unless the user uses any Pro cloud feature (text correction, GPT summary, translation, or Apple Private Cloud summarization), recordings, transcripts, and summary content are not transmitted to the Operator's servers, to OpenAI, or to Apple. However, Firebase data collected for app usage statistics and error diagnostics is transmitted regardless of subscription tier (see Article 2 and Article 10).
- **Encryption in Transit**: All data transmitted to external services (OpenAI, Firebase Cloud Functions, Apple) uses HTTPS/TLS encryption.
- **Encryption at Rest**: Data stored on the device is protected by iOS device encryption. iCloud data is protected by Apple's encryption standards.
- **Minimal Data Transmission**: Only the minimum data necessary for Pro features (text only) is transmitted to OpenAI or, when selected by the user, to Apple Private Cloud. Audio files are never transmitted to OpenAI or Apple.
- **MCP Local Integration Security (Pro, User's Choice)**: Even when this feature is on, the server responds only to this Mac itself (loopback address, 127.0.0.1), and no other device on the same network can reach it. Access requires a token stored in the device's Keychain (device-local, not synced via iCloud), and the server runs only while the app is running.
- **System Audio Capture Security (Pro, macOS Only)**: Captured audio follows the same local storage and processing path as microphone recordings, and a persistent visual indicator is shown in the menu bar and the recording screen while capture is in progress (see Article 6-5).
- **Backend Infrastructure (Firebase Cloud Functions)**: The Operator operates Google Firebase Cloud Functions (United States region, project `cleio-prod`) for the following purposes.
  - OpenAI API proxy (API key protection and usage management)
  - Subscription verification (Apple StoreKit JWS signature validation)
  - Usage limit management and usage logging
  - This infrastructure is invoked only for transcription/summary/translation requests, and original media such as audio files are never transmitted to it.
  - Apple Private Cloud summarization (Article 6-3) does not pass through this backend; it is transmitted directly from the user's device to Apple's servers.

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
