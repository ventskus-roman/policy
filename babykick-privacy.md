---
layout: babykick
title: "Baby Kick — Privacy Policy"
lang: en
---

[English](https://ventskus-roman.github.io/policy/babykick-privacy) · [Русский](https://ventskus-roman.github.io/policy/babykick-privacy-ru) · [Português (Brasil)](https://ventskus-roman.github.io/policy/babykick-privacy-pt-br)

# Baby Kick — Privacy Policy

Last updated: October 30, 2026

Baby Kick is developed by Roman Ventskus, the seller listed on the App Store. For privacy or support, contact [scofield665@gmail.com](mailto:scofield665@gmail.com?subject=Baby%20Kick%20Privacy).

## Your records, iCloud and reports

Baby Kick stores movement sessions, counts and timestamps, goals, notes and contraction start/end times in its local data store. The store is configured to synchronize these records through Apple's iCloud/CloudKit when available. Due date, reminder preferences, language and other settings are stored on your device. Widgets use a shared local snapshot of session information and pregnancy week; a local queue lets the app save movements recorded outside its main screen. These functions remain available when usage analytics is off.

Reports are generated from the records you select. Sharing creates a temporary PDF. Recipients and services you choose can retain their own copies; deleting a session does not recall a shared report.

## Purchases and app configuration

Apple processes payments. RevenueCat validates purchases, provides subscription/Premium status, retrieves purchase options and restores access. RevenueCat uses a generated app user ID and purchase/transaction information. This ID is pseudonymous and can be linked to purchase history; it is not described as anonymous. Purchase processing works independently of the usage-analytics setting. Baby Kick does not ask you to provide an app account, name or email address for this purchase flow.

The app can keep a local experiment assignment to present a consistent experience. Retrieving current purchase/configuration options can send the app user ID to RevenueCat even when usage analytics is off. Experiment analytics is described below. See [RevenueCat's privacy information](https://www.revenuecat.com/privacy) and [Apple's privacy policy](https://www.apple.com/legal/privacy/).

## Usage analytics and your choice

In version 1.1.1, usage analytics is enabled by default without a startup approval prompt. A previous explicit choice to turn it off is preserved. You can turn it off or on using **Share usage analytics** in Settings. Records distinguish the default setting from changes you make. When collection is enabled, the app sends client usage events to PostHog. Events describe app opening, onboarding, feature actions, paywalls/plans, purchase outcomes, restoration/billing actions and experiment exposure. They include a pseudonymous app-scoped ID derived from the RevenueCat ID, app version/build, environment, interface language, App Store country, first-seen/install information and experiment assignment/exposure. SDK technical context can include device model/type, OS/version, system locale/time zone, screen dimensions, network type and SDK/session identifiers.

Custom event fields exclude movement counts, individual movement timestamps, medical durations, pregnancy dates, answers, notes and report contents. Events can still reveal use of a pregnancy app. The app configuration disables automatic screen/interaction collection, session replay, automatic error capture and surveys. PostHog uses a US Cloud project. Its SDK also stores a random installation UUID and uses this persistent identifier in configuration/feature-flag requests; these requests can include the app-scoped user ID and other SDK identifiers.

GeoIP enrichment is disabled for captured events. Configuration/feature-flag requests can still use an IP-derived approximate location while evaluating the request; this request-time evaluation is separate from writing geolocation to analytics events or person profiles. Network requests expose IP addresses to service providers. The shared PostHog project's IP-discard setting is currently off, and raw IP addresses and request identifiers may be retained in provider diagnostic logs. Disabling event GeoIP does not remove IP addresses or disable all request-time geolocation processing.

While usage analytics is enabled, RevenueCat also receives app/language/country, collection-setting and experiment attributes so purchases can be related to app use. When you turn usage analytics off in Settings, the app stops new client captures and requests clearing of analytics enrichment and its PostHog attribution ID, while retaining the disabled-setting marker. Synchronization is asynchronous. The app clears its saved analytics queue when you switch collection off and retries a pending cleanup before the SDK can start again. If cleanup fails, sending stays disabled. Requests already sent or in flight cannot be recalled; switching collection off does not erase records already stored by servers.

RevenueCat also forwards subscription events to PostHog for financial reporting. Legacy financial events without a recorded analytics choice may be included. This server path is separate from client usage collection; collection-setting metadata and server filtering update asynchronously. Essential Apple/RevenueCat purchase processing continues if usage analytics is off.

## Retention and your choices

The current PostHog event window is **12 months**; events beyond that window are removed at the next monthly cleanup. This is an event-retention setting, not a promise that every profile, support message or provider backup is erased at exactly 12 months. Contact us for access or erasure requests involving those records.

The app does not automatically expire your local history or settings. Individual sessions can be deleted in History; recent contractions can be cleared in the timer. The free three-day history display is not a deletion schedule. iCloud and other-device copies, temporary files, OS backups and reports you have shared must be considered separately. There is no complete erase-all-history action in the version covered here.

The app does not set an automatic expiry period for RevenueCat customer records. Purchase records support verification and restoration and may also be subject to the providers' obligations. Deleting a RevenueCat customer record does not cancel an Apple subscription, and restoring purchases can recreate synchronized transaction information. Manage or cancel subscriptions in [Apple subscription settings](https://apps.apple.com/account/subscriptions).

## Support and requests about your data

Email support with Baby Kick in the subject. Your email address and the information you choose to send are processed to answer you. Avoid sending health notes/reports, passwords, Apple credentials or full receipts unless a secure, necessary process has been agreed. Our legacy support website uses Formspree and Google Fonts; this dedicated support page uses direct email links instead of a form or remote fonts. Website hosting can process technical request data.

We retain support correspondence, contact details and any identifiers you provide for as long as needed to resolve your request, handle related follow-up, meet applicable legal obligations or establish, exercise or defend legal claims. When these purposes no longer require the information, we delete it or remove identifying details. You can request deletion of a support conversation by email. We review the request and explain any information that must be retained and why. There is no automatic mailbox expiry or fixed retention period promised here; the 12-month PostHog event window does not apply to support email.

For access, correction or deletion, state which records you mean: local/iCloud history, usage/financial analytics or a support conversation. In versions with **Copy support ID** in Settings, you can choose to copy the app-scoped identifier and include it in your request. It contains no health records. Copying does not send anything or change your analytics setting; the clipboard item is configured to stay on this device and expire after five minutes. Older versions may not provide this control; tell us if you cannot locate the identifier. We may need a minimal verification step before processing a request. Email alone does not reliably identify pseudonymous app records. We cannot ask for or access your Apple account credentials to remove private iCloud data.

Turning analytics off, deleting the app, deleting historical data and cancelling a subscription are separate actions. Depending on applicable law, you may also request restriction, object to processing, withdraw consent or complain to your relevant data protection authority. We explain the scope completed and any remaining technical or applicable legal limitations rather than promising that one action erases every copy.

## Changes and contact

We update this page when the app's processing changes and revise the date above. Privacy/support: [scofield665@gmail.com](mailto:scofield665@gmail.com?subject=Baby%20Kick%20Privacy).


[Privacy](https://ventskus-roman.github.io/policy/babykick-privacy) · [Support](https://ventskus-roman.github.io/policy/babykick-support) · [Terms](https://ventskus-roman.github.io/policy/babykick-terms)
