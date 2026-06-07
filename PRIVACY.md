# **ZeroTrace Privacy Policy**

**Effective date:** June 6, 2026

## 1. Overview

**ZeroTrace** is browser extension focused on privacy and quality of life during browsing.

ZeroTrace is built with local-first privacy architecture. It protects from web trackers and ads while limiting developer-side data visibility by keeping product behavior local in browser.

## 2. Two-layer privacy approach

ZeroTrace protects privacy in two ways:

- **Web-facing privacy** — blocks common ad and tracker activity at request level and reduces tracking-related page clutter.
- **Developer-facing privacy** — extension does not require account and keeps preferences in local browser storage.

ZeroTrace <u>does not</u> sell personal data and <u>does not</u> share personal data with data brokers.

## 3. Data ZeroTrace accesses for product behavior

To provide blocking and per-site controls, ZeroTrace may access browser data locally on your device:

- **Active tab and host context** — to apply popup actions to correct site
- **Network request metadata** — to apply request-level protection behavior
- **Extension settings data** — to keep your selected toggles and preferences

This access supports extension functionality only, in local browser context.

## 4. Local settings storage

ZeroTrace stores settings locally in browser extension storage, including:

- global protection toggles
- category toggles (ads, trackers, annoyances, social widgets)
- per-site pause and skip controls
- optional UI and notification preferences

Settings stay in your browser profile until you change them or remove extension.

## 5. No account required

ZeroTrace does not require account creation, sign-in, or profile setup to use core protection features.

## 6. Data sharing and selling

ZeroTrace <u>does not</u> sell personal data.

ZeroTrace <u>does not</u> share personal data with data brokers.

## 7. Permissions explanation

ZeroTrace may request permissions required for extension behavior:

- **`declarativeNetRequest`** — block ad and tracker requests before resources load
- **`storage`** — save user preferences locally
- **`scripting`** — apply page-level filtering behavior
- **`tabs`** — apply per-site controls to active host
- **`webRequest`** — support request-level runtime protection logic
- **`notifications`** — show optional user-facing notifications
- **`<all_urls>` host access** — allow protection on sites you visit

Permissions are used for stated product outcomes and user controls.

## 8. Updates to this policy

If privacy practices evolve, this policy will be updated with clear language and updated effective date.

## 9. Contact

For privacy questions, use project issue tracker:

- Issues: [GitHub Issues](https://github.com/ork89/ZeroTrace-public/issues)
