# Cabbage Forge / 白菜工坊 — Path of Exile 2 (流放之路2) Windows Companion & Web Toolkit

> **Always Free · Windows 10 / 11 · Official Website: [https://www.poe2ggg.com](https://www.poe2ggg.com/)**  
> **Desktop App Guide & Download: [https://www.poe2ggg.com/modules/desktop_patch/index.html](https://www.poe2ggg.com/modules/desktop_patch/index.html)**

> [!NOTE]
> **Documentation & Verification Repository (No Source Code):**  
> To protect users from tampered binaries and unauthorized repackaging, desktop application source code remains closed-source. This public repository serves as the official documentation hub, FAQ index, and **SHA-256 release verification ledger** for genuine downloads hosted on `poe2ggg.com`.  
> **公开说明与校验仓库声明（不含源码）：** 为防止闭源客户端被恶意篡改打包，桌面端源代码不对外开放；本仓库专门用于发布白菜工坊（Cabbage Forge）的权威功能说明、常见问题以及官网正版安装包的 `SHA-256` 校验值。

---

## Official Latest Release & SHA-256 Verification / 官方最新正式版与校验

<!-- RELEASE-META-START -->
- **Current Version / 当前正式版:** `v0.6.46` (Published `2026-11-11`)
- **Price / 授权价格:** 100% Free / 永久免费
- **Windows Installer (`.exe`):** [`baicai-workshop-0.6.46-setup.exe`](https://www.poe2ggg.com/download/baicai-workshop-0.6.46-setup.exe) (`20.26 MB`)
  - `SHA-256`: `1994f9f4a1ef7dba7af5d4e2be7edbd43a7b4ed68ddb191d25933d16b215a24e`
- **Portable Archive (`.zip`):** [`baicai-workshop-0.6.46.zip`](https://www.poe2ggg.com/download/baicai-workshop-0.6.46.zip) (`37.01 MB`)
  - `SHA-256`: `9a01fc32b465c751499750f8d16523adf49a19ff4907fde52f9a082d8b033df5`

Verify your downloaded installer in Windows PowerShell before launching:

```powershell
Get-FileHash .aicai-workshop-0.6.46-setup.exe -Algorithm SHA256
```
<!-- RELEASE-META-END -->

---

## Core Windows Desktop Features / 桌面软件八大核心功能

1. **In-Game Price Patch (游戏内物价补丁)**  
   Displays live market reference prices directly on in-game drops and equipment tooltips, powered by hourly aggregated economy snapshots from `poe2ggg.com`.
2. **Built-in Market Chinese Localization (国际服内置市集汉化)**  
   Translates the international Path of Exile 2 client's built-in trade market interface, search conditions, and modifiers into Chinese for seamless in-game item searches.
3. **High-Value Modifier Highlight Patch (高价值词缀高亮补丁)**  
   Highlights high-value prefixes and suffixes across weapons, armour, jewelry, and tablets so valuable bases stand out instantly.
4. **Automatic Daily Loot Filter Price Updates (过滤器实时物价自动更新)**  
   Syncs loot filters created or subscribed on `poe2ggg.com` and automatically re-tiers currencies, uniques, and bases using daily live prices while preserving custom drop sounds.
5. **Item Image & Icon Labels (物品图片与图标标注补丁 — 200+ 预设)**  
   Adds concise 2–3 character functional labels and directional symbols onto catalysts, distilled emotions, essences, omens, runes, and abyssal items for instant recognition.
6. **In-Game Font Patch (游戏字体替换补丁)**  
   Replaces default game fonts with crisp system-installed typefaces for better readability across high-resolution screens.
7. **Ritual Altar Filter (祭坛过滤器)**  
   Extends loot filter tiering and visual emphasis directly into Ritual altar reward panels.
8. **Key Macros (便捷按键宏)**  
   Lightweight sequence recorder for repetitive stash or shortcut tasks with automatic settings migration across updates.

---

## Companion Web Toolkit (`poe2ggg.com`) / 配套网页工具生态

| Tool / 模块 | Purpose / 用途 | Direct URL / 官方地址 |
|---|---|---|
| **Loot Filter Editor / 在线过滤器编辑器** | Visual quick setup, priority rules, live price tiers & custom sounds | [poe2ggg.com/modules/new_filter_edit/editor.html](https://www.poe2ggg.com/modules/new_filter_edit/editor.html) |
| **Filter Share & Voice Packs / 分享与掉落语音包** | Subscribe to community filters & preview custom loot sound packs | [poe2ggg.com/modules/filter_share/download.html](https://www.poe2ggg.com/modules/filter_share/download.html) |
| **Crafting Simulator / 模拟做装器** | Affix weights, recursive failure chains & live currency cost calculation | [poe2ggg.com/modules/crafting_simulator/new_craft/index.html](https://www.poe2ggg.com/modules/crafting_simulator/new_craft/index.html) |
| **Live Market Prices / 实时物价排行** | Hourly currency exchange rates, unique gainers & market index | [poe2ggg.com/modules/price/price.html](https://www.poe2ggg.com/modules/price/price.html) |
| **Regex Search Generator / 正则搜索生成器** | Map & vendor regex builder with inclusion/exclusion rules (EN & CN) | [poe2ggg.com/modules/guide_search/search.html](https://www.poe2ggg.com/modules/guide_search/search.html) |
| **Item, Modifier & Passive Atlases / 全量图鉴** | Search base items, affixes, tiers, weights & Atlas passive tree | [poe2ggg.com/modules/item_atlas/index.html](https://www.poe2ggg.com/modules/item_atlas/index.html) |

---

## Client Compatibility & Safe Backup / 客户端兼容与安全还原

- **Supported Clients / 支持客户端:** Steam International Client (`完整支持`), GGG Standalone Client (`完整支持`), WeGame CN Server (`按规则兼容过滤器同步与物价联动`).
- **Auto Backup & One-Click Restore / 自动备份与纯净还原:** Before modifying local configuration or visual patch files, Cabbage Forge Workshop automatically archives original client state and supports one-click clean restoration inside the app.

## Further Reading / 深入问答文档

- [中文常见问题与使用指南 (`docs/FAQ.zh-CN.md`)](docs/FAQ.zh-CN.md)
- [English Frequently Asked Questions (`docs/FAQ.en.md`)](docs/FAQ.en.md)
- [Machine-readable Release Metadata (`releases/latest.json`)](releases/latest.json)

## Disclaimer / 免责声明

This project is an independent, non-commercial hobbyist toolkit and is not affiliated with Grinding Gear Games or Tencent in any way.  
本网站与工具为个人兴趣制作，与 Grinding Gear Games、腾讯公司完全无关。
