# Privacy Policy — CoatTail

_Last updated: 2026-05-06_

CoatTail is built privacy-first. Here is exactly what happens with your data.

## What stays on your device

Your watchlist, copied trades, custom alerts, price alerts, notes, collections, and settings live entirely on your iPhone (and on your iCloud private database if you opt in to sync via Settings → Appearance & data → iCloud sync).

CoatTail does not have user accounts and does not run any server that stores your activity.

## What goes over the network

The app talks directly to public providers from your device:

- **SEC EDGAR** (sec.gov) — for Form 4 (insider trading) and 13F (fund holdings) filings.
- **Quiver Quantitative** — for U.S. Congress trade disclosures via their public beta endpoint.
- **Blockchair** — for the wallet addresses you choose to watch (Ethereum, Bitcoin, Litecoin, Dogecoin).
- **Yahoo Finance** — for stock prices and headline news (RSS).

These services see your IP address as a side effect of an HTTPS request, exactly the same way they would if you opened their websites in Safari. CoatTail does not send them any personally identifiable information about you.

## Subscription processing

Subscription purchases are handled entirely by Apple's StoreKit framework. CoatTail never sees your payment details, billing address, or Apple ID.

If you subscribe to Premium and use the AI take feature, the app sends a signed Apple StoreKit transaction (so we can verify your entitlement) along with a short prompt — the ticker symbol and up to eight names of public entities (politicians, funds, or insiders) trading it — to our backend. The backend forwards the prompt to Anthropic's API and returns the response. The prompt and response are not associated with you, are not retained beyond the immediate request, and are not used for analytics or model training.

## Notifications

All notifications (per-event, daily digest, NEW position alerts, custom alert rules, price alerts) are scheduled locally on your device. CoatTail uses no Apple Push Notification Service (APNs) server.

## Crash reports & analytics

CoatTail does not include any third-party analytics SDK, advertising tracker, or crash reporting service. Apple may collect anonymous crash reports if you have crash reporting enabled at the iOS level — those go to Apple, not to us.

## Data shared with third parties

None.

## Children

CoatTail is not directed at children under 13 and does not knowingly collect data from any user.

## Your choices

- **Stop using a data source:** remove the watched entity (politician/wallet/fund/ticker) from your Watchlist, or disable the source's notifications in Settings.
- **Erase activity cache:** Settings → Data → "Clear all activity & cache."
- **Cancel subscription:** Settings → Premium → Manage, or via Apple's Subscriptions screen.
- **Disable iCloud sync:** Settings → Appearance & data → iCloud sync toggle.

## Contact

Questions or requests: **{{SUPPORT_EMAIL}}**

---

_This policy applies to CoatTail v0.1 and later. We will revise this document if anything changes; the current version is always available in-app at Settings → Privacy policy._
