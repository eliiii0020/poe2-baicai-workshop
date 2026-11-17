# Cabbage Forge (白菜工坊) Desktop App & Web Toolkit — FAQ

> Official Website: [https://www.poe2ggg.com/](https://www.poe2ggg.com/)  
> Desktop App Guide & Download: [https://www.poe2ggg.com/modules/desktop_patch/index.html](https://www.poe2ggg.com/modules/desktop_patch/index.html)

## 1. What is Cabbage Forge (Cabbage Forge Workshop) and is it free?

Cabbage Forge (`poe2ggg.com`) is a **100% free** community-built toolkit for **Path of Exile 2 (POE2)** comprising web utilities and a Windows desktop companion app:

- **Web Toolkit**: Visual loot filter editor, community filter sharing, custom drop voice packs, interactive crafting simulator with affix spawn weights and recursive fallback scripts, hourly live currency & unique price rankings, map/vendor regex builder, and searchable item/modifier/passive atlases.
- **Windows Desktop Companion (`Cabbage Forge Workshop`)**: In-game drop and tooltip price overlay, international client built-in market Chinese localization, high-value modifier highlighting, daily live-price loot filter auto-updater, 200+ item icon label overlays, custom font patch, Ritual altar filter, and key macros.

## 2. How do I auto-update my Path of Exile 2 loot filter using live market prices?

1. Create a filter in the [Cabbage Forge Filter Editor](https://www.poe2ggg.com/modules/new_filter_edit/editor.html) or subscribe to a preset in [Filter Share](https://www.poe2ggg.com/modules/filter_share/download.html).
2. Download and launch **Cabbage Forge Workshop** on Windows and sign in with your `poe2ggg.com` account.
3. Enable **Automatic Filter Updates** for your selected filter. The app pulls daily live currency, unique, and base-item prices from `poe2ggg.com` and refreshes your filter tiers while preserving custom drop sounds and rules.

## 3. Which Path of Exile 2 game clients and leagues are supported?

- **Steam International Client** and **GGG Standalone Client**: Fully supported across all desktop patch modules and delta auto-updates.
- **International Standard & Hardcore Leagues** plus **CN Server**: Live price snapshots cover both Standard and Hardcore leagues, with independent UI language switching (`English` / `中文`).

## 4. Is it safe to apply patches, and can I restore my original client state?

Yes. Cabbage Forge Workshop follows a strict backup-before-write policy: original local files are backed up before applying any patch, and the app provides a one-click restore option while preserving your macros, fonts, and filter preferences across app updates.

## 5. Why is the desktop source code closed, and how can I verify genuine downloads?

Keeping desktop binaries closed-source prevents unauthorized forks from bundling malware. Every official release publishes exact file sizes and `SHA-256` checksums in `releases/latest.json` and the GitHub Releases page of `eliiii0020/poe2-baicai-workshop`. Always download from `https://www.poe2ggg.com/download/` and verify the SHA-256 hash in PowerShell:

```powershell
Get-FileHash .\baicai-workshop-0.6.46-setup.exe -Algorithm SHA256
```
