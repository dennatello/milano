[Русский](README.md) | **English**

<img src="icon.png" width="88" height="88" alt="Milano app icon">

# Milano for Mac

**Floating notes. Ready-to-use replies with a hotkey. Russian ↔ English keyboard layout correction.**

Milano is a small native workspace for people who answer customers, handle messages and keep useful information close at hand.

**[Download the Apple Silicon beta](https://github.com/dennatello/milano/releases/tag/v1.0.0-rc8#english)** · [Installation guide (Russian)](INSTALL.md) · [Report an issue](https://github.com/dennatello/milano/issues)

## Features

- **Floating notes:** multiple windows, always on top, resizing, opacity, collapse and autosave.
- **Quick phrases:** groups, search and custom global keyboard shortcuts.
- **Work profiles:** Sales, Support and Personal, with manual switching. These profile names appear in Russian in the current app.
- **Templates:** date, time, clipboard content, cursor position and custom fields to fill in before pasting.
- **RU ↔ EN layout correction:** optional automatic correction at word boundaries, manual correction and undo by repeating the shortcut. Automatic mode is off by default.
- **Local data:** JSON import/export and local backups. No required account or cloud sync.

For example, `Hello, {name}! Order {order} is ready.` asks you for a name and order number before inserting the completed reply.

## Current version

**1.0 RC8, build 9 — a free test build.** Licensing is disabled in this beta. The seven-day trial and purchasing are not available yet.

Requires an Apple Silicon Mac and macOS 13 or later. Intel Macs and Windows are not supported. This is the configured minimum macOS version; testing across all supported system versions is still in progress. The current app interface is in Russian. This English page translates the description, not the app itself.

This beta has **no Developer ID signature or Apple notarization**, so macOS may block the first launch. Read the [installation guide and limitations (Russian)](INSTALL.md) and [Apple's guidance on opening downloaded apps](https://support.apple.com/en-us/102445). This is an early test version; compatibility with every editor has not been established.

## Quick start

1. Download `Milano-1.0-rc8-preview-arm64.dmg` from the release's **Assets** section.
2. Quit a running copy of Milano, open the DMG and drag `Milano.app` onto the **Applications** shortcut. Eject the image and launch the installed app.
3. Floating notes work without input permissions. For phrase insertion, grant Milano **Accessibility** access in macOS settings.
4. For automatic layout correction, also grant **Input Monitoring**, restart if requested and enable automatic correction in Milano's settings.
5. Type `ghbdtn` followed by a space in TextEdit; the expected result is `привет`.

`SHA256SUMS.txt` contains the DMG checksum. GitHub's automatic **Source code** archives contain only this repository's public materials, not the application.

## Data and permissions

Notes and phrases stay on your Mac. Accessibility is used to inspect the focused text field and insert text. Input Monitoring is also needed for automatic layout correction. Milano does not send typed text to the developer.

Data is stored in `~/Library/Application Support/Milano/`. JSON exports and backups contain your texts and are not encrypted by the app. [Data details (Russian)](PRIVACY.md).

## Help improve Milano

Try it in your usual workflow and [leave feedback](https://github.com/dennatello/milano/issues/new): which app you used, what worked and what got in the way. Repeatable bugs and examples of time saved are especially useful. Use fictional examples instead of sharing private notes or messages.

This repository contains product information and distribution materials. **Milano's application source code is closed.** See [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) for third-party notices.
