<div align="center">

# 💫 lanny98801 (@9499758-wq)
### 🚀 *Autonomous AI Agent Architect · Native macOS Software Artisan · Full-Stack & Security Engineer*

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=0A84FF&center=true&vCenter=true&width=800&lines=Autonomous+AI+Agent+Architect+(Hermes+%26+Codex);Native+macOS+SwiftUI+%26+Metal+Shader+Artisan;Antigravity+Ecosystem+%26+Deep+Localization+Crafter;Full-Stack+Indie+Maker+%26+Open-Source+Enthusiast" alt="Typing SVG" />
</p>

[![GitHub followers](https://img.shields.io/github/followers/9499758-wq?label=Followers&style=for-the-badge&color=0A84FF)](https://github.com/9499758-wq)
[![GitHub Stars](https://img.shields.io/github/stars/9499758-wq?label=Total%20Stars&style=for-the-badge&color=FFDD00)](https://github.com/9499758-wq)
[![Profile Views](https://komarev.com/ghpvc/?username=9499758-wq&style=for-the-badge&color=32D74B)](https://github.com/9499758-wq)

---

</div>

## 🌌 开发者概述与工程哲学 (Engineering Philosophy)

你好！我是 **lanny98801**。我是一名深耕于 **自主 AI 智能体底层架构 (Autonomous AI Agents)**、**macOS 原生精工开发 (SwiftUI & Metal)**、**系统级安全监控** 与 **开发者生产力工具** 的全栈工程师与独立开发者。

在技术选型与工程实践中，我始终遵循以下四大核心原则：
1. 🎯 **极致工程鲁棒性 (Engineered for Robustness)**：在自主智能体与底层系统中，设计完备的状态机、WAL 日志回滚与断点自愈机制，杜绝黑盒不可控。
2. 🍏 **原生与性能至上 (Native Craftsmanship)**：善用系统原生 API（SwiftUI、Metal、AppKit、POSIX IPC），坚持极低 CPU 与内存能耗，追求像素级丝滑交互。
3. ⚡ **无感与高可用交付 (Zero-Friction Developer Experience)**：打造零依赖、即插即用、开箱即得的工程工具（如纯 Python ASAR 解析器与自动化部署流水线）。
4. 🙏 **敬畏开源与持续演进 (Respect for Upstream & Open Source Ethics)**：在站在开源巨人的肩膀上进行二次开发时，始终清晰致敬原作者并贡献有实质价值的定制增强。

---

## 🪐 深度工程项目详解 (In-Depth Project Showcases)

---

### 🤖 1. 自主 AI 智能体与底层引擎架构 (Autonomous AI Agents)

#### 🧠 [Hermes Agent & Gateway](https://github.com/9499758-wq/hermes-agent) — 高并发自主 AI 智能体运行时与多模型路由网关
> **技术栈**：`Python 3.11+` · `SQLite (WAL 模式)` · `Phoenix Engine` · `Textual (TUI)` · `TypeScript / React (WebUI)` · `FastAPI`

* 💡 **设计初衷与解决痛点**：传统大模型 Agent 在执行多步复杂任务时，普遍面临“推理中断后上下文丢失”、“状态黑盒不可追溯”、“缺少轻量且直观的可视化交互”三大痛点。
* 🏗️ **核心架构实现**：
  * **WAL 状态持久化与回滚引擎**：基于 SQLite WAL 预写日志自研断点快照机制，在智能体遭遇网络震荡或模型限流时支持亚秒级状态回滚与无缝自愈；
  * **Phoenix 动态模型网关**：实现多推理后端（Gemini / Claude / 本地大模型）的动态热插拔、负载均衡与故障转移；
  * **双模态无缝交互控制台**：
    * `Hermes TUI`：基于 Rich / Textual 构建的极客终端交互面板，支持流式 Token 监控与快捷按键操作；
    * `HermesWebUI`：现代响应式可视化仪表盘，提供执行轨迹可视化回放、技能库管理与参数热调配；
  * **Batch Runner 批量推理调度器**：支持并发测试用例批量评估与输出一致性校验。

---

#### 🧩 **Codex Multi-Agent Orchestrator** — 复杂工程级多智能体协同流水线
> **技术栈**：`Multi-Agent Topology` · `Subagent IPC` · `Checkpoint / Rollback` · `Sandboxed Execution`

* 💡 **设计初衷**：解决复杂工程任务无法由单智能体完成的瓶颈，实现真正的“多工种智能体协同编队”。
* 🏗️ **核心技术特性**：
  * **任务递归分解与分发**：主智能体负责全局规划与拓扑调度，子智能体（Research / Coder / Debugger）在隔离上下文中并发执行并聚合汇报；
  * **全链路 Checkpoint 状态快照**：支持阶段性任务成果自动固化与一键安全回滚；
  * **安全沙箱与终端工具链交互**：受控执行本地 Bash/Python 指令，具备敏感权限动态确认机制。

---

### 🏝️ 2. macOS 原生精工与系统级交互 (Native macOS & Enhanced Custom Forks)

#### 🏝️ [Atoll for macOS (二次开发定制版)](https://github.com/9499758-wq/Atoll) — Mac 刘海屏灵动岛交互增强系统
> **致敬上游**：基于原作者 **[Ebullioscopic/Atoll](https://github.com/Ebullioscopic/Atoll)** 开源项目进行深度二次开发与定制增强  
> **技术栈**：`Swift 5.9+` · `SwiftUI` · `Apple Metal Shaders` · `AppKit` · `MediaRemote framework` · `IOKit`

* 💡 **项目定位**：将 MacBook 的顶部屏幕刘海化身为极具科技感与实用性的聚焦控制中心。
* 🛠️ **我们的二次开发增强亮点**：
  * **粒子级 FluentAnim 天气动效重构**：重新优化并补全了雪花、暴雨、云层浮动、多云转晴等全套 70+ 帧序列的高清平滑渲染；
  * **`AtollBridge` 跨进程工具链**：自研基于 Python & Swift 的 IPC 桥接层，允许外部脚本或 AI Agent 动态向灵动岛发送自定义通知与状态挂载；
  * **自动化一键部署体系**：编写了 `deploy-atoll.sh` 脚本与 AppleScript 自动化本地构建编译与安装流水线；
  * **全功能模块矩阵**：
    * 🎵 **媒体控制与桌面歌词**：深度适配 Apple Music、Spotify、QQ音乐、网易云音乐，内置 Metal 频谱动效；
    * 🔒 **锁屏扩展小组件**：锁屏下展示音乐歌词、蓝牙外设（AirPods/鼠标/键盘）电量、天气预报与番茄钟；
    * 📊 **轻量系统性能监视**：基于 IOKit 与 SMC 低开销采集 CPU/GPU、内存压力与网络速率。

---

#### 🐱 [RunCatNeo (二次开发版)](https://github.com/9499758-wq/RunCatNeo) — 轻量级状态栏动态猫咪监视器
> **致敬上游**：基于原作者 **[Kyome (Takuto Nakamura)](https://github.com/Kyome22/RunCat_for_macOS)** 开源的 RunCat 深度定制  
> **技术栈**：`Swift` · `AppKit` · `Mach Kernel API` · `UserDefaults Store`

* 🛠️ **二次开发增强亮点**：
  * **非线性性能映射与平滑插值**：重构了 CPU 负载与跑动帧率之间的映射算法，在高负载突发时跑动过渡更加平滑自然；
  * **RunnerBar 状态管理架构重构**：扩展了多套自定义像素动图支持与独立配置持久化存储；
  * **极致能效优化**：优化后台采样定时器，CPU 占用率常态保持在 0.1% 以下。

---

#### 📊 [Stats Custom (二次开发版)](https://github.com/9499758-wq/Stats-Custom) — 全能菜单栏硬件性能监控套件
> **致敬上游**：基于原作者 **[exelban (Stats)](https://github.com/exelban/stats)** 源码定制  
> **技术栈**：`Swift` · `IOReport` · `SMC Helper` · `Modular Architecture`

* 🛠️ **定制增强亮点**：
  * 深度定制 CPU/GPU、内存压力、电池健康度、传感器温度与网络上下行速率展示；
  * 定制化极简仪表盘与专属中文本地化界面适配。

---

### 🚀 3. 开发者生态与系统安全工具 (Developer Tooling & Security)

#### 🚀 [Antigravity Chinese Patch](https://github.com/9499758-wq/antigravity-chinese-patch) — Google Antigravity 终极全套深度汉化补丁
> **技术栈**：`Python 3` · `Electron ASAR Binary Parser/Packer` · `DOM MutationObserver` · `Ad-hoc Code Signing` · `RegEx Engine`

* 💡 **解决的核心痛点**：市面已有汉化方案存在“系统弹窗英文”、“报错拦截英文”、“会话自动命名为英文”以及“依赖繁琐/后台高占用”等严重缺陷。
* 🏗️ **全链路五层立体汉化架构**：
  1. **纯 Python 零依赖物理注入**：内置纯 Python 编写的 ASAR 二进制解包与重组算法，**彻底摆脱 Node.js、npm 或 asar 外部工具依赖**；
  2. **1200+ 词条动态拦截引擎**：基于 `MutationObserver` 实时监听 DOM 树变动、Shadow DOM、iframe 及各种异步 React 渲染属性；
  3. **原生系统级弹窗深度覆写**：完整汉化欢迎向导（`wizardHtml.js`）、退出确认弹窗（`main.js`）、检查更新（`updater.js`）及工作区选择器；
  4. **全量异常与 Gemini 过滤器汉化**：通过自适应正则精准匹配 *“This request was blocked by Gemini's filters...”* 拆分段落与超链接，汉化 60+ 类系统与网络错误；
  5. **全局智能体中文命名规则锁定**：通过 `~/.gemini/config/GEMINI.md` 注入底层指令，彻底根治新建会话标题自动生成纯英文的行业痛点；
  6. **macOS 自动代码重签名**：内置 Ad-hoc 深度签名逻辑，杜绝打包后“应用损坏”报错，支持 `--restore` 一键回滚。

---

#### 🖨️ [PrintSentinel](https://github.com/9499758-wq/PrintSentinel) — 打印服务安全监控与敏感运单队列审计系统
> **技术栈**：`C# (.NET 8 / ASP.NET Core)` · `Winspool / CUPS API` · `Spooler Parser` · `Vanilla HTML5 / Web UI`

* 💡 **项目定位**：针对企业打印合规与物流出单场景打造的轻量级打印审计中枢。
* 🏗️ **核心技术特性**：
  * **打印任务全生命周期拦截与追踪**：实时监控 Spool 打印缓冲队列，捕获作业提交、渲染、打印完毕与异常状态；
  * **敏感运单与数据正则识别引擎**：内置顺丰 (SF)、圆通 (YT)、韵达 (YD)、京东 (JD) 等全主流物流运单号及关键隐私字段自动识别；
  * **开箱即用的轻量 Web 管理后台**：原生提供可视化任务列表查询、日志检索与异常打印阻断。

---

### 🌸 4. 创意产品与私域小程序 (Creative Products)

* 🌸 **[Immersive Flower Miniapp](https://github.com/9499758-wq/immersive-flower-miniapp)**：像素风鲜花养成 + 真花市集微信小程序，结合游戏化像素种植、稀有花卉收集、社交裂变与花晶币积分商城，打造高留存高复购的私域电商范例。
* 📷 **云南机位云相册 (Yunnan Photo Cloud)**：专为摄影爱好者打造的机位探索、参数分享与云相册社群小程序。

---

## 🛠️ 全景技术栈与武器库 (Comprehensive Arsenal)

<div align="center">

### 💻 核心编程语言 (Languages)
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/Shell_Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />

### ⚙️ 系统底层、图形与框架 (Systems, Graphics & Frameworks)
<img src="https://img.shields.io/badge/SwiftUI-007ACC?style=for-the-badge&logo=swift&logoColor=white" alt="SwiftUI" />
<img src="https://img.shields.io/badge/Apple_Metal-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Metal" />
<img src="https://img.shields.io/badge/AppKit-1D1D1F?style=for-the-badge&logo=apple&logoColor=white" alt="AppKit" />
<img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
<img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />

### 🛡️ 智能体与安全逆向生态 (AI Agents & Security)
<img src="https://img.shields.io/badge/Model_Context_Protocol_(MCP)-8A2BE2?style=for-the-badge" alt="MCP" />
<img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=for-the-badge&logo=google&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge" alt="BurpSuite" />
<img src="https://img.shields.io/badge/Frida-2D3748?style=for-the-badge" alt="Frida" />
<img src="https://img.shields.io/badge/radare2-000000?style=for-the-badge" alt="radare2" />

</div>

---

## 📈 数据统计与活跃度 (GitHub Stats & Activity)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=9499758-wq&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="49%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=9499758-wq&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=9499758-wq&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="98%" />
</div>

---

<div align="center">
  <br/>
  <b>⚡ <i>"Simplicity is the prerequisite for reliability; elegance is the signature of craftsmanship."</i></b>
  <br/><br/>
  <i>欢迎关注、交流、提出 Issue 或 Star 支持！🌟</i>
</div>
