# Joe's WoW: Forever addons

WoW: Forever addons, made by Joe for Joe and friends:

- **Hotline**: a better friends list. Every WoW: Forever toon your Battle.net friends play is remembered, so you can still find their alts when they're offline.
- **ForeverBags**: all your bags in one window, with search, sorting and sections. It sells junk and repairs at vendors.
- **DotNudge** (for Warlocks): shows the next Affliction DoT your target needs, with timers for every mob you've DoTed. Type `/dn`.
- **FishTrack** (for fishing): catches per hour, skill-ups, a lure timer and one-click lure, rare-catch alerts, catch goals, and your catch history on the world map. Type `/ft`.

## Install them (once)

1. Open the [newest release](../../releases/latest) and download **Forever-Updater.exe**.
2. Run it. Windows may say it's from an unknown publisher: click **More info**, then **Run anyway**.
3. If it can't find World of Warcraft by itself, press **Change...** and pick your World of Warcraft folder.
4. Hotline and ForeverBags are ticked. Tick DotNudge or FishTrack if you want them, untick anything you don't, then press **Install**.

Had **Hotline-Updater.exe** before? Download Forever-Updater.exe once instead. It remembers your WoW folder.

## Every night

Run **Forever-Updater.exe** before you play and press **Update** if it offers one. If WoW is already open, type `/reload` afterwards. The updater keeps itself up to date too, so you only download it once.

The updater never touches your settings: they live in WoW's `WTF` folder, and the updater only changes the folders of the addons you've ticked in `Interface\AddOns`.

## New things

Hotline grows one simple feature at a time. The first is the friends list: `/hl` or Alt+H opens it. ForeverBags stays a simple bag.

This repository only holds the release files. The updater never asks for passwords and never touches anything outside those addon folders.
