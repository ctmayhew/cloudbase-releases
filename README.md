# Cloudbase AltiReader

**Free desktop app for skydivers.** Read your altimeter, audible, or GPS logger via USB. Download your jump log as CSV or sync to your Cloudbase logbook.

→ **[Download the latest release](https://github.com/ctmayhew/cloudbase-releases/releases/latest)**
→ **[getcloudbase.com/altireader/download](https://getcloudbase.com/altireader/download)**

---

## Supported devices

| Device | Connection | What you get |
|--------|-----------|--------------|
| Alti-2 Neptune | USB serial | Jump log, exit altitude, freefall time, speed |
| Alti-2 N3 | USB serial | Jump log, exit altitude, freefall time, speed |
| Alti-2 N3A | USB serial | Jump log, exit altitude, freefall time, speed |
| Alti-2 Atlas | USB serial | Jump log, exit altitude, freefall time, speed |
| Caelum Systems Talkable | USB drive | Jump log, exit altitude, freefall time |
| L&B ProTrack II | USB drive | Jump log, exit altitude, freefall time |
| FlySight 1 | USB drive | GPS track, exit/deploy altitude, max/avg speed, freefall time, drop zone detection |

Alti-2 devices require the **[Silicon Labs CP210x driver](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)** (free — the app will guide you). All other devices work without drivers.

---

## Features

- **Read your jump log** — plug in and read in seconds, no account required
- **Download as CSV** — unified export format across all device types with exit altitude, deploy altitude, freefall time, max/avg speed, and drop zone (columns left blank when not available for your device)
- **FlySight GPS analysis** — speed analysis from GPS velocity data, deploy altitude from canopy opening detection, automatic drop zone matching from GPS coordinates
- **Sync to Cloudbase** — upload your jumps and GPS tracks directly to your Cloudbase logbook
- **Auto-detection** — detects connected devices automatically, or pick your device type manually

---

## Installation

### Mac
1. Download `Cloudbase.AltiReader-x.x.x-arm64.dmg`
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

Cloudbase AltiReader is independent software. It is not affiliated with, endorsed by, or officially supported by Alti-2, L&B, Caelum Systems, Bionic Avionics, or any device manufacturer. The app performs read-only operations — it does not modify device firmware or settings. Use at your own discretion. All device names are trademarks of their respective owners.
