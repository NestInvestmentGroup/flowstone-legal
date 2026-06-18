# Privacy Policy

> **Status: starting draft for legal review.** This document is tailored to what Flowstone actually does today (anonymous-first auth, local-first engagement storage, optional Supabase sync, and the Kids lane parental gate). It is not legal advice and must be reviewed by a qualified attorney in your jurisdiction before you publish or rely on it. Search the document for every `[BRACKETED]` placeholder and fill them in.
>
> **Last updated: 2026-06-12**

## 1. Who we are

Flowstone is a meditation app for kids, teens, and adults. Flowstone is operated by The Nest Investment Group LLC ("we", "us", "our"), located at 116 Agnes Road, Suite #200, Knoxville, TN 37919, USA. You can reach us with any privacy question at inquiry@thenestinvestmentgroup.com.

## 2. What this policy covers

This policy applies to:

- Flowstone mobile app (iOS and Android)
- The admin web page used by our content team to manage meditations
- Any communications you send us at the contact addresses above

It does not cover websites, apps, or services run by other companies, even if we link to them.

## 3. The shortest possible version

- We do not collect your name, postal address, phone number, or location.
- You can use Flowstone without creating an account. Your engagement data (check-ins, journals, sessions, goal) lives on your device first.
- If you sign in with Apple or Google in the future, we receive a stable identifier from them; we do not receive your password.
- For the Kids lane, a parent or guardian completes a verification step before any data is collected. Kid use is tied to a parent account.
- We do not sell your data. We do not run third-party advertising.
- Sleep and heart rate are off by default. If you connect them, we read only your recent sleep duration and heart-rate samples from Apple Health or Health Connect to show your sleep alongside your mood and to notify you when your heart rate spikes so you can take a breath. We never sell or share this data.
- You can delete your account and the data tied to it at any time from the in-app **Settings > Danger zone**, or by emailing inquiry@thenestinvestmentgroup.com.

## 4. The information we collect

### 4.1 Lane preference

When you choose a lane (Kids, Teens, or Adults), we store that choice on your device so we can show you appropriate content. If you sign in, we also store the lane on your account.

### 4.2 Engagement data (local-first)

Flowstone creates the following records when you use the app. Each record is stored on your device first. If you sign in, the same record is also stored on our servers so it is available across devices.

- Daily check-ins: a date, a mood value (1 to 5), and any note you choose to add.
- Mood check-ins before and after a session: a mood value (1 to 5) and a reference to the session.
- Session records: which meditation you read, when you started, when you finished, and how long you spent.
- Journal entries: the text you write.
- Goal: the goal type (days per week or minutes per week) and the target you choose.
- Notification preferences: whether your daily reminder is on and the time you picked.

You write the text in journals and check-in notes. Treat that text the way you treat anything you write down: only include what you are comfortable having stored.

### 4.3 Account data

If you create an account, you do so in one of these ways:

- Anonymous account: created automatically when you first open the app. We receive a randomly generated identifier from our authentication provider. No name, email, or password is collected.
- Apple Sign-In or Google Sign-In: when this option is available, you authorize Apple or Google to share a stable identifier with us. We may also receive an email address you choose to share. We never receive your Apple or Google password.

### 4.4 Device and technical data

When the app communicates with our servers, our infrastructure provider receives basic technical information that any web-connected service receives: IP address, approximate request time, and the request itself. Our provider may retain this information in security and operations logs for a short period to keep the service safe.

We do not embed third-party advertising or analytics SDKs that profile you across other apps and websites. If we add any analytics in the future, we will update this policy and, where required, ask for your consent.

### 4.5 Notifications

If you turn on the optional daily reminder, the app schedules a local notification on your device. The reminder is delivered by your device's operating system at the time you chose. We do not send these reminders from our servers and we do not learn whether you opened them.

### 4.6 What we do not collect

Flowstone does not collect:

- Your name, postal address, or phone number
- Your location
- Photos, video, or audio recordings (no microphone or camera access)
- Contacts or calendars
- Advertising identifiers
- Information about other apps on your device

If we add a feature that needs any of these, we will update this policy and ask for your consent first.

### 4.7 Health data (sleep, heart rate, mindful minutes)

Flowstone reads three categories of health data, all opt-in, all read-only except where noted, and all used strictly inside the app to make the experience better for you. We request access only to the specific data types described below, and nothing else.

**Sleep.** Used on the Pattern Mirror screen (Teens and Adults lanes only) to show how your recent sleep relates to your mood. **Off by default** — happens only after you tap "Connect your sleep" and grant permission.

