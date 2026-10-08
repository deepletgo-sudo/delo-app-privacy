# DELO Privacy Policy

**Last updated: October 7, 2026**

---

## Our Commitment to Your Privacy

DELO is a personal journaling and emotional expression app. We understand that the thoughts and feelings you record are deeply personal. Privacy is not an afterthought — it is the foundation of everything we build.

This Privacy Policy explains what information we collect, what we do not collect, and how we protect your data.

---

## 1. Information We Collect

We collect minimal information necessary to operate the app:

**Device Information (if analytics enabled):**
- Device model and operating system version
- App version and build number
- General usage patterns (screens visited, features used)
- Crash reports and error logs

**Account Information:**
- Username (optional, stored locally only)
- Subscription status (managed by Apple/Google via RevenueCat)
- Legal disclaimer acceptance timestamp

All of the above is either stored locally on your device or processed in anonymized, aggregated form.

---

## 2. Information We Do NOT Collect

We do NOT collect, transmit, store on servers, or have access to:

- The content of your journal entries or secrets
- Your emotions or emotional selections (stored locally only; never shared except as described in Section 5)
- Your reflection answers or ritual responses
- Your encryption keys or passwords
- Your real name, email address, or phone number
- Your location data
- Your contacts, photos, or other device data

Your journal content is encrypted using AES-GCM-256 encryption and stored exclusively on your device. We have no technical ability to access it.

---

## 3. Analytics & Crash Reporting

DELO uses Firebase Analytics and Firebase Crashlytics, services provided by Google, for the following purposes:

**Firebase Crashlytics (ages 13 and up; always off for ages 9–12):**
- Collects crash reports to help us fix bugs
- Includes device type, OS version, and stack traces
- Does NOT include any journal content or emotional data

**Firebase Analytics (opt-in only, adults 18+):**
- Tracks anonymous usage patterns (e.g., which screens are visited)
- Helps us understand which features are most valuable
- Disabled by default — you must opt in via Settings
- Can be disabled at any time in Settings > Security & Data

Google's privacy policy applies to data processed by Firebase: https://policies.google.com/privacy

---

## 4. How We Use Information

The limited information we collect is used exclusively to:

- Fix crashes and improve app stability
- Understand feature usage to improve the app experience
- Process subscription purchases (via Apple/Google)
- Comply with legal obligations

We do NOT use your data for:
- Targeted advertising
- Selling to third parties
- Profiling or behavioral analysis
- Marketing communications

---

## 5. Data Storage & Encryption

Your journal entries and secrets are:

- Encrypted with AES-GCM-256 (military-grade encryption)
- Stored exclusively on your device
- Protected by device-bound encryption keys that never leave your device

App settings and preferences are stored locally using your device's secure storage mechanisms (SharedPreferences, Keychain/Keystore).

**AI Insights (opt-in; Premium and Ultra; adults 18 and older):**

If you choose to enable AI Insights, the decrypted text of released entries is sent via our Cloud Function proxy to a third-party AI provider (Anthropic Claude for single-entry reflections, Google Gemini for batch pattern analysis — see Section 6) to generate reflections. This data is:

- Sent anonymously — no user account, name, or identity is attached
- Not stored on any server after processing
- Never used for training, advertising, or profiling
- Only sent for entries you have already released through a Ritual

AI Insights are designed and supported for entries written in English only. Entries in other languages may produce inaccurate, incomplete, or no results. The AI proxy does not scan your entries for crisis or risk language and performs no safety monitoring.

**Body Awareness Data (somatic zones):**

If you select body zones during a somatic check-in (e.g. "shoulders", "chest"), those selections are stored encrypted on your device and never shared or sold. If AI Insights is enabled, somatic zone names may be included anonymously in the AI payload alongside your entry text to generate richer, more personalised reflections. This data is processed under the same conditions as entry text: not stored on any server after processing, never used for training or profiling, and always anonymous.

**Wearable Sync & Wellness Signals (opt-in, Premium tier and above):**

If you connect a wearable or activity tracker (Apple Health on iPhone, e.g. with an Apple Watch), DELO reads read-only wellness signals — such as activity level, sleep duration, and recovery patterns — from your device's activity store. These signals are:

- Stored in encrypted form on your device only
- Never sold, shared, or transmitted in identifiable form, to anyone, including AI providers
- Used exclusively for on-device features: the Health Correlation Card and the proactive wellness nudge, both shown only within the app

Wellness data is never included in AI Insights requests or any other transmission, regardless of subscription tier or which features are enabled — this data never leaves your device.

---

## 6. Third-Party Services

We use the following third-party services:

**Firebase (Google):**
- Crash reporting (Crashlytics) and analytics
- Privacy: https://firebase.google.com/support/privacy

