# Bill-Calendar

Payoff Calendar is an iOS app for tracking one-time and recurring bill due dates, daily totals, and optional subscription management.



Persistence:
Local-only storage:
- Payoffs: `UserDefaults`
- Payoff backup payload: `UserDefaults`
- Subscription list: `UserDefaults`
- Removed recurring occurrences: `UserDefaults`
- Monthly recurring overrides: `UserDefaults`

Covered areas:
- recurrence and monthly total calculations
- current occurrence vs future occurrence deletion
- payment history aggregation
- backup restore behavior
- subscription sync candidate filtering and add flow
- App Store version comparison
- end-to-end UI flows for add, history, delete confirmation, recurring deletion, future-occurrence deletion, and mock subscription sync


Privacy Policy

# Payoff Calendar Privacy Policy

Effective Date: March 10, 2026

This Privacy Policy explains how `BUPARK LLC` ("Payoff Calendar," "we," "us," or "our") collects, uses, stores, and shares information when you use the Payoff Calendar mobile application and any related Plaid-powered subscription sync service (collectively, the "Service").

This policy is intended for publication with the Payoff Calendar app. Before publishing, replace the bracketed placeholders in this document with your actual legal entity name, contact email address, and, if desired, mailing address or website URL.

## 1. Scope

This Privacy Policy applies to:

- the Payoff Calendar iOS application;
- optional subscription-sync features powered by Plaid;
- related backend services used to create Plaid link tokens, exchange public tokens, and request recurring transaction data; and
- advertising and consent tooling used in the app.

This Privacy Policy does not apply to third-party services that have their own privacy policies, including Plaid and Google.

## 2. Information We Collect

The information we collect depends on how you use the Service.

### A. Information you enter directly

When you use Payoff Calendar without connecting a financial account, we may collect and store information that you enter into the app, including:

- payment or bill names;
- payment amounts;
- due dates or billing days;
- recurring frequency selections;
- paid/unpaid status;
- monthly amount overrides;
- subscription descriptions, billing dates, and estimated costs; and
- preferences or feature settings.

### B. Financial data you choose to share through Plaid

If you choose to connect a financial account through Plaid, we may receive or process information needed to identify recurring subscriptions and similar payment patterns, including:

- recurring transaction descriptions or merchant labels;
- recurring transaction dates;
- average or estimated recurring payment amounts;
- billing-day information derived from recurring transactions;
- Plaid access tokens or other connection tokens needed to complete requests; and
- limited account-connection metadata required to complete the sync flow.

We do not ask you to type your online banking username or password directly into Payoff Calendar. Financial account credential collection and connection flows are handled by Plaid and participating financial institutions.

### C. Device, app, and diagnostic information

When you use the Service, we or our service providers may automatically collect certain technical information, such as:

- device type, operating system, and app version;
- IP address and approximate location derived from IP address;
- request timestamps and network response information;
- crash, error, and troubleshooting data; and
- advertising identifiers, consent signals, and ad interaction data where applicable.

### D. Consent and advertising information

If the app shows ads, we and our advertising partners may process:

- consent choices you make through the consent flow;
- device and advertising identifiers;
- ad request, impression, and interaction data; and
- limited technical data needed to deliver, measure, and limit ads.

## 3. How We Use Information

We use information we collect to:

- operate the core payment calendar features;
- save and restore your bill, payoff, and subscription data;
- calculate due dates, recurring schedules, totals, and payment history;
- detect and present recurring subscription candidates from Plaid-connected financial data;
- deduplicate and import selected subscription candidates into your calendar;
- operate, secure, debug, and improve the Service;
- display ads and manage consent choices where ads are enabled;
- comply with legal obligations, enforce our terms, and protect against misuse, fraud, or security incidents; and
- respond to support or privacy requests.

We do not use Plaid-connected bank transaction data to create personalized financial profiles for sale to data brokers, and we do not use that data to target users based on sensitive financial characteristics.

## 4. How We Store Information

### A. Local app storage

Payoff Calendar currently stores much of your app data locally on your device, including:

- bill and payment entries;
- backup copies of saved payoff data;
- subscription items you add or accept;
- removed recurring-occurrence markers;
- monthly recurring overrides; and
- in some configurations, a locally stored Plaid access token.

### B. Backend processing for Plaid

If you use Plaid sync, Payoff Calendar may send a Plaid access token and related sync requests to a backend service controlled by us so the backend can request recurring transaction data from Plaid and return subscription candidates to the app.

Depending on your production setup, backend logs and request records may be retained for security, debugging, abuse prevention, and legal compliance.

## 5. How We Share Information

