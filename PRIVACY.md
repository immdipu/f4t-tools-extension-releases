# Privacy Policy — F4T Tools

**Last updated:** 4 August 2026

F4T Tools is an unofficial browser extension that shows extra profile and activity
information for [Free4Talk](https://www.free4talk.com) users. It is not affiliated
with, endorsed by, or connected to Free4Talk.

## What the extension stores

Everything below is stored by Chrome on your own device (`chrome.storage`). If you
have Chrome Sync enabled, Google syncs the settings to your other signed-in Chrome
browsers. None of it is sent to us except as described in the next section.

| Stored | Why |
| --- | --- |
| Your API key | Authenticates your requests to the F4T Tools API |
| On/off switch | Remembers whether the extension is enabled |
| Display preferences | Remembers your avatar display choices |
| Update information | Only in the version distributed outside the Chrome Web Store |

## What the extension sends

When you view a Free4Talk user's profile, the extension requests that user's public
activity summary from `https://tracker.free4talk.me`. The request contains:

- the **Free4Talk user ID** of the profile you are viewing, and
- **your API key**, so the server knows the request is authorised.

That is the only data transmitted, and it is sent only to the address above. The
extension makes no other network requests, apart from loading user avatar images
directly from Free4Talk's own image servers.

## What the extension does not do

- It does not collect your name, email address, location, or browsing history.
- It does not read, record, or transmit any conversation, chat message, or audio.
- It does not track you across websites — it runs only on `free4talk.com`.
- It does not sell or share your data with third parties.
- It does not use your data for advertising, or for any purpose unrelated to
  showing you the profile information you requested.
- It contains no analytics and no third-party tracking code.

## Where it runs

The extension only has permission to run on `free4talk.com`. It cannot see or
interact with any other website you visit.

## Data retention

Your API key and preferences stay on your device until you remove them, which you
can do at any time by clearing the key in the extension popup or by uninstalling
the extension. For how long the F4T Tools API retains request data, contact us at
the address below.

## Children

The extension is not directed at children under 13.

## Changes

If this policy changes, the "Last updated" date above will change with it.

## Contact

Questions about this policy: **info@free4talk.me**
