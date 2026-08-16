# Privacy Policy — Billable

**Last updated:** 2026-08-16

**Billable — Time Tracker & Invoicing** ("the extension") is designed to
keep your work data on your device. It handles the local data described below
and communicates with ExtensionPay and Stripe only for optional payment and
subscription features.

## What the extension stores

The extension stores the following data **locally, on your device**, using
the browser's built-in extension storage APIs. This data is never sent to
us or any third party:

- Your clients (name, hourly rate, currency, billing cutoff), saved tasks,
  and tracked time entries
  (client, note, start/end time, any idle time you chose to deduct,
  whether it's been billed)
- Invoicing settings (your business name, tax rate, invoice numbering),
  generated invoices, and invoice history
- Cached Billable Pro license status and the number of free invoice
  generations used
- Install date (stored locally; not transmitted)

## What we don't do

- We do not collect analytics, usage tracking, or telemetry.
- We do not use cookies, fingerprinting, or any tracking identifiers.
- We do not sell user data or transfer it for advertising, analytics,
  credit decisions, or unrelated purposes.
- We do not send your clients, saved tasks, time entries, rates, notes,
  invoice details, or generated documents over the network. Time tracking
  and access to your locally stored work data continue to work offline.

## Payments

Time tracking, editing, and data exports are free. After three free invoice
generations, unlimited invoicing is available through the optional Billable
Pro subscription.

Payments and subscription status are handled by
[ExtensionPay](https://extensionpay.com), a third-party payment service
for browser extensions, together with its payment processor Stripe. When the
extension checks your Pro status or opens a payment or subscription-management
page, it communicates with ExtensionPay. ExtensionPay may process the email
address used to purchase or restore access and the associated license and
subscription status. Its [privacy policy](https://extensionpay.com/privacy)
governs that processing.

Card and billing details are entered on Stripe-hosted pages and processed by
Stripe. We never receive or store your card number or other payment-card
credentials. Your locally stored Billable work data is not sent to
ExtensionPay or Stripe.

## Permissions

The extension requests only three permissions:

- **storage** — to save your clients, time entries, and settings locally
- **idle** — to detect when you step away while a timer is running, so
  you can choose to deduct that time
- **alarms** — to refresh the toolbar badge about once a minute while a
  timer is running

It does not access ordinary websites you visit. A narrowly scoped content
script runs only on `https://extensionpay.com/*` to relay payment or
restored-access confirmation to the extension. It does not collect that
page's content or your browsing history.

## Contact

Questions about this policy: **billable.extension@gmail.com**

## Changes

We'll update the "Last updated" date above if this policy changes.
