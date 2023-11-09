![Aelysium Wordmark Image](https://github.com/Aelysium-Group/.github/blob/main/images/rustyconnector-wordmark.png?raw=true)

# 👋 歡迎使用RustyConnector
![Velocity](https://flat.badgen.net/badge/Velocity/3.1.1%20-%203.2.0/1197d1?icon=dockbit)
![PaperMC](https://flat.badgen.net/badge/Paper/1.16%20-%201.20.2/F96854?icon=telegram)
![Folia](https://flat.badgen.net/badge/Folia/Supported/E004BC?icon=maven)
[![Aelysium](https://flat.badgen.net/badge/Discord/Aelysium/5865F2?icon=discord)](https://join.aelysium.group/)
[![Build](https://flat.badgen.net/github/release/Aelysium-Group/rusty-connector?label=Latest%20Stable%20Release&icon=maven)](https://github.com/Aelysium-Group/rusty-connector/releases)
[![License](https://flat.badgen.net/badge/License/MIT/5865F2)](https://github.com/Aelysium-Group/rusty-connector/blob/main/LICENSE)

[RustyConnector]是一款可運行於[Velocity]/[Paper]/[Folia]群組網絡的負載均衡插件，它可以讓你的服務器在運行狀態下自動向代理端註冊或取消註冊子服務器，並實現玩家間的負載均衡。

<!-- Table-1 -->
<table>
<thead>
<h2>🧭 快捷鏈接</h2>
</thead>
<tbody>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://wiki.aelysium.group/rusty-connector/"><img src="./blob/images/logo/rc-logo.webp"></a>
  </td>
  <td valign="top">
    <h3>Wiki</h3>
   <p>
      不知道如何使用本插件？ <a href="https://wiki.aelysium.group/rusty-connector/">點擊此鏈接</a>教你快速入門。
    </p>
  </td>
</tr>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://github.com/Aelysium-Group/rusty-connector/releases"><img src="./blob/images/logo/rc-logo.webp"></a>
  </td>
  <td valign="top">
  <h3>下載插件</h3>
    <p>
      <a href="https://github.com/Aelysium-Group/rusty-connector/releases">點擊前往Github Releases下載</a>，或前往插件發布頁。
    </p>
  </td>
</tr>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://join.aelysium.group"><img src="./blob/images/logo/rc-logo.webp"></a>
  </td>
  <td>
  <h3>幫助支持</h3>
    <p>
      您可<a href="https://join.aelysium.group">點擊此鏈接</a>加入我們的Discord社區獲得更多幫助。
    </p>
  </td>
</tr>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://github.com/Aelysium-Group/rusty-connector/issues"><img src="./blob/images/logo/rc-logo.webp"></a>
  </td>
  <td>
  <h3>BUG反饋</h3>
    <p>
      在使用插件的時候遇到了煩人的BUG？請<a href="https://github.com/Aelysium-Group/rusty-connector/issues">點擊此鏈接</a>與我們反饋。
    </p>
  </td>
</tr>
</tbody>
</table>

<!-- Table-2 -->
<table>
<thead>
<h2>🚀 插件發布頁</h2>
</thead>
<tbody>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://modrinth.com/plugin/rustyconnector"><img src="./blob/images/logo/modrinth.svg"></a>
  </td>
  <td valign="top">
    <h3>Modrinth</h3>
    <p>
      <a href="https://modrinth.com/plugin/rustyconnector">點擊前往Modrinth插件發布頁。</a>
    </p>
  </td>
</tr>
<tr>
  <td width="80" align="center" valign="top">
    <br>
    <a href="https://hangar.papermc.io/nathan-i-martin/RustyConnector"><img src="./blob/images/logo/hangar.svg"></a>
  </td>
  <td valign="top">
    <h3>Hanger</h3>
    <p>
      <a href="https://hangar.papermc.io/nathan-i-martin/RustyConnector">點擊前往Hanger插件發布頁。</a>
    </p>
  </td>
</tr>
</tbody>
</table>

---
# ✨ 特色功能
- ### ✅ 為構建大型群組服而生
- ### ✅ 可在運行期間自動向代理端註冊全新的子服務器
- ### ✅ 與Redis集成實現超快速度傳輸
- ### ✅ 可創建預定義的白名單配置並動態開啟或關閉它們
- ### ✅ 可通過家族級白名單和負載平衡將類似的服務器註冊成家族
- ### ✅ 可自動從代理端中取消註冊被凍結的服務器
- ### ✅ 可為你的服務器添加軟/硬人數限制
- ### ✅ 可用來搭建穩定可靠的Minecraft群組伺服器
- ### ✅ 支援端對端的資料包加密
- ### ✅ 可與LuckPerms-Velocity一起使用
- ### ✅ 支持Kubernetes容器化部署
- ### ✅ 支持Folia服務端
- ### ❌ 它不能做到給你個擁抱或Rickroll了你

---
# 🎨 數據統計

## 🌌 代理端數據統計 ([點擊查看](https://bstats.org/plugin/velocity/RustyConnector/17972)):
[![RustyConnector bstats graph](https://bstats.org/signatures/velocity/RustyConnector.svg)](https://bstats.org/signatures/velocity/RustyConnector.svg)
## 🌌 子服務器數據統計 ([點擊查看](https://bstats.org/plugin/bukkit/RustyConnector/17973)):
[![RustyConnector bstats graph](https://bstats.org/signatures/bukkit/RustyConnector.svg)](https://bstats.org/signatures/bukkit/RustyConnector.svg)

---
## 🌐 語言切換

语言切换 / Need to switch languages?

[![English](https://flat.badgen.net/badge/English/Click%20me/blue)](https://github.com/Aelysium-Group/rusty-connector/)
[![简体中文](https://flat.badgen.net/badge/简体中文/Click%20me/blue)](https://github.com/Aelysium-Group/rustyconnector-zhhans)
[![繁體中文](https://flat.badgen.net/badge/繁體中文/Click%20me/blue)](https://github.com/Aelysium-Group/rustyconnector-zhhant)

2023 © [Aelysium](https://www.aelysium.group)

<!-- URL LIST -->
[Folia]:https://github.com/PaperMC/Folia
[Paper]: https://papermc.io
[Velocity]: https://velocitypowered.com
[RustyConnector]: https://github.com/Aelysium-Group/rusty-connector
