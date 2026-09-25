# Privacy Policy - AccentMirror

**Last updated: 25 September 2026**

AccentMirror is developed and operated by Stuart Pendergast, a sole trader based in the United Kingdom. Stuart is the data controller for the personal data described here.

This policy explains what AccentMirror collects, why, who processes it, how long it is kept, and your rights under UK GDPR and other applicable data protection laws.

---

## The short version

- Your voice recordings are sent to speech services for transcription and scoring. We don't store your audio.
- From your first take, your scores, transcriptions and word-by-word results are backed up to our cloud database (Google Firebase) under an anonymous ID. You don't need an email address or an account for this.
- Without an account, that backup can't be restored after a reinstall or on another device. If you create an account, the backup is linked to it and can be restored.
- We don't sell your data.
- You can delete your data at any time with **Settings → Delete Account**, or by emailing accentmirrorapp@gmail.com.

---

## What we collect and why

### 1. Your voice and what you say

When you record a take, the audio is sent to speech services for transcription and pronunciation scoring:

- **Deepgram** - transcription of what you say in free practice (Stage 1).
- **Microsoft Azure Speech Services** - transcription and pronunciation scoring, and generating the reference and "accent mirror" audio you hear.
- **Microsoft Azure Translator** - translating your transcription so you can see what you said.

The text of your take, its word-by-word scores and your recent score history are then sent to **Anthropic** (Claude) through our own server functions, to generate your coaching tips, progress insights and practice phrases.

We don't store your audio. AccentMirror sends each recording for processing and keeps nothing afterwards, apart from short-lived playback files in your phone's temporary cache. Each provider handles the data it receives under its own terms and data protection agreements, which are linked below.

**Why:** this is the service you asked for. Without it, the app can't score or coach you. **Lawful basis:** performance of a contract (UK GDPR Art. 6(1)(b)).

### 2. Your practice history (backed up to the cloud)

On first launch, the app creates an **anonymous user ID** (Firebase Anonymous Authentication). This is a random identifier, not your device's hardware or advertising identifier.

From your first scored take, the following is stored in Google Firebase (Cloud Firestore) under that ID:

- each scored take: the phrase, your transcription, its translation, your score, band, word-by-word scores and score breakdown (no audio);
- exam results (phrases, scores, improved and weak words);
- usage counters that enforce daily take limits and prevent abuse, a marker showing you've used your free trial, and a count of AI requests.

**Stays on your device only:** your coaching summaries and tips, your language settings (unless you have an account), cached audio and translations, and app preferences.

**Without an account**, the cloud backup can't be restored if you reinstall the app, clear its data or change phone, because nothing can sign back in to that anonymous ID.

**With an account**, the same backup is linked to your account, and your language settings are backed up too. That lets you restore your history on a new install or another device.

**Why:** to keep your progress safe, to enforce plan limits fairly, and to prevent abuse. **Lawful basis:** performance of a contract for your practice history; legitimate interests for limits, abuse prevention and security (Art. 6(1)(f)).

### 3. Your account (optional)

You can create an account in **Settings → Save your progress** with email and password, Sign in with Apple, or Google Sign-In. We store:

- your email address and the identifiers your sign-in provider gives us;
- for Sign in with Apple, a token held on our server so we can revoke Apple access when you delete your account.

**Lawful basis:** performance of a contract.

### 4. Progress emails (optional)

If you tick the box to receive progress summaries and product updates, we store your email address and your choice. We haven't started sending these yet, and we'll update this policy before we do. You can change your mind at any time by contacting us. **Lawful basis:** consent (Art. 6(1)(a)).

### 5. Analytics

We collect usage events (such as "session started" and "score shown") through **Google Analytics for Firebase** to fix bugs and improve the app. Events don't include audio, transcriptions or your email address. Events are tied to a random app-instance identifier, not to your AccentMirror user ID or account. **Lawful basis:** legitimate interests. You can object at any time by contacting us.

### 6. Advertising (free Echo plan)

The free Echo plan shows ads, including optional rewarded video ads, through **Google AdMob**.

- In the UK, EEA and Switzerland, you choose whether ads can be personalised through Google's certified consent tool, shown on first use. You can change your choice at any time in **Settings → Manage ad privacy**.
- On iPhone, personalised ads also need your permission through Apple's App Tracking Transparency prompt.
- If you don't consent, or you're elsewhere and haven't consented, only non-personalised (contextual) ads are shown.

If you consent, your device's advertising identifier may be used. **Lawful basis:** consent for personalised ads; legitimate interests for non-personalised ads.

