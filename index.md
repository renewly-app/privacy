---
title: Privacy Policy – Renewly
---

# Privacy Policy – Renewly

[Terms of Use](terms.md) · [Impressum / Legal Notice](impressum.md) · [Deutsch](datenschutz.md)

Last updated: August 31, 2026

This privacy policy applies to the Android app **Renewly**
(package ID: `com.renewly.subscriptions`).

## 1. Data Controller

Robert Peringer  
Ittlinger Hauptstraße 17  
94315 Straubing  
Germany  

Email: FsNaviVfr@gmail.com

## 2. Summary

Renewly is a subscription renewal tracker. The subscription data you
enter (subscription name, price, billing cycle, next renewal date) is
stored in a local database on your device. There is no user account,
no registration, and no server/backend of our own. The app itself
never transmits your subscription data to the developer or any third
party.

Some functions involve third-party services: Google Play Billing is
used to process premium purchases, and the Frankfurter API may be
contacted directly from your device to fetch exchange rates when you
use the currency conversion feature. No advertising, analytics, or
tracking services are used.

If Android's Auto Backup feature is enabled on your device, the app's
local database may be included in a backup associated with your
Google Account. The developer has no access to such backups (see
Section 5).

## 3. What Data Is Processed?

### 3.1 Subscription Data You Enter

Name, price, currency, billing cycle, and renewal date for each
subscription you add are stored in the app's local database on your
device. This data is used to display your subscriptions and to
schedule local reminder notifications before a renewal date. It is
never uploaded to a server operated by the developer.

### 3.2 Google Play Billing

Paid premium features are purchased through Google Play Billing.
Payment details (card numbers, billing address, etc.) are processed
entirely by Google, which acts as an independent data controller for
that processing — Renewly never sees or receives your payment
details.

To determine whether premium features should be unlocked, the app
queries your purchase status directly from Google Play each time it
starts. This purchase information is not transmitted to the developer
— there is no developer-operated server to receive it — and is not
stored on your device either; it is only held in memory for the
current app session. See
[Google's Privacy Policy](https://policies.google.com/privacy).

### 3.3 Currency Conversion (Exchange Rates)

If you use the Insights screen to display totals in a currency other
than the one a subscription was entered in, the app fetches current
exchange rates from the free, keyless Frankfurter API
(`api.frankfurter.app`, based on European Central Bank reference
rates) over the internet. The purpose of this request is solely to
convert amounts between currencies for display; no subscription data
or other personal data is included in or derived from this request,
only the currency codes needed to look up a rate. The request is sent
directly from your device to the Frankfurter API; the developer does
not operate or route this request through its own server, does not
receive this request, and the app does not store your IP address. As
with any network request, your device's IP address is technically
visible to the Frankfurter service and any technical infrastructure
providers (for example hosting or content-delivery services) it
relies on to operate that API. How long that connection data is
retained is determined by those services' own policies, not by the
developer, who has no control over it. Fetched rates are cached
locally on your device for 24 hours to minimize how often this
request is made.

## 4. Permissions and Network Access

The app declares and uses the following Android permissions:

| Permission | Purpose |
|---|---|
| **Notifications** (`android.permission.POST_NOTIFICATIONS`) | Used to remind you before a subscription renews. Reminders are scheduled entirely on your device. On Android 13+, this requires your explicit consent, which the OS will ask for. |
| **Internet** (`android.permission.INTERNET`) | Used for Google Play Billing and fetching exchange rates for currency conversion (see 3.2–3.3). This is a standard permission automatically granted at install time, not something you are separately prompted to approve. |

The app does not request access to your contacts, location, camera,
microphone, photos, or other sensitive device data.

## 5. Third-Party Services

The app uses **Google Play Billing** to process premium purchases,
and the **Frankfurter API** to fetch exchange rates for currency
conversion in the Insights screen (see 3.3). No advertising,
tracking, or analytics/statistics SDKs are used (e.g. no Google
Analytics, Firebase Analytics, or similar).

The app also supports Android's built-in Auto Backup, which — if
enabled on your device — automatically backs up the app's local
database as part of the standard Android OS backup service. The
backup is handled by Android and associated with your Google Account;
the developer does not operate this backup service and has no access
to its contents. See Google's documentation on
[Android Auto Backup](https://developer.android.com/identity/data/autobackup)
for details, and Android's device backup settings to control it.

## 6. Storage and Disclosure

Subscription data you enter is stored in the app's local database on
your device and remains there until you edit or delete it, or delete
the app's local data. The developer does not operate its own server
and does not receive or disclose this data to third parties.

If Android Auto Backup is enabled for Renewly, this local database may
also be included in a backup associated with your Google Account, as
described in Section 5.

## 7. Rights of Data Subjects

Under the GDPR, you generally have the right to access (Art. 15),
rectification (Art. 16), erasure (Art. 17), and restriction of
processing (Art. 18). Where the respective legal requirements are
met, you may also have the right to data portability (Art. 20 GDPR)
and the right to object to processing based on legitimate interests
(Art. 21 GDPR).

Since Renewly does not store or transmit your subscription data on
the developer's side, most of these rights are already effectively in
your own hands: you can view, edit, or delete your subscription data
directly in the app at any time. This is not the same as formally
exercising a right under the GDPR, however. To formally invoke any of
the above rights — for example regarding the limited technical data
described in Sections 3.2–3.3 — please contact the developer using
the details in Section 10.

Deleting the app or its local data removes this data from your
device. If Android Auto Backup is enabled, a backup may remain
associated with your Google Account until it is managed or deleted
through Android's backup settings or your Google Account — the
developer cannot delete this on your behalf, as it has no access to
it (see Section 5).

You also have the right to lodge a complaint with a data protection
supervisory authority.

## 8. Legal Basis

Where the GDPR applies, different processing activities described in
this policy rely on different legal bases:

- Processing of the subscription data you enter (Section 3.1) is
  based on Art. 6(1)(b) GDPR, insofar as it is necessary to provide
  the subscription tracking and renewal reminder functionality you
  requested, or otherwise on Art. 6(1)(f) GDPR (legitimate interest
  in operating the app's core functionality).
- Currency-conversion requests to the Frankfurter API (Section 3.3)
  are based on Art. 6(1)(f) GDPR — the developer's legitimate
  interest in providing exchange-rate conversion without operating a
  currency-rate server of its own.
- Processing related to Google Play Billing (Section 3.2) is carried
  out by Google as an independent controller under its own legal
  basis; see [Google's Privacy Policy](https://policies.google.com/privacy)
  for details.

## 9. Changes to This Privacy Policy

This privacy policy may be updated as needed, for example due to
changes in the app's functionality or legal requirements. The
current version is always available via the link provided in the
app and in the Play Store listing.

## 10. Contact

For privacy-related questions, please contact:
FsNaviVfr@gmail.com

## 11. Trademarks

Renewly lets you track subscriptions to third-party services (for
example Netflix, Spotify, or similar). Any product names, logos, and
brands referenced or selectable within the app are the property of
their respective owners. Company, product, and service names used in
the app are for identification purposes only and do not imply any
affiliation, sponsorship, or endorsement by those companies. You are
always free to enter a custom subscription name instead of choosing
from the predefined list.
