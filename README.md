<div align="center">

<img src="docs/logo.png" alt="Cloak" width="120" />

# 43 CLOAK

**面向企业全员的 AI 工作平台，让组织的智力资产越用越厚**

[![版本](https://img.shields.io/badge/版本-0.1.1-blue)](https://github.com/43-COLLEGE-TEAM/Cloak/releases)
[![平台](https://img.shields.io/badge/平台-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)](#下载)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#)

</div>

---

## 43 CLOAK 是什么

43 CLOAK 是一款面向企业全员的 AI 工作平台。它让企业的每一位员工，在日常工作中拥有一位懂业务的 AI 同事。

企业将自身积累的流程规范、岗位经验与行业 know-how 装入工作区，员工以对话方式调用工作区中的 AI 同事，由其协助完成日常业务。能力开放给员工使用，know-how 内核始终归属于组织。每一次调用都精确绑定至具体员工、具体工作区与具体业务产出，企业在 AI 上的投入由此与真实的生产现场逐一对应。员工在 AI 协同下形成的成果亦可经回流机制反哺工作区，使组织的智力资产在持续使用中持续增厚。

43 CLOAK 让企业的 AI 投入对管理者**管得住、用得对、留得下**，让 AI 对员工越用越懂业务、越懂岗位、越懂这家公司，适用于各行业、各规模企业的全员 AI 协作场景。

> 当前发布的桌面客户端为 43 CLOAK 的个人使用入口，企业工作区功能正在持续建设中。
> 本项目早期工作参考借鉴了 [TOKENICODE](https://github.com/yiliqi78/TOKENICODE) 进行迭代开发，在此致谢原作者（@小七姐，@Tiny）。
> Cloak 为闭源软件，仅提供安装包。

**当前已有功能：**

- 💬 **多个对话同时进行** — 可以同时开好几个话题，互不干扰，随时切换
- 📁 **直接处理文件** — 把文件拖进对话窗口，让 AI 帮你读、帮你总结、帮你分析
- 🤖 **选择不同的 AI 模型** — 根据需要，自由选择反应更快或能力更强的模型
- 🎨 **个性化界面** — 亮色、暗色随意切，还有多种配色可选
- 🌐 **中英文支持** — 界面语言可以随时切换

---

## 下载

> 当前版本：**v0.1.1**

| 系统 | 下载 |
|------|------|
| 🪟 Windows | [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.1/Cloak_0.1.1_x64-setup.exe) |
| 🍎 macOS（M 系列芯片）| [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.1/Cloak_0.1.1_aarch64.dmg) |
| 🍎 macOS（Intel 芯片）| [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.1/Cloak_0.1.1_x64.dmg) |
| 🐧 Linux | [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.1/Cloak_0.1.1_amd64.AppImage) |

不知道自己的 Mac 是哪种芯片？点左上角苹果图标 → **关于本机**，看「芯片」那一行。写着 M1 / M2 / M3 / M4 就选 M 系列，写着 Intel 就选 Intel。

> **Windows 用户：** 首次使用前需要先安装 [Git for Windows](https://git-scm.com/download/win)，安装时一路默认就好。

---

## 界面预览

**主界面**

![主界面](docs/screenshots/main.png)

**文件管理**

![文件管理](docs/screenshots/files.png)

**设置**

![设置](docs/screenshots/settings.png)

---

## 怎么使用

### 第一步：安装

- **Windows**：双击下载好的安装文件，一路点「下一步」就行
- **macOS**：打开下载的文件，把 Cloak 图标拖到「应用程序」文件夹
- **Linux**：右键下载的文件 → 属性 → 勾选「允许作为程序执行」，然后双击打开

### 第二步：填入你的 API Key

第一次打开 Cloak，点左下角的**设置**图标，找到「服务商」，选择你使用的平台，把 API Key 粘贴进去保存。

Cloak 内置了以下服务商，选好后点对应链接去注册获取 Key：

| 服务商 | 获取 API Key |
|--------|-------------|
| Anthropic（官方 Claude） | [前往获取](https://console.anthropic.com/account/keys) |
| 智谱 GLM | [前往获取](https://bigmodel.cn/usercenter/proj-mgmt/apikeys) |
| Kimi | [前往获取](https://platform.moonshot.cn/console/api-keys) |
| Kimi Code | [前往获取](https://www.kimi.com/code/console) |
| MiniMax | [前往获取](https://platform.minimaxi.com/user-center/basic-information/interface-key) |
| 通义千问 | [前往获取](https://bailian.console.aliyun.com/?apiKey=1) |
| OpenRouter | [前往获取](https://openrouter.ai/settings/keys) |
| 小米 MiMo | [前往获取](https://platform.xiaomimimo.com/) |

如果你已经有了 Key，直接粘贴进去就能用，不需要重新注册。

### 第三步：开始对话

点左上角的**新建对话**，在底部输入框里写下你想问的问题或想做的事，按回车发送，等 Claude 回复就行了。

**几个小技巧：**
- 有文件想让 AI 看？直接拖进对话框
- 输入 `/` 可以看到所有快捷命令
- 按 `Ctrl+K`（Windows）或 `Command+K`（Mac）可以快速搜索功能

---

## 更新记录

### v0.1.1
- 修复了左侧菜单有时展开收起不正常的问题
- 修复了后台偶尔占用内存过高的问题
- 更新了应用图标

### v0.1.0
- 🎉 首次发布
- 支持多个对话同时进行
- 内置文件浏览器，支持拖拽附件
- 支持切换不同 Claude 模型
- 亮色 / 暗色主题
- 中英文界面切换

---

## 未来计划

### 企业 / 团队功能

- **飞书账号登录** — 企业用户通过飞书一键登录，无需单独配置 API Key
- **团队配额管理** — Token 用量由管理员统一分配，个人无需关心计费
- **工作空间** — 按项目或团队划分独立的文件与对话空间，互不干扰
- **审计与合规** — 每次调用精确绑定至具体员工与业务产出，管理员可查看操作日志，满足企业合规要求

### 平台扩展

- **更多模型接入** — 持续新增国内外主流大模型
- **移动端** — iOS / Android 版本规划中

---

## 遇到问题？

用着有什么不对劲，或者有想要的新功能，欢迎告诉我们：

👉 [去这里反馈](https://github.com/43-COLLEGE-TEAM/Cloak/issues/new)

说清楚你在做什么、出现了什么情况、用的是哪个系统，我们会尽快处理。

---

## 联系我们

<!-- 以下链接待补充 -->

| 渠道 | 链接 |
|------|------|
| 🌐 官网 | 即将上线 |
| 💬 飞书群 | 即将开放 |
| 💬 微信群 | 即将开放 |

---

<div align="center">

Made with ❤️ by [43 COLLEGE TEAM](https://github.com/43-COLLEGE-TEAM)

© 2026 43 COLLEGE TEAM. All rights reserved. 本软件为闭源软件，禁止反编译、二次分发或商业使用。

</div>
