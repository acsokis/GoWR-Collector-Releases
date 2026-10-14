# GoWR Collector Assistant

Unofficial Windows companion for God of War Ragnarök, with a desktop atlas and paired phone/Steam browser view.

**[Download the latest release](https://github.com/acsokis/GoWR-Collector-Releases/releases/latest)**

## Run

1. Extract `GoWRCollector-Portable.zip` into a writable folder.
2. Run `GoWRCollector.exe`. No installer is required.
3. For the phone view, connect both devices to the same trusted LAN/Wi-Fi and scan the QR shown by the app. QR links are valid for 30 days by default and survive Collector restarts. Set 1–365 days or revoke old links on the PHONE tab. Collector must be running on the same LAN address.
4. For Steam, use the app's Steam Overlay link in Steam's browser.

Settings and manual marker notes are stored in the generated `userdata` folder. Keep this folder when updating.

## Current limitations

- Looted/unlooted chest detection is **not automatic**. Collected and locked states are manual annotations shared across desktop, phone and Steam.
- Maps are schematic source-position atlases, not verified terrain or walkable routes.
- The supported-build camera adapter is read-only; independent character/Atreus position and all marker alignments are not verified.
- Translations are incomplete and may retain source text.

The private development source is maintained separately. This public repository contains release documentation and download assets only. Its automatically generated source archives contain this documentation, not the application source.

This application is unofficial. Game rights belong to their respective owners. The QR generator is Project Nayuki's MIT-licensed QR Code generator; its attribution and license are available in the application About view.