### 7. Subscriptions

Payments are handled by Apple (App Store) or Google (Google Play). We never see your card details. **RevenueCat** manages subscription status and receives your AccentMirror user ID and your purchase history. **Lawful basis:** performance of a contract; legal obligation for transaction records.

### 8. Shared AI cache

To keep costs down, generated coaching tips are cached on our server, keyed by language, band, the practice phrase and weak words. The cache isn't linked to your user ID.

---

## Who processes your data

| Provider | What for | Privacy policy |
|---|---|---|
| Deepgram | Speech-to-text for free practice | [deepgram.com/privacy](https://deepgram.com/privacy) |
| Microsoft Azure (Speech, Translator) | Transcription, pronunciation scoring, audio generation, translation | [privacy.microsoft.com](https://privacy.microsoft.com/en-gb/privacystatement) |
| Anthropic | AI coaching tips, insights and practice phrases | [anthropic.com/privacy](https://www.anthropic.com/privacy) |
| Google Firebase (Auth, Firestore, Cloud Functions) | Anonymous ID, cloud backup, server functions | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| Google Analytics for Firebase | Usage analytics | [policies.google.com/privacy](https://policies.google.com/privacy) |
| Google AdMob and User Messaging Platform | Ads and ad consent (Echo plan) | [policies.google.com/privacy](https://policies.google.com/privacy) |
| RevenueCat | Subscription management | [revenuecat.com/privacy](https://www.revenuecat.com/privacy) |
| Apple, Google | Payments; Sign in with Apple and Google Sign-In | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) · [policies.google.com/privacy](https://policies.google.com/privacy) |

**International transfers.** Some providers process data outside the UK, mainly in the USA, under their standard data protection terms and UK transfer safeguards.

---

## How long we keep it

- **Practice history without an account** (anonymous backup, usage and AI-request counters): deleted 12 months after your last take.
- **Practice history, exam results and account data with an account:** deleted 2 years after your last take or sign-in, or sooner if you delete your account or ask us to.
- **Analytics:** Google Analytics keeps event data for 2 months, and user-level data for 14 months after your last use of the app.
- **On-device data:** until you delete it in the app or uninstall.

---

## Deleting your data

- **Settings → Delete Account** deletes your cloud practice history, exam results, account profile, settings, trial marker and usage counters, and your sign-in account. It works even if you never created an account.
- **Privacy & Data → Delete all local data** clears the app's data on this device only. To remove your cloud data as well, use Delete Account **first**.
- If you've already reinstalled or cleared the app, email accentmirrorapp@gmail.com and we'll help where we can. Without an account, we may not be able to identify which anonymous backup is yours.

---

## Do I need an account?

No. AccentMirror works fully without one, and your practice history is backed up automatically under an anonymous ID. An account is only needed if you want to restore that history after reinstalling or on another device.

---

## What we don't do

- We don't sell your personal data.
- We don't store your voice recordings.
- We don't share your personal data with anyone except the providers listed above, and only for the purposes described.
- We don't use your transcriptions for anything other than running the app.

---

## Your rights under UK GDPR

You have the right to:

- **Access** a copy of your personal data
- **Rectification** of inaccurate data
- **Erasure** of your data
- **Restriction** of processing
- **Portability**: receive your data in a structured, machine-readable format
- **Object** to processing based on legitimate interests, including analytics
- **Withdraw consent** at any time, for personalised ads and progress emails

Contact accentmirrorapp@gmail.com. We'll respond within one month, and there's no charge.

If you're unhappy with our response, you can complain to the **Information Commissioner's Office (ICO)** at [ico.org.uk](https://ico.org.uk).

---

## California residents (CCPA/CPRA)

We don't sell your personal information. If you allow personalised ads, Google may use your device's advertising identifier to show them, which California law may treat as "sharing". You can stop this at any time by turning off ad tracking in your phone's settings, or by contacting us. California residents can also ask what we collect and have it deleted by emailing accentmirrorapp@gmail.com.

---

## Children

AccentMirror isn't directed at children under 13, and we don't knowingly collect data from them. If you believe a child has used the app, contact us and we'll delete their data.

---

## Changes to this policy

We'll update the date at the top whenever this policy changes. For significant changes, we'll let you know in the app before they take effect.

---

## Contact

Stuart Pendergast
Email: accentmirrorapp@gmail.com
United Kingdom

*AccentMirror is an independent app. It isn't affiliated with Microsoft, Anthropic, Deepgram, RevenueCat, Apple or Google.*
