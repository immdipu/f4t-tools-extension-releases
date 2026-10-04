# Privacy Policy — F4T Tools

**Last updated:** 4 October 2026

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
| Welcome message | Your welcome and welcome-back texts, whether it's turned on, and the welcome-back delay |
| Saved Chats (Pro) | Chat history of rooms you visit, so you can browse it later. Stored only on your device, in your browser's storage for free4talk.com. Never transmitted anywhere. You can delete any saved conversation in the panel, and there is a 200-room cap after which the oldest is removed. |
| DM history (Pro) | Your direct messages with friends, as Free4Talk loads them, so they stay visible after Free4Talk deletes them (it keeps only the last 7 days). Stored only on your device, in your browser's storage for free4talk.com. Never transmitted anywhere. |
| Spotify Client ID (Pro) | The ID of the Spotify app you create during setup, so you only enter it once |
| Spotify sign-in tokens (Pro) | Keep you connected to Spotify between sessions, so you don't have to sign in every time. Stored only on your device. |
| Spotify playlist cache (Pro) | A local copy of your playlists and their tracks so the panel opens instantly |
| YouTube remote link (Pro) | Which YouTube tab is connected to which room tab, while connected. Kept only for the current browser session and removed when you disconnect. |
| YouTube remote card (Pro) | Where you left the card on the page, whether it's minimized, and your queue (the videos' IDs, titles and channels) |
| Skip non-music parts | Whether it's turned on |
| Update information | Only in the version distributed outside the Chrome Web Store |

## What the extension sends

When you view a Free4Talk user's profile, the extension requests that user's public
activity summary from `https://tracker.free4talk.me`. The request contains:

- the **Free4Talk user ID** of the profile you are viewing, and
- **your API key**, so the server knows the request is authorised.

The same API key is also used to check your subscription level, which unlocks the
Pro features.

If you connect the **Spotify Player** (a Pro feature), the extension talks directly
to Spotify (`accounts.spotify.com` and `api.spotify.com`) to sign you in and list
your playlists. Those requests carry only your own Spotify tokens and go straight
from your browser to Spotify — never through our servers. We never see your Spotify
account, password, or playlists. Playing a track uses Free4Talk's own built-in
YouTube player, exactly as if you had searched for the video yourself.

If you connect a **YouTube tab** to your room (a Pro feature), you first allow the
extension to access `www.youtube.com`. It then runs on YouTube but acts only in the
tab you connected: it reads which videos you open or add to your queue there, looks
up their titles and channels from YouTube's public oEmbed endpoint, and hands them to
your Free4Talk room's player — exactly as if you had searched for them yourself. Other
YouTube tabs are left alone, nothing about your YouTube account or history is read,
and nothing goes to our servers. You can remove the access at any time in Chrome's
extension settings.

If you turn on **Skip non-music parts**, the extension asks SponsorBlock
(`sponsor.ajay.app`) which parts of the videos you start in a room are not music. To
keep the video private, it sends only the first 4 characters of a hash of the video's
ID and picks the right video out of the handful SponsorBlock returns; SponsorBlock
never learns which video you're playing. Nothing about you is sent.

If you turn on **Welcome message**, the extension posts your message into the room's
chat through Free4Talk itself, from your account, when someone joins — exactly as if
you had typed it. It goes only to Free4Talk, like any chat message you send.

Beyond that, the extension's only other network activity is loading images: user
avatars from Free4Talk's image servers, album art from Spotify's image servers, and
video thumbnails from YouTube's image servers.

## What the extension does not do

- It does not collect your name, email address, location, or browsing history.
- It does not transmit any conversation, chat message, or audio anywhere (the
  welcome message you choose to post goes to Free4Talk like any chat message). Saved
  Chats and DM history (if you have Pro) keep room chats and your direct messages on
  your own device only — they never leave your browser.
- It does not track you across websites — it runs on `free4talk.com`, and on
  `www.youtube.com` only if you allow it for the YouTube remote.
- It does not sell or share your data with third parties.
- It does not use your data for advertising, or for any purpose unrelated to
  showing you the profile information you requested.
- It contains no analytics and no third-party tracking code.

## Where it runs

The extension has permission to run on `free4talk.com`. If you connect a YouTube tab
to your room, Chrome asks whether it may also run on `www.youtube.com`; it does only
if you allow it, and you can take that back at any time in Chrome's extension
settings. It cannot see or interact with any other website you visit.

## Data retention

Your API key, preferences, Spotify data, saved chats, and DM history stay on your
device until you remove them — clear the key in the popup, use Disconnect in the
Spotify panel, delete conversations in the Saved Chats panel, or uninstall the
extension. (Saved chats and DM history live in your browser's storage for
free4talk.com, so clearing that site's data also removes them.) For how long the F4T Tools API retains request data, contact us at
the address below.

## Children

The extension is not directed at children under 13.

## Changes

If this policy changes, the "Last updated" date above will change with it.

## Contact

Questions about this policy: **info@free4talk.me**