**Heart rate.** Used by the optional "settle for a breath?" nudge that fires a notification when your heart rate climbs meaningfully above your resting baseline (for example, twenty beats per minute above your usual resting rate). The notification opens the Breathe pacer. **Off by default** — happens only after you grant heart-rate read access. You can turn it off at any time by revoking the permission in your device's health settings or disabling notifications in your device's settings for Flowstone.

**Mindful minutes (iOS only).** We write a Mindful Session entry to Apple Health when you finish a breath session, so your session shows up alongside other mindful activity in Apple Health. The entry reflects the actual duration of the session you completed — we never write false, estimated, or inaccurate data. We never read it back.

For all three:

- **Where it comes from:** Apple Health (HealthKit) on iOS and Health Connect on Android.
- **What we read:** only the data categories above (sleep duration, heart rate samples, resting heart rate). We never read any other health category.
- **What we write:** only the Mindful Session entry described above. We never write to any other category. We never write at all on Android.
- **How we use it:** only to display information in the app and to fire the optional heart-rate nudge. We do not use it for advertising, profiling, data mining, or automated decision-making.
- **Where it is stored:** on your device. Heart-rate samples are read in memory to decide whether to nudge you and are not persisted on our servers. Sleep totals are stored on our servers (Supabase) so the feature works across your devices if you are signed in, under the same protections as your other engagement data.
- **Turning it off:** revoke Flowstone's access at any time in your device's Apple Health or Health Connect settings. Deleting your account (Settings > Danger zone) deletes the stored health data.

**Apple Health (HealthKit) — our specific commitments.** When Flowstone reads from or writes to Apple Health on iOS, we follow Apple's HealthKit requirements:

- We request only the specific HealthKit data types we use: heart rate and resting heart rate (read), sleep analysis (read), and mindful sessions (write). You grant or deny each type individually in Apple Health, and you can change your decision at any time in **Settings > Health > Data Access & Devices > Flowstone**.
- We **never** use HealthKit data — including heart rate — for advertising, marketing, or use-based data mining, and we never permit any third party to do so.
- We **never** sell HealthKit data, and we never disclose or share it with third parties, including data brokers, for any purpose other than the in-app sleep and heart-rate features described above.
- We **never** store any HealthKit data in iCloud.
- We write only mindful-session data that accurately reflects a session you actually completed in the app.

**Health Connect (Android).** Our access, use, and storage of data read through Health Connect complies with the Health Connect Permissions policy and Google's limited-use requirements. We do not sell this data, use it for advertising, transfer it to data brokers, or use it for any purpose other than the in-app sleep and heart-rate features described above.

## 5. How we use information

We use the information described above only to:

1. Provide the app and its core features (showing meditations, recording your check-ins, calculating your streak and weekly progress).
2. Sync your data across your devices when you sign in.
3. Keep the service secure (detecting abuse, debugging issues).
4. Communicate with you about important account or service matters at the email you have shared with us, if any.

We do not use your information to:

- Build advertising profiles
- Sell, rent, or trade information to third parties
- Train external machine learning models on your journal entries or notes

## 6. Children's privacy (COPPA and similar laws)

### 6.1 The Kids lane

The Kids lane is intended for users aged 4 to 11. Before a user can enter the Kids lane, the app presents a parental verification step that a child is unlikely to complete on their own. Once verified, the resulting profile is treated as a kid profile and is tied to the verifying parent's account when accounts are available.

We collect from the kid only the minimum needed to operate the service:

- Lane choice and the selections the kid makes within the app
- Engagement records (check-ins, sessions, journal entries, mood values)

We do not collect a kid's real name, photo, voice, location, contacts, or any identifier other than the random account identifier we receive from our authentication provider.

We do not show third-party advertising to children. We do not use kid data for behavioral advertising. We do not share kid data with third parties except the service providers listed in Section 7, and only as needed to run the service.

### 6.2 Parental rights

A parent or guardian of a Kids lane user can, at any time:

- Use the in-app **Settings > Danger zone > Delete account** option to delete the kid's profile and all data tied to it.
- Email inquiry@thenestinvestmentgroup.com to request a copy of the data, ask us to delete the kid's profile, or withdraw consent for further data collection.

We will respond to email requests within 30 days and may ask reasonable questions to confirm you are the parent on file. In-app deletion is immediate.

### 6.3 If you are a kid

