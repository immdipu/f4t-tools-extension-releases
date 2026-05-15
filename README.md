# F4T Tools — Release Mirror

Public release mirror for the [F4T Tools](https://github.com/immdipu/f4t-tools-extension) Chrome extension.

The source repository is private; this repository exists solely to host signed release artifacts (`.zip` builds) so the extension's in‑app update check can reach them via the public GitHub API.

---

![F4T Tools extension demo](https://free4talk.me/extension/f4t--tool-ext-demo.gif)

> Prefer a walkthrough? The full setup guide lives at **[free4talk.me/f4t-tools-extension](https://free4talk.me/f4t-tools-extension)** — annotated screens, FAQ, and a five‑minute install.

---

## Setup — four short steps

### 1. Sign in
Open **[free4talk.me/login](https://free4talk.me/login)** and click **Continue with Google**. One Google login; the key you create next is tied to this account.

### 2. Generate your API key
Open **[free4talk.me/api-key](https://free4talk.me/api-key)**, click **Generate API key**, then **Copy**. One key per account.

📹 Watch the API‑key flow: [video walkthrough](https://res.cloudinary.com/deolhhiqa/video/upload/v1778836235/zqa4boxz5ifworbeow6t.mov) (~15 seconds).

### 3. Install the extension
1. Download the latest `f4t-tools-vX.Y.Z.zip` from **[Releases](https://github.com/immdipu/f4t-tools-extension-releases/releases/latest)**.
2. Unzip it.
3. Open `chrome://extensions` in your browser.
4. Toggle **Developer mode** on (top‑right).
5. Click **Load unpacked** and select the unzipped folder.

> 💻 Desktop only — Chrome / Edge / Brave / Opera on a PC or Mac.

### 4. Paste your key and go live
Click the F4T Tools icon in the toolbar, paste the API key into the popup, hit **Save**, then flip the toggle to **Live**. You'll see a green indicator when the key is verified.

---

## Updating

The extension checks this repository for new releases via the public GitHub API. When a new build ships, you'll see an update prompt in the popup — re‑download the latest ZIP and reload the unpacked extension.

## Troubleshooting

- **Key rejected?** Make sure you copied the full key from [free4talk.me/api-key](https://free4talk.me/api-key) and that the same Google account is signed in on both sides.
- **Lost your key?** Revoke and regenerate from the API Key page — the old one stops working immediately.
- **Stopped working after an update?** Reload the extension at `chrome://extensions`.

## Links

- 🧭 Setup guide — https://free4talk.me/f4t-tools-extension
- 🔑 API key — https://free4talk.me/api-key
- 🔐 Sign in — https://free4talk.me/login
- 📦 Latest release — https://github.com/immdipu/f4t-tools-extension-releases/releases/latest
