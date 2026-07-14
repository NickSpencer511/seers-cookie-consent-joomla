# Seers Cookie Consent Banner for Joomla!

AI-powered cookie consent and consent management platform (CMP) for Joomla!
GDPR, CCPA, LGPD, PECR and ePrivacy compliant — 150+ privacy laws, zero coding.

## Requirements

- Joomla 5.x or 6.x
- PHP 8.1+
- cURL extension enabled
- A free [Seers](https://seers.ai) account

## Installation

1. Download the latest `pkg_seerscookieconsent-x_x_x.zip` from [Releases](../../releases)
2. In Joomla admin: **System → Install → Extensions → Upload Package File**
3. Upload the zip
4. Go to **Components → Seers Cookie Consent**
5. Create your Seers account (or connect an existing one) — the banner goes live automatically

## Features

- AI cookie scanning and automatic categorisation (750,000+ cookie database)
- Real-time script blocking before consent — Google Analytics, GTM, Facebook Pixel, Hotjar and more
- Google Consent Mode v2, Microsoft Consent Mode, IAB TCF v2.2, Global Privacy Control
- AI region detection — correct banner per visitor's jurisdiction
- 28+ languages, auto-translated
- Granular categories: Necessary, Analytics, Marketing, Preferences
- Consent logging with timestamps, audit-ready and exportable
- Auto-generated cookie policy
- WCAG 2.1 AA accessible, lightweight

## What's in this package

| Extension | Type | Purpose |
|---|---|---|
| `com_seerscookieconsent` | Component | Admin dashboard — account, banner settings, reports |
| `plg_system_seerscookieconsent` | System plugin | Injects the consent banner script on the frontend |

## Changelog

### 2.0.1
- Fixed API endpoints to point to production
- Enabled SSL certificate verification on all outbound requests

### 2.0.0
- Rewritten for Joomla 5/6 with namespaced component architecture

## Support

- Documentation: https://seerssupport.zendesk.com/hc/en-us/categories/11055391902492-Cookie-Consent
- Contact: https://seers.ai/contact/

## License

GPL-2.0-or-later — see [LICENSE](LICENSE)