The Kids lane is meant for you to use with a parent's permission. We collect only what you tap inside the app. We do not ask for your real name, your phone, or your address. If you are not sure about any of this, ask a grown-up to read this with you, or have them email us.

## 7. Service providers

We use a small set of service providers to operate Flowstone. Each one acts on our instructions and is bound to keep your information confidential.

- **Supabase, Inc.** (database, authentication, file storage). Region: us-west-2. Privacy policy: https://supabase.com/privacy.
- **Apple Inc.** and **Google LLC** (Sign in with Apple and Sign in with Google), if you choose to upgrade to a signed-in account.
- **Expo (650 Industries, Inc.)** for the mobile app build and over-the-air update infrastructure. Push notifications scheduled on your device do not flow through Expo's servers; remote notifications, if we add them later, will.
- **Vercel Inc.** for hosting the admin web page used by our content team.

If we change service providers we will update this list.

## 8. International transfers

We are based in the State of Tennessee, USA. Our service providers may store and process information in other countries, including the United States. Where required, we put in place appropriate safeguards (for example, the Standard Contractual Clauses approved by the European Commission) for international transfers.

## 9. How long we keep data

- **Engagement data on your device**: kept until you uninstall the app or clear local storage.
- **Engagement data on our servers** (when you sign in): kept while your account is active. When you delete your account, we delete this data within 60 days except where we must retain a copy to comply with the law or resolve a dispute.
- **Operational logs**: kept for a short period (typically 30 to 90 days) and then aggregated or deleted.

## 10. Your rights

Depending on where you live you may have the following rights regarding your information. Two of them are self-service in the app:

- **Delete your account and data**: in-app **Settings > Danger zone > Delete account**.
- **Download a copy of your data**: in-app **Settings > Account > Export your data**. The export is generated as a printable "Year of Flowstone" PDF (cover, active-days summary, practices, intentions, mood overview, and your reflections) covering your local check-ins, sessions, sleep records, journal entries, goal, and reminder preferences. A raw JSON file is provided as a fallback when the PDF generator is unavailable.

To exercise any other right (correction, restriction, objection, withdrawing consent, or filing a complaint), email inquiry@thenestinvestmentgroup.com.

- Access: ask for a copy of the personal data we hold about you.
- Correction: ask us to correct inaccurate data.
- Deletion: ask us to delete your data.
- Portability: ask us to provide your data in a portable format.
- Objection / restriction: ask us to stop or limit certain uses of your data.
- Withdraw consent: where we relied on your consent, you can withdraw it at any time.
- Lodge a complaint: residents of the EEA, UK, and similar regions may complain to their local data protection authority. Residents of California can find more information about their rights under the CCPA/CPRA in Section 11 below.

We will respond within the period required by your local law (typically 30 days).

## 11. Region-specific notices

### California (CCPA / CPRA)

In the past 12 months we have collected the following categories of personal information described above: identifiers (the random account identifier; an email if you sign in with Apple or Google), internet or electronic activity (engagement records inside our app), and inferences only as derived from that activity (your streak, weekly progress, goal). We do not sell or share your personal information for cross-context behavioral advertising.

You have the right to know, delete, and correct your personal information. We will not discriminate against you for exercising any of these rights.

### European Economic Area / United Kingdom (GDPR / UK GDPR)

The legal bases on which we process your personal data are:

- **Performance of a contract** with you, when we provide the app's core features.
- **Legitimate interests** in keeping the service secure and improving it, where those interests are not overridden by your rights.
- **Consent**, where we ask for it (for example, to enable optional analytics in the future).
- **Legal obligation**, where we must retain or disclose data to comply with the law.

You can object to processing based on legitimate interests at any time.

### Other regions

If you live in a region with its own privacy law (for example, Brazil's LGPD, Canada's PIPEDA, or any U.S. state law), the rights described above apply to the extent your local law gives them.

## 12. Security

We protect information using a mix of organizational and technical measures: signed-in connections, role-based access controls, row-level security at the database, and standard application hardening. No system is perfectly secure. If we ever discover a breach affecting your personal information, we will notify you and the relevant authorities as required by law.

## 13. Changes to this policy

We may update this policy from time to time. When we do, we will update the "Last updated" date at the top. For material changes we will let you know in the app or at the email address you have given us. Your continued use of the app after the changes take effect means you accept the new version.

## 14. Contact us

The Nest Investment Group LLC
116 Agnes Road, Suite #200, Knoxville, TN 37919, USA
inquiry@thenestinvestmentgroup.com
