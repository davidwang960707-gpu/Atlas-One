# Atlas One

<div align="center">

  <img src="https://github.com/davidwang960707-gpu.png" width="120" height="120" alt="王六 avatar" />

  <h3>Atlas One · Enterprise AI Workforce Platform</h3>

  <p>
    面向企业的 B/S 数智员工平台，以编排、协作、交付为核心，精准交付业务结果。
  </p>

  <p>
    <img src="https://img.shields.io/badge/B%2FS%20Architecture-Enterprise%20Platform-111827?style=for-the-badge&logo=cloudflare&logoColor=white" alt="B/S Architecture" />
    <img src="https://img.shields.io/badge/AI%20Workforce-Trusted%20%26%20Controlled-2563EB?style=for-the-badge&logo=openai&logoColor=white" alt="Trusted AI Workforce" />
    <img src="https://img.shields.io/badge/Xiaomi-Model%20Service-FF6900?style=for-the-badge&logo=xiaomi&logoColor=white" alt="Xiaomi Model Service" />
    <img src="https://img.shields.io/badge/Project%20Entry-README%20Only-22C55E?style=for-the-badge&logo=readme&logoColor=white" alt="Project Entry" />
  </p>

  <p>
在线体验：http://124.222.146.231
  </p>

</div>

---

## 一句话定位

**Atlas One 是一个面向企业场景的 B/S 数智员工平台。**

Atlas One 以**编排、协作、交付**为核心设计理念，面向 OPC 和初创团队高效管理数智员工队伍，把 AI 能力落到明确任务、协作过程和可交付的业务结果上。

Atlas One 更关注「执行是否安全、权限是否清楚、过程是否可审计、结果是否能被企业信任」。

它不是再做一个聊天窗口，也不是把 CLI 搬到 Web 页面里，更不是让每个用户在自己的本机上各自运行一套 Agent。

Atlas One 的核心，是把 Agent 能力组织成可管理、可控、可信的「数字员工」，并通过企业级平台统一提供访问、权限、审计、调度和治理。
<img width="3600" height="2016" alt="image" src="https://github.com/user-attachments/assets/839dd2fd-8610-40ed-b9a1-afa1469f1fb3" />
<img width="3600" height="2016" alt="image" src="https://github.com/user-attachments/assets/0fbbecc4-c596-4c32-8b46-d9293d2fa468" />


## 核心理念

Atlas One 围绕三个关键词设计：

- **编排**：把复杂任务拆解给合适的数字员工，让能力、上下文和任务路径有序流转。
- **协作**：让不同岗位的数字员工围绕同一业务目标接力工作，而不是各自孤立回答。
- **交付**：以最终业务结果为导向，关注任务是否完成、产物是否清楚、过程是否可追踪。
  <img width="3600" height="2016" alt="image" src="https://github.com/user-attachments/assets/2b70f9d3-9aa0-4e96-b306-dba5562d2a63" />


对 OPC 和初创团队来说，Atlas One 希望承担的是一套轻量但可靠的数智团队管理入口：不用从零搭建模型、权限和运行环境，就能让数字员工围绕真实业务目标开展工作。

## 为什么不是本地运行

Atlas One 坚持 B/S 架构的重要原因之一：企业级 AI 能力不应该散落在每台个人电脑上，而应该由平台统一提供稳定、可控、可追踪的模型服务。

本地 Agent 工具很适合个人开发者快速试验，但企业真正落地时，会遇到一组绕不开的问题：

- 凭证散落在个人电脑上，难以统一管理
- 文件、会话、记忆和日志分散在本地，难以审计
- 工具权限依赖个人配置，边界不够清晰
- 高危操作缺少统一审批与追踪
- 多人协作时缺少组织视角和责任归属
- 员工离职、换岗或设备更换时，数据与权限交接复杂

用户通过浏览器访问，运行、权限、数据、审计和治理由服务端集中承载，企业可以更清楚地知道：谁在用、用哪个数字员工、做了什么、有没有越权、结果在哪里。

## 和普通Agent/类Claw产品的区别

| 维度 | 通用Agent | Atlas One |
|---|---|---|
| 部署方式 | 本机运行、个人配置 | B/S 架构、服务端统一承载 |
| 模型服务 | 用户自行配置模型或 Key | 平台统一提供小米模型服务 |
| 使用对象 | 单个用户、单个 Agent | 企业团队、多名数字员工 |
| 安全边界 | 依赖本地环境和个人习惯 | 平台统一权限、审计和控制 |
| 数据归属 | 文件、会话、记忆多在本地 | 企业侧集中管理和追踪 |
| 能力组织 | 工具和模型围绕个人使用 | 技能、知识、工具围绕岗位配置 |
| 管理视角 | 个人工作台 | 数字员工队伍与组织治理 |
| 信任机制 | 相信使用者自己管好 | 平台让过程可见、权限可控、结果可追溯 |

所以 Atlas One 的重点不是「把 Agent 放进浏览器」，而是把 Agent 能力变成企业能放心使用、能持续管理的数字劳动力。

## 在线试用
Atlas One 仍处于预览阶段，功能、界面和部署方式都会持续变化。

Atlas One 对外试用阶段统一提供xiaomi大模型服务。

预览版会优先开放核心体验：进入平台、选择或调度数字员工、发起任务、观察流式响应、查看员工身份与任务上下文。当前阶段更重视真实可用的主路径，而不是把所有企业功能一次性铺满。

后台管理功能暂不对外开放。试用环境会由平台侧预先配置好数字员工、模型服务和基础运行策略，大家先体验前台使用流程即可。


## 目前试用环境部署在资源有限的虚拟机上，所以体验时可能出现：

- 首次访问稍慢
- 高峰期响应变慢
- 大任务执行时间较长
- 偶尔需要刷新或稍后再试

## 欢迎来试，欢迎认真挑刺，也请先对这台预览机温柔一点，如果页面短暂不可用，大概率不是项目消失了，而是虚拟机正在努力把前端、后端、数据库和 Agent 运行环境一起扛住。


## 适合谁关注

- 正在关注 AI Agent 企业落地的人
- 想把 AI 从「聊天助手」推进到「数字员工」的人
- 需要用数智团队提升交付效率的 OPC 和初创团队
- 需要企业内部 AI 工作台、审计、权限和流程治理的人
- 关注 B/S 架构下 Agent 安全运行与集中管控的人
- 想观察一个 AI 原生企业产品从预览版逐步长出来的开发者、设计师和产品同学

## 反馈方式

欢迎通过 GitHub Issues 留下反馈。

如果你遇到问题，可以尽量附上：

- 发生问题的大致时间
- 你当时正在尝试的操作
- 页面提示或错误现象
- 是否可以稳定复现

如果只是产品建议，也完全可以直接说人话，不需要写成正式报告。比如「这个员工不像员工，更像套了名字的聊天机器人」这种反馈就很有价值。

## License

本仓库当前仅用于 Atlas One 项目入口页与公开说明，不包含完整项目源码。

---

<div align="center">

  <b>Atlas One：让 Agent 成为企业可管理、可控、可信的数字员工。</b>

</div>
