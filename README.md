# Spoolman GO

**Manage your 3D printing filament spools from your iPhone.**

Spoolman GO connects to your [Spoolman](https://github.com/Donkie/Spoolman) server and gives you a clean, fast mobile interface to track every spool in your collection — including NFC tag support so you can scan a tag and instantly pull up all the details.

---

## What it does

Do you have a shelf full of filament spools and no idea which ones are almost empty? Spoolman GO fixes that.

- **See all your spools at a glance** — remaining weight, material, color, and where each spool is stored.
- **Log filament use** — book how much you printed, or measure what's left on the scale, right from your phone.
- **Get low-stock warnings** — the dashboard highlights spools that are running low so you can reorder in time.
- **Manage everything** — create, edit and delete spools, filament profiles, manufacturers (vendors), and storage locations.
- **Scan & write NFC tags** — tap an [OpenSpool](https://github.com/spuder/OpenSpool)-compatible NFC tag to a spool and Spoolman GO reads it instantly. Or write a new tag from the spool detail screen.
- **Search and filter** — find spools by material, manufacturer, location, color, or stock level in seconds.
- **Try it without a server** — Demo Mode lets you explore the full app offline with sample data, no Spoolman setup needed.

---

## Requirements

| What you need | Details |
|---|---|
| iPhone | iPhone 7 or newer, iOS 13 or later |
| Spoolman server | Self-hosted [Spoolman](https://github.com/Donkie/Spoolman) or [FilaMan](https://github.com/ManfredTremmel/filaman) instance on your local network or the internet |
| NFC tags (optional) | NTAG215 or NTAG216 tags for reading/writing OpenSpool data |

No Spoolman server yet? Use **Demo Mode** to try the app first.

---

## Getting started

1. Download Spoolman GO from the App Store *(link coming soon)*
2. On first launch, choose **Demo Mode** to explore the app, or **Live Mode** to connect to your server.
3. In Live Mode, go to Settings and enter your Spoolman URL, for example:
   - `http://spoolman.local:8083` — local network
   - `https://spoolman.example.com` — public instance
   - `https://example.com/spoolman` — behind a reverse proxy
4. Tap **Test connection** — that's it.

---

## Languages

The app automatically switches between **English** and **German** based on your iPhone's language setting.

---

## Found a bug or have a suggestion?

Please open an issue — it's the fastest way to reach me:

**[Report a bug or request a feature](https://github.com/Fazerize/spoolman-go/issues)**

Include:
- What you were trying to do
- What happened instead
- Your iPhone model and iOS version
- Your Spoolman version (visible in the Spoolman web UI)

---

## Privacy

Spoolman GO does not collect any personal data. All data stays on your device and your own Spoolman server.

[Privacy Policy](https://fazerize.github.io/Spoolman-GO/privacy.html)

---

## License

© 2026 Fazerize. All rights reserved.
