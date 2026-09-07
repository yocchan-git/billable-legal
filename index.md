# Privacy Policy — Billable v1.3.0

**Last updated:** 2026-09-06

Billable — Time Tracker & Invoicing ("Billable") is designed to keep work and invoicing data on the user's device. Billable has no Billable-operated cloud account or server for that data.

## Data stored locally on the device

Billable stores the following data in the browser's extension storage on the user's device:

- Client details: names, addresses, email addresses, hourly rates, currencies, and billing cutoffs. Issuer details: business/name, address, email address, phone number, and tax identifier.
- Time records and saved tasks: client association, notes, timestamps, idle-time choices, and billing association.
- Invoice data: draft and confirmed invoice details, invoice numbers, dates, issuer tax identifiers, global payment instructions and terms, notes, and status/history.
- Recipient information entered for fixed invoice message preparation.
- Product data needed to operate locally, including the number of invoice confirmations used and cached subscription status.

This local data is not sent to Billable servers because Billable does not operate a server for it. Where supported by the browser, Billable restricts `storage.local` to trusted extension contexts. This is a browser access control and is not encryption; users should protect access to their device and browser profile.

## Email assistance

Billable does not send email, connect to an email inbox, or attach files. Only after an explicit user action to create an email does Billable pass the reviewed recipient, subject, and plain-text body to the operating system or browser's configured mail application through a mailto link. Users may instead copy the subject or body themselves.

The global billing-default payment-instructions field is free text. Billable warns users not to enter card numbers, passwords, private keys, or other authentication secrets in it.

## Payments and subscriptions

Billable offers an optional Billable Pro subscription. ExtensionPay and its payment processor Stripe handle payment and subscription-management flows. When a user checks subscription status or opens a payment or subscription-management page, ExtensionPay may process purchase-related account information, such as the email address used for purchase, license status, and subscription status, under its own policy: [ExtensionPay Privacy Policy](https://extensionpay.com/privacy).

Billable does not receive or store payment-card details. Billable work and invoice data are not sent to ExtensionPay or Stripe.

## What Billable does not do

- It does not collect analytics, telemetry, advertising identifiers, cookies, fingerprinting data, browsing history, or ordinary website content.
- It does not sell or transfer work or invoice data for advertising, analytics, credit decisions, or unrelated purposes.
- It does not provide cloud synchronization, an account service, automated email sending, or remote code execution.
- Core local features continue to work offline.

## Permissions

Billable requests these permissions only:

- **storage** — saves the local work, invoice, backup, and cached license data described above.
- **idle** — detects inactivity or screen lock while a timer is running so the user can choose whether to deduct away time.
- **alarms** — refreshes the running-timer toolbar badge approximately once a minute.

Billable declares no Chrome host permissions. Its existing ExtensionPay payment-confirmation content script is limited to `https://extensionpay.com/*`; it does not read ordinary browsing content or browsing history.

## Retention and user control

Invoice history is not automatically deleted. Users can export local JSON backups. Clearing browser data, uninstalling the extension, losing a device, or losing a browser profile can remove locally stored data; users are responsible for keeping backups.

## Contact and changes

Questions about this policy: **billable.extension@gmail.com**. Material changes will be reflected here and identified by the "Last updated" date above.
