# Privacy Policy

**Last updated:** July 12, 2026

**App name:** Perspective: AI assisted CBT  
**Package:** `com.perspectivecbtapp`  
**Contact:** [support@perspectivecbtapp.com](mailto:support@perspectivecbtapp.com)  
**Policy URL:** [https://perspective-cbt.github.io/perspective-legal/privacy-policy/](https://perspective-cbt.github.io/perspective-legal/privacy-policy/)

This Privacy Policy explains how Perspective: AI assisted CBT (“we”, “us”, “the app”) collects, uses, stores, and shares information when you use our cognitive behavioral therapy (CBT) reflection app on Android (and other platforms where available).

Perspective: AI assisted CBT is a self-help journaling and reflection tool. **It is not medical care, therapy, or a substitute for professional mental health treatment.** If you are in crisis, contact local emergency services (for example, **911** in the U.S.) or a qualified professional immediately.

## Summary

- We collect account and app data needed to sign you in, sync your thought records, run AI-assisted thought records you request, and process subscriptions.
- Your thoughts and analyses are sensitive health-related information. We treat them accordingly and give you export and deletion options.
- When you create a thought record, your text is processed on our servers and may be sent to **Google Gemini (Google AI)**.
- We collect limited **first-party product analytics** (such as app opens and screen views) to understand usage and improve reliability.
- Paid features use **Google Play Billing**. Purchase and subscription status may be verified with Google and stored with your account.
- Data is stored **on your device** and, if you have an account, **on our cloud database** (hosted on **Railway**).
- You can **export** your data from the app and **delete your account** to remove synced server data.

## Information we collect

### Account and authentication

- **Email address** and **password** (passwords are hashed; we do not store plain-text passwords).
- **Email sign-in codes** when you use passwordless login (we send a one-time code to your email).
- If you use **Google Sign-In**, we receive information allowed by that service (such as email and basic profile details from Google).
- On supported Apple devices, **Sign in with Apple** may provide email and an Apple user identifier.
- **Authentication tokens** to keep you signed in securely.

### Profile and preferences (optional)

- **Display name** (first name or nickname you choose).
- **Profile photo** if you upload one.
- **Mental health context preferences** you choose to share (self-reported; not a diagnosis).
- **App preferences** (appearance, accessibility, quiet progress mode, spoon budget, etc.).
- **AI context settings** (such as whether past entries may be used to personalize analyses).

### Content you create

- **Inbox thoughts** (text you capture before a Thought Record).
- **Thought records** (emotions, thought patterns, balanced perspectives, action plans, and related fields).
- **Vault entries** (saved analyses you keep).
- **Clarification questions and answers** from the thought record wizard.
- **Drafts** of in-progress analyses stored on your device.
- **Metadata** such as titles, tags, timestamps, emotional intensity, and sort order.

### Subscriptions and purchases (Google Play)

- When you subscribe or restore purchases, we may process **product IDs**, **purchase tokens**, **order / subscription status**, **expiry / renewal info**, and related billing metadata needed to unlock Premium features and prevent fraud.
- Google processes payment details under Google Play’s policies. We do **not** receive your full payment card number.

### Product analytics and diagnostics

When you are signed in, the app may send first-party analytics events to our servers, such as:

- App opens and approximate session length
- Screen views and selected in-app taps / feature uses
- Platform (for example Android) and app version
- Aggregate AI usage metrics (token estimates and estimated cost) used to operate and budget the service

These analytics help us understand which features are used and keep the service reliable. They are **not** used for third-party advertising.

We may also collect **crash and error diagnostics** (for example stack traces, device model, OS version, and app version) through a crash-reporting provider such as **Sentry**, so we can find and fix bugs. Crash reports are configured to avoid intentionally collecting thought-record contents.

### Usage and service data

- **Monthly / daily usage counts** (for example, number of analyses and revisions) to enforce free-tier limits and fair use of AI features.
- **Sync metadata** needed to merge inbox, vault, and preferences across devices.
- **Basic server logs** (such as request errors) for reliability and security.

### Information we do not intentionally collect

- We do not require your legal name, phone number, or precise location.
- We do not sell your personal information.
- We do not use your thought records for advertising.
- We do not train our own models on your content.

## How we use your information

We use information to:

- Create and manage your account and authenticate you.
- Store and sync your inbox, vault, drafts, and settings.
- Generate thought records, clarifications, activity insights, and related AI features **when you request them**.
- Verify subscriptions, restore purchases, and provide Premium features.
- Enforce usage limits and prevent abuse of AI features.
- Understand product usage and improve reliability (analytics and crash reporting).
- Send transactional email (such as sign-in codes or password reset messages).
- Maintain security, debug failures, and improve reliability.

## AI and automated processing

When you start or revise a Thought Record, **the text you provide** (thought, optional context, clarification answers, profile context you enabled, and related thought record fields) is sent to **our backend**, which calls **Google Gemini (Google AI)** to generate a response.

Google processes this data under [Google’s terms and privacy policies](https://policies.google.com/privacy). We configure these features to provide you a response, not for us to resell your data.

**You choose when to run AI.** You can capture thoughts locally without a Thought Record; creating one requires an account and internet access in normal use.

## Third-party services

| Service | Purpose |
|--------|---------|
| **Google Gemini / Google AI** | Generate thought records and related AI features |
| **Google Sign-In** | Optional authentication |
| **Google Play Billing** | Subscriptions, purchase verification, and restore |
| **Sign in with Apple** | Optional authentication (where supported) |
| **Railway** | Cloud hosting for our API and database |
| **PostgreSQL** (via Railway) | Encrypted-at-rest database storage for account and synced data |
| **Resend** | Transactional email (sign-in codes, password reset) |
| **Sentry** (when enabled) | Crash and error diagnostics |

Links to third-party policies:

- Google: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- Apple: [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
- Railway: [https://railway.com/legal/privacy](https://railway.com/legal/privacy)
- Resend: [https://resend.com/legal/privacy-policy](https://resend.com/legal/privacy-policy)
- Sentry: [https://sentry.io/privacy/](https://sentry.io/privacy/)

## Where data is stored

- **On your device:** Inbox, vault, thought record drafts, preferences, and cached account data may be stored locally using your device’s secure storage mechanisms.
- **On our servers:** If you create an account, synced inbox, vault, preferences, profile fields, subscription status, analytics summaries, and usage records are stored in our PostgreSQL database on Railway.

Production traffic uses **HTTPS**. Local development builds may use different API endpoints.

## Device permissions

The app may ask for:

- **Internet access** — sync, sign-in, AI analyses, and billing verification.
- **Photos / camera** — only if you choose a profile picture.
- **Notifications** — optional (for example app-icon badge / reminders), if you enable related features.
- **Biometric unlock** — optional app lock; biometric data stays on your device and is not sent to us.

You can deny optional permissions and still use core features that do not require them.

## Your choices and rights

### Offline use

Many capture and reading features work offline. **Sync, AI analyses, and subscription verification require an internet connection** and (for AI) a signed-in account.

### Export your data

In the app: **Settings → Data & export → Export my data**. This creates a **JSON file** with your local inbox, vault, preferences, and mental health profile preferences so you can save or share it.

### Clear local data

**Settings → Data & export → Clear local data** removes inbox, vault, and drafts from **this device only**. Your cloud account and synced data remain until you delete your account.

### Delete your account

**Settings → Data & export → Delete account** (while signed in) deletes your account and **associated server data**, including synced inbox, vault, profile fields, and usage records tied to your account.

Account deletion is intended to be permanent. We may retain minimal information only where required by law or for security (for example, fraud prevention logs for a limited time).

### Manage subscriptions

Subscriptions are billed through **Google Play**. You can cancel or manage renewal in Google Play subscription settings. Canceling stops future renewals according to Google Play’s rules; it does not automatically delete your Perspective account.

### Contact us

Email [support@perspectivecbtapp.com](mailto:support@perspectivecbtapp.com) to ask questions about your data or to request help with export or deletion.

Depending on where you live, you may have additional rights (access, correction, portability, objection). Contact us and we will respond within a reasonable time.

## Data retention

- We retain your data **while your account is active** and as needed to provide the service.
- When you delete your account, we delete associated personal data from our production database, subject to limited exceptions (backups for a short period, legal obligations, or security logs).
- Local data on your device remains until you clear it or uninstall the app.
- Crash reports and server logs are retained only as long as needed for debugging and security.

## Security

We use industry-standard practices including password hashing, authenticated API access, HTTPS in production, and access controls on our database. No method of transmission or storage is completely secure; use a strong password and protect access to your device.

## International transfers

Our servers may be located in countries other than yours (including the United States). By using the app, you understand your information may be processed in those locations, with appropriate safeguards for service operation.

## Children

Perspective: AI assisted CBT is **not directed to children under 13** (or the minimum age required in your country). We do not knowingly collect personal information from children. If you believe a child has provided us data, contact us and we will delete it.

## Changes to this policy

We may update this Privacy Policy from time to time. We will post the updated version at [https://perspective-cbt.github.io/perspective-legal/privacy-policy/](https://perspective-cbt.github.io/perspective-legal/privacy-policy/) and change the “Last updated” date. Continued use of the app after changes means you accept the updated policy.

## Contact

**Email:** [support@perspectivecbtapp.com](mailto:support@perspectivecbtapp.com)

---

*This policy describes our current practices. It is not legal advice.*
