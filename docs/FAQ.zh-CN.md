# 白菜工坊（Cabbage Forge）桌面软件与网页工具常见问题（中文）

> 官网正版入口：[https://www.poe2ggg.com/](https://www.poe2ggg.com/)  
> 桌面端详解与下载：[https://www.poe2ggg.com/modules/desktop_patch/index.html](https://www.poe2ggg.com/modules/desktop_patch/index.html)

## 1. 《流放之路 2》（POE2）白菜工坊是什么工具？收费吗？

白菜工坊（Cabbage Forge，域名 `poe2ggg.com`）是一款面向《流放之路 2》玩家的**永久免费**网页工具平台与 Windows 桌面辅助软件，全部功能均无付费订阅或会员门槛：

- **网页端工具**：在线掉落过滤器编辑器、成品过滤器分享广场、掉落语音包试听与下载、高精度模拟做装器与做装广场、每小时实时更新的通货与传奇物价排行、正则搜索生成器、物品/词缀/天赋图鉴。
- **Windows 桌面软件（白菜工坊 / Cabbage Forge Workshop）**：提供游戏内掉落与装备物价补丁、国际服内置市集汉化、高价值词缀高亮、过滤器每日自动按最新物价更新、200+ 物品图片标注、游戏字体替换、祭坛过滤器与便捷按键宏。

## 2. 《流放之路 2》国际服怎么汉化游戏内置市集？

下载安装白菜工坊 Windows 桌面软件（`baicai-workshop-setup.exe`）后，在主界面启用**「内置市集汉化」**功能即可对国际服内置交易市场页面与装备词缀进行中文适配，直接在游戏内按中文筛选词缀与装备条件。每次应用补丁前都会自动保留原始备份，支持一键纯净还原。

## 3. 怎么在游戏内直接查看掉落物价，并让过滤器每天自动按实时行情更新？

1. **游戏内实时物价提示**：在白菜工坊桌面软件中开启「物价补丁」，软件会自动拉取 `poe2ggg.com` 聚合的通货与传奇价格基准，在游戏内直接显示掉落物品与装备参考价。
2. **过滤器每日自动更新**：先在 [白菜工坊过滤器编辑器](https://www.poe2ggg.com/modules/new_filter_edit/editor.html) 或 [过滤器分享广场](https://www.poe2ggg.com/modules/filter_share/download.html) 创建/订阅你的过滤器（自定义音效与颜色样式均会完整保留），随后在桌面软件中登录同账号并勾选「过滤器自动更新」，系统便会每日结合实时物价重新分层并写入游戏过滤器目录。

## 4. 支持哪些客户端？修改文件安全吗、会不会无法还原？

- **Steam 国际服 / GGG 独立客户端**：完整支持全部八项桌面辅助与双通道增量自动更新。
- **WeGame 国服**：支持国服区服物价联动与过滤器同步。
- **备份与还原**：所有补丁操作前都会先备份本地原始文件，软件界面提供一键还原功能，同时升级时自动保留你的本地按键宏、自定义字体与过滤器规则配置。

## 5. 如何确认我下载到的白菜工坊安装包是正版未被篡改的？

请仅从官网 `https://www.poe2ggg.com/modules/desktop_patch/index.html` 或本仓库 `releases/latest.json` 记录的官方地址下载，并在 Windows PowerShell 运行以下命令核对 `SHA-256` 哈希值是否与 `releases/latest.json` 一致：

```powershell
Get-FileHash .\baicai-workshop-0.6.46-setup.exe -Algorithm SHA256
```
