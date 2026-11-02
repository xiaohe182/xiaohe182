<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=170&section=header&text=xiaohe182&fontSize=46&fontColor=ffffff&animation=fadeIn&desc=Practical%20systems%20%C2%B7%20Web%20automation%20%C2%B7%20Developer%20tools&descSize=16&descAlignY=68" alt="banner" width="100%" />

### 把真实需求,做成可用的系统。

Building practical systems, automation tools & thoughtful interfaces — from UI to server, from data to delivery.

<img src="https://img.shields.io/badge/%F0%9F%94%8D-Collect%20Studio-233056?style=flat-square" alt="Collect Studio" />
<img src="https://komarev.com/ghpvc/?username=xiaohe182&style=flat-square&color=233056&label=PROFILE+VIEWS" alt="profile views" />

<p>
<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=ts,vue,react,nodejs,electron,rust,kotlin,html,css&perline=9" alt="tech stack" />
</a>
</p>

[项目矩阵](#-selected-work) · [工程关注点](#-engineering-focus) · [持续构建](#-currently-building)

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2&section=header" alt="divider" width="100%" />

</div>

我关注从界面到服务端的完整交付:让业务流程可执行,让重复操作可自动化,让失败路径可恢复。项目覆盖桌面自动化、系统工具、AI 图像工程、订单履约、移动端数据同步与开发者工具。

## 🧩 Selected work

<table>
<tr>
<td width="50%" valign="top">
<sub>01 / DESKTOP AUTOMATION · 旗舰</sub>
<h3><a href="https://github.com/xiaohe182/collect-studio">Collect Studio</a></h3>
<p><b>可视化网页数据采集工作台</b></p>
<p>Electron + 内置 Chromium,自动识别列表并在页面框选预览,滚动加载 / 自动翻页 / 流程树编排 / 详情采集,后台线程导出 CSV · JSON · Excel。</p>
<p><code>Electron</code> <code>Chromium</code> <code>IPC</code></p>
<sub>主进程桥接 · 流程树执行器 · 分批备份 · 后台线程导出</sub>
</td>
<td width="50%" valign="top">
<sub>02 / SYSTEMS TOOLING · RUST</sub>
<h3><a href="https://github.com/xiaohe182/heprint">HePrint</a></h3>
<p><b>替代 C-Lodop 的桌面打印服务</b></p>
<p>Rust + WebView2,单文件约 1.5MB 双击即用;HTTP + WebSocket 双协议,26 个 HE_ 前缀精选 API,TypeScript SDK 一等公民,端口错开可与 C-Lodop 共存。</p>
<p><code>Rust</code> <code>WebView2</code> <code>WebSocket</code></p>
<sub>单文件交付 · 双协议服务 · TS SDK · 零依赖安装</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>03 / AI ENGINEERING</sub>
<h3><a href="https://github.com/xiaohe182/ai-image-workbench">AI Image Workbench</a></h3>
<p><b>本地优先的 AI 图像工作台</b></p>
<p>换背景 / 换模特 / 透明抠图 / 画布精修,统一接入腾讯云 TokenHub 8 个图像模型,同步返回与任务轮询双模;零构建前端 + Node 标准库后端。</p>
<p><code>Node.js</code> <code>sharp</code> <code>TokenHub</code></p>
<sub>模型适配层 · 轮询状态机 · A/B 工作区 · 日志脱敏</sub>
</td>
<td width="50%" valign="top">
<sub>04 / BUSINESS SYSTEMS</sub>
<h3><a href="https://github.com/xiaohe182/orderdesk">OrderDesk</a></h3>
<p><b>轻量订单与数字商品履约系统</b></p>
<p>连接订单管理、支付状态轮询和限时交付,以原生 Web 技术实现可部署的业务流程。</p>
<p><code>Node.js</code> <code>JavaScript</code> <code>HTML / CSS</code></p>
<sub>幂等入单 · 用户数据隔离 · 交付凭证摘要存储</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>05 / MOBILE RELIABILITY</sub>
<h3><a href="https://github.com/xiaohe182/sms-backup">SmsBackup</a></h3>
<p><b>Android 短信备份与可靠同步</b></p>
<p>在设备持有人主动授权后,将允许同步的短信写入本地队列,并提交到自定义服务器。</p>
<p><code>uni-app</code> <code>Kotlin / UTS</code> <code>SQLite</code></p>
<sub>WorkManager 指数退避 · 双重去重 · 幂等上传</sub>
</td>
<td width="50%" valign="top">
<sub>06 / DEVELOPER TOOLS</sub>
<h3><a href="https://github.com/xiaohe182/codex-auth-admin">Codex Auth Admin</a></h3>
<p><b>可自托管的授权文件管理后台</b></p>
<p>集中处理已有授权文件的导入、启停、备注与导出,并支持 CLIProxyAPI 同步。</p>
<p><code>Vue 3</code> <code>Element Plus</code> <code>Node.js</code></p>
<sub>本地 JSON 持久化 · 加密授权文件存储 · 前后端联调</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>07 / AI TOOLING</sub>
<h3><a href="https://github.com/xiaohe182/moreMcp">moreMcp</a></h3>
<p><b>个人 AI 能力注册中心</b></p>
<p>以 registry.yml 为唯一事实源,统一管理 MCP Server 与技能,为 Codex / Claude Code / Cursor / ZCode 生成编辑器专属配置,按 Profile 分档启用。</p>
<p><code>YAML</code> <code>MCP</code> <code>Profiles</code></p>
<sub>单一事实源 · 编辑器适配器 · 最小启用原则</sub>
</td>
<td width="50%" valign="top">
<sub>08 / WEB GAME · 在线可玩</sub>
<h3><a href="https://github.com/xiaohe182/PlantsVsZombies">Plants vs. Zombies Web</a></h3>
<p><b>植物大战僵尸网页版复刻</b></p>
<p>原生 JavaScript 实现,免安装。GitHub Pages 在线试玩:<a href="https://xiaohe182.github.io/PlantsVsZombies/">xiaohe182.github.io/PlantsVsZombies</a></p>
<p><code>JavaScript</code> <code>HTML5</code> <code>Game</code></p>
<sub>零依赖 · 纯前端 · 一键部署静态托管</sub>
</td>
</tr>
</table>

## 🎯 Engineering focus

| 方向 | 关注的问题 | 项目中的实践 |
| :--- | :--- | :--- |
| **产品与界面** | 如何把复杂操作变得清晰 | 可视化流程编辑、A/B 工作区、管理后台 |
| **自动化** | 如何连接页面、数据与流程 | DOM 识别、Chromium 集成、流程树执行 |
| **可靠性** | 如何处理重复、断网与失败 | 幂等键、本地队列、重试退避、结果备份 |
| **系统边界** | 如何划分访问与数据范围 | 用户数据隔离、限时凭证、主动授权 |

## 🔨 Currently building

本地项目中的持续探索;以下项目尚未作为独立公开仓库发布。

- **Nebula** — Vue 3 + TypeScript 内容系统,博客前台 SSG 与管理后台 CSR 分流;配套 SQLite API、响应式图片处理及 S3 兼容对象存储。
- **Torna Script Studio** — 将 Torna / OpenAPI 文档与 cURL 解析连接起来,生成浏览器 JavaScript、Python 和 Axios / TypeScript 请求脚本。

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=110&section=footer" alt="footer" width="100%" />

<sub>**Clear interfaces. Explicit boundaries. Useful software.**</sub><br />
<sub>清晰的界面 · 明确的边界 · 实用的软件</sub>

</div>
