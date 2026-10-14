# GoWR Collector Assistant

Find your next chest, Raven, artifact or lore discovery in God of War Ragnarök. Browse the atlas on your PC, keep it beside you on your phone, or open it in Steam's browser.

**[Download the latest portable release](https://github.com/acsokis/GoWR-Collector-Releases/releases/latest)** · Windows 10/11, 64-bit · No installer

## Start exploring

1. Extract `GoWRCollector-Portable.zip` into a folder you can write to, then run `GoWRCollector.exe`.
2. Open COLLECTOR and choose a realm, region and collectible type. Use the search and filters to narrow your hunt.
3. Click or tap a marker to add it to your targets. Tap it again to remove it. You can track several discoveries together.
4. Enable the game HUD to see numbered, color-coded icons. The nearest target sits in the middle, with other nearby targets beside it. A small arrow inside each ring points toward the target; the red distance arc shrinks as you approach and empties at five camera-distance world units.

The HUD uses a read-only camera adapter for the supported game build. It appears while the game is in the foreground. Distance is measured from the camera, so it does not necessarily reach zero beside a chest.

## Phone and Steam

Connect your phone and PC to the same trusted Wi-Fi or LAN. Open PHONE, start the companion and scan the QR code. For Steam, open the app's Steam Overlay link in Steam's browser. The browser view is a companion page, not an injected Steam plugin.

QR links last 30 days by default and survive Collector restarts. You can choose 1–365 days or revoke old links on the PHONE tab. Collector must stay running at the same LAN address. Web pages now reload when the app's web interface changes; refresh older open tabs once after this update.

## Updating

Close Collector, replace the portable app files, and keep your `userdata` folder. That folder holds settings, pairing and any existing manual marker notes. ReShade and game files are not replaced by this companion.

## What to expect

- Automatic opened/looted chest detection is not available. Unknown means unknown; an empty distance arc does not mean a chest was looted. Existing manual notes are only personal annotations.
- The maps are drawn exploration atlases based on extracted positions. They are not the game's terrain maps or verified walking routes, and some collectibles may still be missing.
- Independent character and Atreus tracking, story/ability access checks, and complete translation coverage are still unfinished.
- The HUD's fixed target row replaces the earlier experimental world-projected circles. Final gameplay and phone-layout testing is ongoing.

## About

An unofficial community companion. Game rights belong to their respective owners. QR generation uses Project Nayuki's MIT-licensed QR Code generator; attribution and license are included in the application.

Development source stays in a separate private repository. This public repository contains player documentation and downloadable releases; GitHub's source archives here contain documentation only.
