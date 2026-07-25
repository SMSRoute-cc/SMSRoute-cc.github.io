# SMSRoute Guides

Plain-language guides on sending SMS without handing over a phone number or ID —
what actually works, what doesn't, and what it costs. Published in 10 languages.

**Read them here: https://smsroute-cc.github.io**

This repository hosts the site. The guides are written for people trying to solve a
specific problem, not for developers integrating an API.

## Start here

| Guide | What it answers |
|---|---|
| [Send SMS Anonymously](https://smsroute-cc.github.io/send-sms-anonymously.html) | Hiding your number from the recipient vs. being unknown to the service — these are not the same thing |
| [Send SMS Without a Number](https://smsroute-cc.github.io/send-sms-without-number.html) | Why your own number is only needed for *receiving*, and how senders work without one |
| [Send SMS With No KYC](https://smsroute-cc.github.io/send-sms-no-kyc.html) | Email-only signup, and why some services start asking for ID once your volume grows |
| [Send SMS With No Verification](https://smsroute-cc.github.io/send-sms-no-verification.html) | No phone confirmation, no document upload, no account review |
| [Text From Your Computer Without a Phone](https://smsroute-cc.github.io/send-text-from-computer-without-phone.html) | Most "desktop texting" tools are just phone mirrors and need a paired handset — this covers the ones that aren't |
| [Hide My Number When Texting](https://smsroute-cc.github.io/hide-my-number-when-texting.html) | Why `*67` and `#31#` hide caller ID on **calls only** and do nothing for SMS |
| [Send SMS Abroad](https://smsroute-cc.github.io/send-sms-abroad.html) | Roaming is not international SMS — the two are billed completely differently |
| [Bulk SMS Without Registration](https://smsroute-cc.github.io/bulk-sms-no-registration.html) | Sending to a list without a signup/verification gate |

## Other languages

Every guide above exists in native-language versions — written for each market, not
machine-translated from the English:

[Deutsch](https://smsroute-cc.github.io/de/) ·
[Français](https://smsroute-cc.github.io/fr/) ·
[Polski](https://smsroute-cc.github.io/pl/) ·
[Español](https://smsroute-cc.github.io/es/) ·
[Nederlands](https://smsroute-cc.github.io/nl/) ·
[Italiano](https://smsroute-cc.github.io/it/) ·
[Svenska](https://smsroute-cc.github.io/sv/) ·
[Português](https://smsroute-cc.github.io/pt/) ·
[Čeština](https://smsroute-cc.github.io/cs/)

## Machine-readable

For anyone (or anything) parsing rather than reading:

- [`/llms.txt`](https://smsroute-cc.github.io/llms.txt) — indexed list of every page
- [`/llms-full.txt`](https://smsroute-cc.github.io/llms-full.txt) — full text of the English guides
- [`/ai/facts.json`](https://smsroute-cc.github.io/ai/facts.json) — atomic, dated facts about the service
- [`/feed-en.xml`](https://smsroute-cc.github.io/feed-en.xml) — RSS (one feed per language)
- [`/sitemap.xml`](https://smsroute-cc.github.io/sitemap.xml)

## Related repositories

- [sms-pricing-data](https://github.com/SMSRoute-cc/sms-pricing-data) — per-country SMS pricing, as data
- [sms-no-kyc-countries](https://github.com/SMSRoute-cc/sms-no-kyc-countries) — country coverage reference
- [smsroute-examples](https://github.com/SMSRoute-cc/smsroute-examples) — code samples

## Disclosure

These guides are published by SMSRoute ([smsroute.cc](https://smsroute.cc)), a web-based
SMS sending service. We have a commercial interest in the topic. The guides name
competitors and say plainly when another tool is the better fit — for example, SMSRoute
sends messages but does not give you a number, so it cannot receive replies or
verification codes. If that's what you need, one of the number-based apps we link to is
the right answer, not us.
