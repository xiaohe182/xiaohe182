<div align="center">

<sub>ENGINEERING PORTFOLIO · XIAOHE182</sub>

# Hi, I'm He.

### 把真实需求，做成可用的系统。

Building practical systems, automation tools & thoughtful interfaces.

<p>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Vue_3-35495E?style=flat-square&logo=vuedotjs&logoColor=4FC08D" alt="Vue 3" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Node.js-233056?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
<img src="https://img.shields.io/badge/Electron-233056?style=flat-square&logo=electron&logoColor=9FEAF9" alt="Electron" />
<img src="https://img.shields.io/badge/Kotlin-233056?style=flat-square&logo=kotlin&logoColor=A97BFF" alt="Kotlin" />
</p>

[Selected work](#selected-work) · [Engineering focus](#engineering-focus) · [Workbench](#workbench)

</div>

---

我关注从界面到服务端的完整交付：让业务流程可执行，让重复操作可自动化，让失败路径可恢复。项目覆盖网页数据采集、订单履约、Android 数据同步，以及开发者工具。

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<sub>01 / DESKTOP AUTOMATION</sub>
<h3><a href="https://github.com/xiaohe182/collect">Collect Studio</a></h3>
<p><b>可视化网页数据采集工作台</b></p>
<p>从 DOM 点选到流程树编排，串联列表识别、滚动加载、分页与详情采集，导出结构化数据。</p>
<p><code>Electron</code> <code>Chromium</code> <code>JavaScript</code></p>
<p>工程重点：主进程与页面桥接、任务持久化、后台线程导出、分批备份。</p>
</td>
<td width="50%" valign="top">
<sub>02 / BUSINESS SYSTEMS</sub>
<h3><a href="https://github.com/xiaohe182/shop">OrderDesk</a></h3>
<p><b>轻量订单与数字商品履约系统</b></p>
<p>连接订单管理、支付状态轮询和限时交付，以原生 Web 技术实现可部署的业务流程。</p>
<p><code>Node.js</code> <code>JavaScript</code> <code>HTML / CSS</code></p>
<p>工程重点：幂等入单、用户数据隔离、交付凭证摘要存储与有效期管理。</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<sub>03 / MOBILE RELIABILITY</sub>
<h3><a href="https://github.com/xiaohe182/SmsBackup">SmsBackup</a></h3>
<p><b>Android 短信备份与可靠同步</b></p>
<p>在设备持有人主动授权后，将允许同步的短信写入本地队列，并提交到自定义服务器。</p>
<p><code>uni-app</code> <code>Kotlin / UTS</code> <code>SQLite</code></p>
<p>工程重点：WorkManager 指数退避、双重去重、幂等上传与离线队列。</p>
</td>
<td width="50%" valign="top">
<sub>04 / DEVELOPER TOOLS</sub>
<h3><a href="https://github.com/xiaohe182/accountManage">Codex Auth Admin</a></h3>
<p><b>可自托管的授权文件管理后台</b></p>
<p>集中处理已有授权文件的导入、启停、备注与导出，并支持 CLIProxyAPI 同步。</p>
<p><code>Vue 3</code> <code>Element Plus</code> <code>Node.js</code></p>
<p>工程重点：本地 JSON 持久化、加密授权文件存储与前后端联调。</p>
</td>
</tr>
</table>

## Engineering focus

| 方向 | 关注的问题 | 项目中的实践 |
| :--- | :--- | :--- |
| **产品与界面** | 如何把复杂操作变得清晰 | 管理后台、可视化流程编辑、任务工作台 |
| **自动化** | 如何连接页面、数据与流程 | DOM 识别、Chromium 集成、流程树执行 |
| **可靠性** | 如何处理重复、断网与失败 | 幂等键、本地队列、重试退避、结果备份 |
| **系统边界** | 如何划分访问与数据范围 | 用户数据隔离、限时凭证、主动授权 |

## Workbench

本地项目中的持续探索；以下项目尚未作为独立公开仓库发布。

- **Nebula** — Vue 3 + TypeScript 内容系统，博客前台 SSG 与管理后台 CSR 分流；配套 SQLite API、响应式图片处理及 S3 兼容对象存储。
- **Torna Script Studio** — 将 Torna / OpenAPI 文档与 cURL 解析连接起来，生成浏览器 JavaScript、Python 和 Axios / TypeScript 请求脚本。
- **AI Image Workbench** — 面向图片处理的 A/B 工作区，结合模型调用、异步任务轮询、透明抠图与画布精修。

---

<div align="center">
<sub>Clear interfaces. Explicit boundaries. Useful software.</sub><br />
<sub>清晰的界面 · 明确的边界 · 实用的软件</sub>
</div>
