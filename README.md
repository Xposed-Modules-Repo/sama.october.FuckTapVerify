<div align="center">
<img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/refs/heads/main/icon.svg"  width="250" height="250" />

# FuckTapVerify
[![LSPosed](https://img.shields.io/badge/LSPosed-Module-blue.svg)](https://github.com/Xposed-Modules-Repo/me.feimeng.vip/releases)

**破解taptap平台上的付费游戏购买验证**
</div>

# 这个模块是做什么的？
用于学习逆向和安全测试，跳过taptap平台上的付费下载游戏的购买验证。

包括taptap原生购买验证和心动游戏二次网络验证。

注意，**非内购破解**。

# 如何使用？
下载并安装[releases](https://github.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/releases)中的最新版本，然后在LSPosed的作用域中勾选需要破解购买验证的游戏。

不建议EdXPosed等全局作用域的框架使用，因为模块会无差别的Hook所有作用域中的非系统应用。

若确有需求可以提出[issue](https://github.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/issues)，我会考虑在下个版本加入模块内选择作用软件的功能。

# 适用范围？
理论上支持大部分**付费下载**的**单机**游戏。

注：**如泰拉瑞亚等有社区或社交等功能的游戏，即使通过了taptap验证和心动服务器的验证后仍需向专用游戏服务器验证账号token。即使玩法偏向单机，但实质上类似网游。因此大概率破解失败。**

心动网络验证仅做了HttpURLConnection支持，若有使用okhttp的游戏破解失败可以提交[issue](https://github.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/issues)。我会写一个针对okhttp的方案。

若您尝试的游戏无法破解，建议您通过[issue](https://github.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/issues)向我反馈。同时需附上您使用的Xposed框架、游戏安装包(通过网盘发送，不接受度盘)、Xposed日志等信息。我会尝试查明原因并改进和适配。

# 免责声明

- 本模块完全免费，并且作者没有从中获取任何利益。本模块仅供个人学习研究之用。请您在下载模块的24小时内完全删除所有相关内容。
- 请勿用于商业和非法用途，请勿传播到国内公共网络平台。
- 下载本模块即代表您同意承担由此可能造成的一切责任，对于本模块造成的一切责任，作者概不承担。
- 如果本模块侵犯了您的合法权益，请在[issue](https://github.com/Xposed-Modules-Repo/sama.october.FuckTapVerify/issues)提供您的邮箱以取得联系。并提供相关证明，若权利侵害属实，我会立即删除本仓库和一切分发渠道。

## Star
[![Stargazers over time](https://starchart.cc/Xposed-Modules-Repo/sama.october.FuckTapVerify.svg?variant=adaptive)](https://starchart.cc/Xposed-Modules-Repo/sama.october.FuckTapVerify)