We may share information in the following circumstances:

### A. Plaid

If you use the Plaid sync feature, financial connection and transaction-related data may be collected, processed, or shared by Plaid as needed to connect your account and provide recurring transaction data. Plaid acts under its own privacy policy and consumer controls.

### B. Advertising and consent providers

If ads are enabled, information may be shared with Google AdMob, Google User Messaging Platform, and related advertising or consent partners to support:

- consent management;
- ad delivery;
- ad measurement;
- fraud prevention; and
- compliance with applicable advertising rules.

### C. Service providers

We may share information with vendors or infrastructure providers that help us host backend systems, secure the Service, diagnose issues, or provide support.

### D. Legal and safety reasons

We may disclose information if we believe disclosure is reasonably necessary to:

- comply with law, regulation, subpoena, court order, or lawful request;
- protect the rights, safety, and property of users, the public, or our business;
- detect, investigate, or prevent fraud, abuse, or security issues; or
- enforce our agreements and policies.

### E. Business transfer

If we are involved in a merger, acquisition, financing, sale of assets, or similar transaction, information may be transferred as part of that transaction, subject to applicable law.

## 6. Data Retention

We retain information for as long as reasonably necessary for the purposes described in this Privacy Policy.

In practice:

- locally stored app data remains on your device until you delete it, remove the app, or reset app data;
- Plaid-related connection data may remain until the connection is removed, the app is deleted, or the data is replaced or cleared; and
- backend logs, if any, may be retained for a limited period for security, debugging, and compliance purposes.

We may retain information longer if required by law, needed to resolve disputes, or necessary to protect the Service and our users.

## 7. Your Choices and Controls

Depending on how you use the Service, you may be able to:

- add, edit, or delete locally stored bill and subscription data in the app;
- stop using Plaid sync at any time;
- revoke or manage financial-data permissions through Plaid or your financial institution;
- manage ad-related consent choices where a consent flow is shown;
- limit ad tracking through your device settings; and
- request access to, correction of, or deletion of information we control, subject to applicable law.

If you connected accounts through Plaid, you may also be able to manage connected accounts and deletion requests through Plaid Portal or by contacting Plaid directly.

## 8. Third-Party Services

Payoff Calendar may link to or rely on third-party services. Their handling of your information is governed by their own terms and privacy policies. Key third parties may include:

- Plaid: [https://plaid.com/legal/](https://plaid.com/legal/)
- Google Privacy Policy: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- Google AdMob / consent documentation: [https://developers.google.com/admob/](https://developers.google.com/admob/)

## 9. Security

We use reasonable administrative, technical, and organizational safeguards designed to protect information under our control. No method of transmission over the internet, mobile network, or local device storage is completely secure, and we cannot guarantee absolute security.

Because financial data is sensitive, you should:

- keep your device protected;
- use current iOS and app updates;
- avoid sharing access to your unlocked device; and
- disconnect financial connections you no longer use.

## 10. Children's Privacy

Payoff Calendar is not directed to children under 18, and we do not knowingly collect personal information from children under 18. If you believe a child has provided personal information through the Service, contact us and we will review the request.

## 11. International Transfers

If third-party providers or backend infrastructure process information in countries other than your own, your information may be transferred to and processed in those countries, subject to applicable law.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the effective date above and may provide additional notice where required by law.

## 13. Contact Us

If you have questions, privacy requests, or complaints, contact:

- Legal Entity: `BUPARK LLC`
- Contact Email: `bumjin509@gmail.com`
- Mailing Address: `13120 NE 85TH ST, UNIT 320, KIRKLAND 98033, WA, USA`
- Website: `https://github.com/bjpark4002/Bill-Calendar/tree/main`

## 14. California and Other U.S. State Privacy Rights

If you are a resident of California or another U.S. state with applicable privacy laws, you may have rights such as:

- the right to know what personal information we collect, use, disclose, or retain;
- the right to request deletion of personal information we hold about you, subject to exceptions;
- the right to request correction of inaccurate personal information;
- the right to access or obtain a portable copy of certain information; and
- the right not to be discriminated against for exercising applicable privacy rights.

To exercise rights that apply to us, contact us using the information above. We may need to verify your identity before responding.

## 15. Important Implementation Note

This Privacy Policy is based on the current Payoff Calendar implementation and planned Plaid integration reflected in the project as of March 10, 2026, including:

- local storage of payment and subscription data;
- optional Plaid-powered recurring-transaction sync;
- backend token exchange and recurring-subscription retrieval;
- ad delivery through Google AdMob; and
- consent handling through Google's User Messaging Platform.