**RevenueCat:**
- Subscription and in-app purchase management
- Processes payments through Apple App Store / Google Play
- Privacy: https://www.revenuecat.com/privacy

**Apple Watch / Activity Trackers (via Apple Health on iPhone):**
- Read-only access to wellness signals when you grant permission
- Wellness data remains on your device; never transmitted anywhere, including to AI providers
- Apple Health privacy: https://www.apple.com/legal/privacy/data/en/health-app/

**Anthropic / Google (AI providers — Premium and Ultra, adults 18 and older):**
- Receive anonymous AI request payloads via our Cloud Function proxy
- Anthropic: https://www.anthropic.com/privacy
- Google: https://policies.google.com/privacy

**Voice dictation (Apple / Google speech recognition):**
- For adults, dictation uses your device's built-in speech recognition, which may send audio to Apple or Google to turn it into text, under their privacy policies. DELO never receives the audio.
- For users under 18, dictation runs on the device only.

These services process only the minimum data necessary for their function. Apart from AI Insights (above), none of them receive your journal content, and none receive identifiable wellness data.

---

## 7. Your Rights

You have the following rights regarding your data:

**Opt-Out of Analytics:**
- Go to Settings > Security & Data > Usage Analytics
- Toggle off to stop anonymous usage tracking
- Crash reporting remains active for users 13 and older, to maintain app quality

**Delete All Data:**
- Go to Settings > Danger Zone > Erase Everything
- This securely overwrites all encrypted data and resets the app
- This action is permanent and cannot be reversed

**Access Your Data:**
- All your data is stored locally on your device
- You have direct access to it through the app at all times

For EU/EEA residents (GDPR), California residents (CCPA), and users in other jurisdictions with data protection laws: you may contact us to exercise additional rights at deepletgo@gmail.com.

---

## 8. No Sale of Personal Data

Yodha Systems LLC does NOT sell, rent, trade, or otherwise transfer your personal information to third parties for commercial purposes.

Your journal content, emotional data, and personal information will never be monetized, sold to data brokers, or used for targeted advertising.

The only third-party data sharing that occurs is strictly necessary for app operation or for features you have explicitly opted into (e.g., anonymous crash reports to Firebase, subscription status to RevenueCat, or anonymous AI request payloads to Anthropic/Google when you enable AI Insights — see Sections 5 and 6) and is governed by their respective privacy policies.

---

## 9. Security Disclaimer

Yodha Systems LLC implements reasonable technical and organizational safeguards to protect your data, including AES-GCM-256 encryption and device-bound keys.

HOWEVER, NO SYSTEM CAN GUARANTEE ABSOLUTE SECURITY. By using the App you acknowledge and accept that:

- No method of electronic storage or transmission is 100% secure
- We cannot guarantee that unauthorized access, data loss, or breaches will never occur
- We are not liable for security incidents beyond our reasonable control

In the event of a data breach that affects your personal information, we will notify you as required by applicable law.

---

## 10. International Data Transfers

Yodha Systems LLC is based in the United States. By using the App, you acknowledge that data may be processed in jurisdictions outside your country, including the United States, where data protection laws may differ from those in your jurisdiction.

Third-party services we use (Firebase, RevenueCat) may process data in multiple countries. We ensure these providers maintain appropriate safeguards under their respective data processing agreements.

Your journal content is stored exclusively on your device and is never transferred internationally, except for opt-in AI Insights (Premium and Ultra plans, adults 18 and older only). With your explicit consent, the text of entries you let go — which may include information about your health, feelings, or wellbeing — is sent to Anthropic and Google and processed in the United States. It is processed anonymously and is not stored after processing. You can withdraw this consent at any time by turning off AI Insights in Settings › Security & Data.

---

## 11. India — Digital Personal Data Protection Act 2023 (DPDP)

For users in India, the following additional rights and obligations apply under the Digital Personal Data Protection Act, 2023 (DPDP Act):

**Data Fiduciary:**
Yodha Systems LLC is the Data Fiduciary responsible for processing your personal data.

**Your Rights as a Data Principal:**
- Right to access information about personal data processed
- Right to correction and erasure of inaccurate or incomplete data
- Right to grievance redressal
- Right to nominate another person to exercise your rights

**Grievance Redressal:**
If you have a grievance regarding the processing of your personal data, you may contact our Grievance Officer at: deepletgo@gmail.com

We will acknowledge your grievance within 48 hours and resolve it within 30 days of receipt.

---

## 12. Children's Privacy & Minor Protections

