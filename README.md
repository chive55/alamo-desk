# Alamo Desk

Operator program for a San Antonio done-for-you front desk.

Missed-call text-back, Google review drafts, appointment reminders. Nathan Butcher builds the live pipe (HighLevel / number / 10DLC). This repo is the brain you run in a walkthrough and on the weekly audit grind.

## Run it

Open `index.html` in a browser, or:

https://htmlpreview.github.io/?https://github.com/chive55/alamo-desk/blob/main/index.html

Nothing is sent to a carrier. Audits and intake stay in localStorage on that browser.

## What each tab is

| Tab | Job |
| --- | --- |
| Live miss demo | 12-minute sales walkthrough. Missed call → two-turn text → handoff. HVAC, dental, shop. After-hours toggle. |
| Review engine | Draft + auto/hold. Dental PHI words never get echoed. 1–3 stars wait for the owner. |
| Reminders | Confirm / 24h / 2h copy with STOP. |
| Audit log | The 25-call week. Voicemail = hot. CSV export. |
| Client intake | 10DLC kickoff fields. |
| Monthly report | The one-pager that keeps the retainer. |
| Rules / GHL map | How to wire the same logic in HighLevel. |

## Price (do not freelance this in the UI)

- Catch $397/mo + $297 setup
- Core $597/mo + $497 setup (default close)
- Full Desk $797/mo + $797 setup

## This is not the carrier

Live SMS still needs:

1. Client 10DLC brand + campaign
2. Call forward on unanswered
3. HighLevel (or OpenPhone + Make) using the templates in the demo
4. GBP connection with an approval queue

Do not cold-text scraped Maps numbers.

## License

Private use for Alamo Desk / Nathan Butcher. Not a public SaaS.
