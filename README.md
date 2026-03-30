# Cloudbase Alti Companion

**Free desktop app for skydivers.** Read your altimeter or audible via USB, download your jump log as CSV, and sync to your Cloudbase logbook.

→ **[Download the latest release](https://github.com/ctmayhew/cloudbase-releases/releases/latest)**
→ **[getcloudbase.com](https://getcloudbase.com)**

---

## Supported devices

| Device | Connection | What you get |
|--------|-----------|--------------|
| Alti-2 Neptune | USB serial | Jump log, max altitude, freefall time, speed |
| Alti-2 N3 | USB serial | Jump log, max altitude, freefall time, speed |
| Alti-2 N3A | USB serial | Jump log, max altitude, freefall time, speed |
| Alti-2 Atlas | USB serial | Jump log, max altitude, freefall time, speed |
| Caelum Systems Talkable | USB drive | Jump log, device settings configurator |

Requires the **[Silicon Labs CP210x driver](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)** for Alti-2 devices (free, the app will guide you).

---

## Features

- **Read your jump log** — plug in and read in seconds, no account required
- **Download as CSV** — export your full jump history for use in any spreadsheet
- **Talkable settings configurator** — edit spoken altitudes, hard decks, beep settings and push them back to your device over USB
- **Sync to Cloudbase** — coming soon; join the waitlist at [getcloudbase.com](https://getcloudbase.com)

---

## Installation

### Mac
1. Download `Cloudbase.Companion-x.x.x-arm64.dmg`
2. Open the DMG and drag the app to your Applications folder
3. **First launch:** right-click the app → Open → Open (bypasses Gatekeeper — the app is not yet code-signed)

### Windows
Coming soon.

---

## Acknowledgements

The Alti-2 USB serial protocol implementation is based on the reverse-engineering work by [**evilwombat/alti2reader**](https://github.com/evilwombat/alti2reader) (GPL-3.0). Big thanks to that project for doing the hard work of mapping the TEA encryption key derivation and binary packet format — without it this app wouldn't exist.

---

## About Cloudbase

Cloudbase is a skydiving logbook and social platform — Strava meets Instagram for skydivers. Auto-syncs jumps from Burble, tracks milestones, and connects you with the DZ community.

**[Join the waitlist at getcloudbase.com](https://getcloudbase.com)**
**[Follow us on Instagram @cloudbaseapp](https://www.instagram.com/cloudbaseapp)**

---

## Disclaimer

Cloudbase Alti Companion is independent software. It is not affiliated with, endorsed by, or officially supported by Alti-2, Caelum Systems, or any device manufacturer. Use at your own discretion. All device names are trademarks of their respective owners.