**DELO is for ages 9 and up.** When you first open the App, we ask for your birth month and year. Only the month and year are kept, on your device — they are never sent to us. If you are under 9, the App does not continue. Where the law requires it, DELO also reads the age range your app store shares (Apple's Declared Age Range or Google Play Age Signals); only the resulting age group is kept, on your device, and the store's age range can lower but never raise it. If a parent manages the account through the store and has not approved DELO's latest update, the App waits for their approval. Some countries have stricter rules: in South Korea DELO is for ages 19 and older, in India for ages 18 and older, and in Brazil for ages 18 and older with the age confirmed by the app store.

**What each age can use.** Plans and prices are the same for everyone; age only decides which features are available:

- Ages 9–12: journaling, let go, rituals, vault, voice notes, moods, and all other on-device features on the Basic and Premium plans.
- Ages 13–15: the same, on the Basic and Premium plans.
- Ages 16–17: the same, plus Privacy Shield on the Ultra plan — a second journal space behind its own PIN; opening the App with that PIN shows only the entries written for it.
- Ages 18 and older: every feature, including AI Insights and Body & Mind.

**Children under 13 (COPPA).** For users aged 9–12, DELO does not collect personal information. For these users there is no account or anonymous sign-in, no Sign in with Apple or Google, no crash reports, no usage analytics, and no anonymous insight sharing, and voice dictation runs on the device only. A parent or guardian must answer a short question before a purchase, sharing, emailing us, or exporting data.

The only information that leaves the device for a user aged 9–12 supports the internal operations of the App, as permitted under COPPA: (1) only once the plans screen is opened, RevenueCat receives an app-generated purchase ID, the App Store or Google Play receipt, basic device information, and an IP address, solely to show plans and to confirm and deliver a plan bought through the store; and (2) Firebase Remote Config receives an app installation identifier together with standard connection information (IP address, app and operating-system version, language, and time zone), solely to download settings the App needs to work. These identifiers are never used for advertising, profiling, or any other purpose: the providers process them on our behalf under their data processing terms, and for this age the App turns off advertising identifiers, analytics, and crash reporting.

**Users aged 13–17.** The following protections apply automatically:

- Usage analytics and anonymous insight sharing are always off
- No behavioral profiling based on activity or emotional patterns
- No emotional analysis transmitted off-device
- No targeted persuasion techniques, win-back offers, or ad-based engagement mechanics
- Voice dictation runs on the device only

Anonymous crash reports (Section 3) and optional Sign in with Apple or Google are available from age 13.

**AI Insights and Body & Mind are restricted to users aged 18 and older** on every plan. For anyone under 18 these features are hidden, no health or wearable data is read, and nothing is ever sent to our AI providers.

**Parents and guardians.** Users under 18 may use DELO with the permission of a parent or guardian (see the Terms of Service). Purchases are made through the App Store or Google Play, so Ask to Buy and family purchase settings apply. A "For parents" page in Settings explains what is on and off at your child's age. Journal content is encrypted on the device and we cannot access it. If the age entered is wrong, it can be corrected in Settings › Your age; raising an under-18 user's age asks a parent or guardian to answer a short question first. To delete your child's data, use Settings › Danger Zone › Erase Everything, or contact us at the address in Section 15.

**Retention for users aged 9–12.** We keep no personal information about users aged 9–12 on our own servers. Remote Config requests are handled by Google and are not stored by us. RevenueCat keeps a purchase record for as long as the subscription is active and afterwards only as long as tax and accounting law requires; you can ask us to have it deleted sooner by contacting us.

**Turning 18.** When a user turns 18, AI Insights (if they choose to use it) covers only entries written from then on, unless they separately choose to include earlier entries. Entries written before age 13 are never included.

**The App does not provide counseling, therapy, or mental health services to minors** (or to any user). DELO is a personal expression tool — it does not attempt to interpret or improve your mental state.

Your journal content and vault entries use a zero-knowledge architecture: they remain encrypted locally on your device, and we have no technical ability to access them. This does not apply to the anonymous, opt-in AI and wellness-signal data flows described in Sections 5 and 6 — those are explicit exceptions you control, not something we passively collect.

---

## 13. Data Retention

- **Local data:** Retained on your device until you delete it or use Erase Everything.
- **Analytics data:** Retained by Firebase for up to 14 months, after which it is automatically deleted.
- **Crash reports:** Retained by Firebase Crashlytics for 90 days.
- **Subscription data:** Retained by Apple/Google per their respective policies.

---

## 14. Changes to This Policy

We may update this Privacy Policy from time to time. When we make material changes, we will:

- Update the "Last updated" date at the top of this policy
- Increment the legal version number in the app
- Require re-acceptance of the legal disclaimer

Continued use of the app after changes constitutes acceptance of the updated policy.

---

## 15. Contact Us

If you have questions or concerns about this Privacy Policy or our data practices, please contact us at:

**deepletgo@gmail.com**

Yodha Systems LLC
New Jersey, United States
