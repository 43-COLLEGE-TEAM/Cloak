<div align="center">

<img src="docs/logo.png" alt="Cloak" width="120" />

# 43 CLOAK

**面向企业全员的 AI 工作平台，让组织的智力资产越用越厚**

[![版本](https://img.shields.io/badge/版本-0.1.5-blue)](https://github.com/43-COLLEGE-TEAM/Cloak/releases/tag/v0.1.5)
[![平台](https://img.shields.io/badge/平台-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)](#下载)
[![License](https://img.shields.io/badge/License-Proprietary-red)](#)

</div>

---

## 43 CLOAK 是什么

43 CLOAK 是一款面向企业全员的 AI 工作平台。它让企业的每一位员工，在日常工作中拥有一位懂业务的 AI 同事。

企业将自身积累的流程规范、岗位经验与行业 know-how 装入工作区，员工以对话方式调用工作区中的 AI 同事，由其协助完成日常业务。能力开放给员工使用，know-how 内核始终归属于组织。每一次调用都精确绑定至具体员工、具体工作区与具体业务产出，企业在 AI 上的投入由此与真实的生产现场逐一对应。员工在 AI 协同下形成的成果亦可经回流机制反哺工作区，使组织的智力资产在持续使用中持续增厚。

43 CLOAK 让企业的 AI 投入对管理者**管得住、用得对、留得下**，让 AI 对员工越用越懂业务、越懂岗位、越懂这家公司，适用于各行业、各规模企业的全员 AI 协作场景。

> 当前发布的桌面客户端已支持个人空间与企业空间，既可以作为个人 AI 工作入口，也可以接入企业团队协作场景。
> 本项目早期工作参考借鉴了 [TOKENICODE](https://github.com/yiliqi78/TOKENICODE) 进行迭代开发，在此致谢原作者（@小七姐，@Tiny）。
> Cloak 为闭源软件，仅提供安装包。

**当前已有功能：**

- 💬 **多个对话同时进行** — 可以同时开好几个话题，互不干扰，随时切换
- 📁 **直接处理文件** — 把文件拖进对话窗口，让 AI 帮你读、帮你总结、帮你分析
- 🏢 **个人空间 / 企业空间** — 个人资料与企业知识分开管理，团队协作边界更清晰
- 🪪 **飞书账号登录** — 企业成员可使用飞书账号登录，减少额外账号配置
- 🛠️ **管理后台** — 管理后台正在开发中，部分空间与成员管理能力已经可用
- 🤖 **选择不同的 AI 模型** — 根据需要，自由选择反应更快或能力更强的模型
- 🎨 **个性化界面** — 亮色、暗色随意切，还有多种配色与个人项目卡片皮肤可选
- 🧩 **工作搭子虚拟宠物** — 支持尺寸调节、转头宠物与自定义皮肤管理
- 💌 **问题反馈** — 设置中可以直接提交使用问题与改进建议
- 🌐 **中英文支持** — 界面语言可以随时切换

---

## 下载

> 当前版本：**0.1.5**  
> 发布页：[43-COLLEGE-TEAM/Cloak](https://github.com/43-COLLEGE-TEAM/Cloak/releases/tag/v0.1.5)

| 系统 | 下载 |
|------|------|
| 🪟 Windows | [EXE 安装包](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_x64-setup.exe) / [MSI 安装包](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_x64_en-US.msi) |
| 🍎 macOS（M 系列芯片）| [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_aarch64.dmg) |
| 🍎 macOS（Intel 芯片）| [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_x64.dmg) |
| 🐧 Linux AppImage | [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_amd64.AppImage) |
| 🐧 Linux DEB | [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak_0.1.5_amd64.deb) |
| 🐧 Linux RPM | [点击下载](https://github.com/43-COLLEGE-TEAM/Cloak/releases/download/v0.1.5/Cloak-0.1.5-1.x86_64.rpm) |

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

### 第二步：登录与配置

第一次打开 Cloak，可以使用飞书账号登录；如果你使用个人空间，也可以点左下角的**设置**图标，找到「服务商」，选择你使用的平台，把 API Key 粘贴进去保存。

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

### v0.1.5
- 修复个人项目上传的自定义背景图会保存到应用数据目录，并通过本地文件资源地址加载，避免打包后引用失效
- 修复自定义背景图清理逻辑兼容新的本地文件引用格式，减少无效文件残留
- 优化企业云端工作区文件展示，改为可展开的树形结构，文件夹层级更直观
- 新增云端文件搜索，可在已加载的目录中快速定位文件和文件夹
- 云端文件行内展示大小、缓存、冲突和下载状态，打开文件时反馈更明确

### v0.1.4
- 个人项目支持卡片换肤
- 桌面宠物增加尺寸调节与转头宠物
- 宠物资源与自定义皮肤管理更完善

### v0.1.3
- 支持飞书账号登录，方便企业成员直接进入工作空间
- 增加企业空间，明确划分企业空间与个人空间
- 增加管理后台，部分空间与成员管理功能已经可用
- 设置中增加问题反馈功能，使用中遇到问题可以更方便地提交
- 新增工作搭子虚拟宠物，让日常 AI 协作更有陪伴感

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

### 43hub

- **skill 商城** — 提供适合不同业务场景的 skill 发现与安装入口

### 管理后台

- **企业技能沉淀** — 将企业内部流程、经验与工具封装成可复用的工作能力
- **技能分发与治理** — 支持企业按团队、岗位或项目分发 skill，并持续维护版本

### 平台扩展

- **更多模型接入** — 持续新增国内外主流大模型
- **移动端** — iOS / Android 版本规划中

---

## 遇到问题？

用着有什么不对劲，或者有想要的新功能，可以在应用内直接反馈：

打开左下角的**设置**，进入**反馈**页面，填写问题描述。你可以粘贴截图或选择文件，也可以留下邮箱、微信或飞书手机号，方便我们后续跟进。

![设置中的反馈页面](docs/screenshots/feedback.png)

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
