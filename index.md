---
title: Privacy Policy – Renewly
---

# Privacy Policy – Renewly

Last updated: August 25, 2026

This privacy policy applies to the Android app **Renewly**
(package ID: `com.renewly.subscriptions`).

## 1. Data Controller

Robert Peringer
Ittlinger Hauptstraße 17, Straubing, Germany
Email: FsNaviVfr@gmail.com

## 2. Summary

Renewly is a subscription renewal tracker. It stores everything you
enter (subscription name, price, billing cycle, next renewal date)
**exclusively on your device**, in a local database. There is no
user account, no registration, and no server/backend of our own. The
app itself never transmits your subscription data to the developer
or any third party.

## 3. What Data Is Processed?

### 3.1 Subscription Data You Enter

Name, price, currency, billing cycle, and renewal date for each
subscription you add are stored locally on your device only. This
data is used to display your subscriptions and to schedule local
reminder notifications before a renewal date. It is never uploaded
to a server operated by the developer.

### 3.2 Google Play Billing

Paid premium features are purchased through Google Play Billing.
Payment details (card numbers, billing address, etc.) are processed
entirely by Google, which acts as an independent data controller for
that processing — the developer only receives a purchase
confirmation (order ID / purchase token), never payment details. See
Google's Privacy Policy: https://policies.google.com/privacy

### 3.3 Optional Google Drive Backup

If you choose to use the optional backup feature, the app connects
directly to your own Google Drive account via Google-authorized
OAuth. The backup file is stored in your own Drive storage; the
developer has no access to it.

### 3.4 Currency Conversion (Exchange Rates)

If you use the Insights screen to display totals in a currency other
than the one a subscription was entered in, the app fetches current
exchange rates from the free, keyless Frankfurter API
(`api.frankfurter.app`, based on European Central Bank reference
rates) over the internet. The purpose of this request is solely to
convert amounts between currencies for display; no subscription data
or other personal data is included in or derived from this request,
only the currency codes needed to look up a rate. As with any network
request, your device's IP address is technically visible to the
Frankfurter service as the operator of that API, independent of the
developer. Fetched rates are cached locally on your device for 24
hours to minimize how often this request is made.

## 4. Permissions

The app requests the following permission:

| Permission | Purpose |
|---|---|
| **Notifications** (`android.permission.POST_NOTIFICATIONS`) | Used to remind you before a subscription renews. Reminders are scheduled entirely on your device. |
| **Internet** (`android.permission.INTERNET`) | Used for Google Play Billing, the optional Google Drive backup, and fetching exchange rates for currency conversion (see 3.2–3.4). |

No other permissions are requested.

## 5. Third-Party Services

The app uses **Google Play Billing** to process premium purchases,
and, only if you opt in, the **Google Drive API** for backup/restore.
It also uses the **Frankfurter API** to fetch exchange rates for
currency conversion in the Insights screen (see 3.4). No advertising,
tracking, or analytics/statistics SDKs are used (e.g. no Google
Analytics, Firebase Analytics, or similar).

## 6. Storage and Disclosure

Subscription data you enter is stored only in a local database on
your device. The app does not operate its own server and does not
disclose your subscription data to third parties.

## 7. Rights of Data Subjects

Under the GDPR, you generally have the right to access (Art. 15),
rectification (Art. 16), erasure (Art. 17), restriction of
processing (Art. 18), data portability (Art. 20), and objection
(Art. 21). Since Renewly does not store or transmit your subscription
data on the developer's side, these rights primarily apply to the
data you manage directly on your device — you can edit or delete it
in the app at any time, or uninstall the app. You also have the
right to lodge a complaint with a data protection supervisory
authority.

## 8. Legal Basis

Local storage and processing of the data you enter, to provide the
app's core function (subscription tracking and renewal reminders),
is based on Art. 6(1)(b) GDPR (performance of a contract, or
pre-contractual measures taken at the request of the user through
their use of the app).

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
