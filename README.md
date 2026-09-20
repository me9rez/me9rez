<div align="center">

# me9rez

**前端开发 · GIS 与三维渲染 · AI Agent 工程师**

*前端出身，日常在浏览器里跟地图和几何数据打交道；这两年把一半时间花在「怎么让 AI Agent 更好用」上。*

[![Email Badge](https://img.shields.io/badge/1811783973@qq.com-EA4335?logo=gmail&logoColor=fff&style=flat)](mailto:1811783973@qq.com)
[![Blog Badge](https://img.shields.io/badge/Blog-me9rez.github.io-5684a1?logo=github&logoColor=fff&style=flat)](https://me9rez.github.io/blog)
![Location Badge](https://img.shields.io/badge/Base-广东-5684a1?style=flat)

</div>

---

## 🙋 关于我

- 🗺️ **地图与图形**：写过地形切片生成、MBTiles 读写、Quantized Mesh 解码等库，熟悉 WebGL / WebGPU 的三维地形与矢量渲染
- 🖥️ **前端工程**：Vue / React / TypeScript 是主力，日常在 Rsbuild、Vite 上做构建与工程化，顺手输出过 Electron、NW.js 的项目模板
- 🦀 **系统方向**：有 Rust 与 Node 原生扩展经验，性能敏感的部分习惯沉到更底层去做
- 🤖 **Agent 工程**：MCP Server、ACP 客户端、Agent 插件、本地模型网关都自己写过；关心的是模型怎么真正进到日常工作流里，而不是再多一个聊天窗口
- 🌱 **开源习惯**：造的轮子基本都开源，也长期在 maptalks 生态里提 issue、写插件

---

## 🛠️ 技术栈

**前端与构建**

![Vue.js Badge](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=fff&style=flat)
![React Badge](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=fff&style=flat)
![TypeScript Badge](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat)
![Vite Badge](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=fff&style=flat)
![Rsbuild Badge](https://img.shields.io/badge/Rsbuild-448AFF?style=flat)

**图形与 GIS**

![WebGL Badge](https://img.shields.io/badge/WebGL-fff?logo=WebGL&logoColor=5684a1&style=flat)
![WebGPU Badge](https://img.shields.io/badge/WebGPU-5684a1?logo=WebGPU&logoColor=fff&style=flat)
![QGIS Badge](https://img.shields.io/badge/QGIS-5684a1?logo=qgis&logoColor=green&style=flat)
![PostgreSQL Badge](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat)

**运行时与工具**

![Rust Badge](https://img.shields.io/badge/Rust-000?logo=rust&logoColor=fff&style=flat)
![Node.js Badge](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=fff&style=flat)
![Docker Badge](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=fff&style=flat)
![Visual Studio Code Badge](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=vscodium&logoColor=fff&style=flat)
![GitHub Badge](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat)

<p align="center">
<img src="https://skillicons.dev/icons?i=html,css,js,ts,rust,python,vue,react,nodejs,rollupjs,webpack,vite,vitest,tauri,threejs,postgres,wasm,docker,github,pnpm,bun,deno,astro,nuxtjs&perline=6" />
</p>

---

## 🖥️ 精选项目

### 🗺️ GIS 与图形渲染

| 项目 | 一句话简介 | 语言 |
| - | - | - |
| [dem-dynamic-terrain](https://github.com/me9rez/dem-dynamic-terrain) | 从 DEM 数据生成地形切片，为三维地形服务提供瓦片 | `TypeScript` |
| [node-mbtiles](https://github.com/me9rez/node-mbtiles) | Node.js 读写 MBTiles 瓦片库，地图数据落地不必再绕 Python / GDAL | `TypeScript` |
| [quantized-mesh-decoder](https://github.com/me9rez/quantized-mesh-decoder) | Quantized Mesh 格式的 JavaScript 解码器，让浏览器直接读地形数据 | `TypeScript` |
| [gas-pipeline-edit-demo](https://github.com/me9rez/gas-pipeline-edit-demo) | 管网在线编辑示例：在地图上完成管线的绘制与编辑 | `TypeScript` |

### 🧰 工程化与效率工具

| 项目 | 一句话简介 | 语言 |
| - | - | - |
| [rsbuild-electron-template](https://github.com/me9rez/rsbuild-electron-template) | 用 Rsbuild 构建 Electron 应用的起步模板（内置 Prisma + SQLite + Svelte 示例） | `TypeScript` |
| [rsbuild-nwjs-app-template](https://github.com/me9rez/rsbuild-nwjs-app-template) | 用 Rsbuild 构建 NW.js 应用的模板，桌面端打包少踩几个坑 | `TypeScript` |
| [webhook](https://github.com/me9rez/webhook) | 轻量高性能的 WebHook 服务：一个 HTTP 请求触发系统命令，用于自动部署与数据同步（已发 npm） | `TypeScript` |
| [node-clipstash](https://github.com/me9rez/node-clipstash) | 把剪贴板里随手复制的链接，收进自己的知识库 | `TypeScript` |

### 🤖 AI Agent 工具链

| 项目 | 一句话简介 | 语言 |
| - | - | - |
| [llm-vision-mcp](https://github.com/me9rez/llm-vision-mcp) | MCP Server：借 OpenAI 兼容的视觉模型把图片转成文字描述，让 DeepSeek、GLM 这类文本模型也能看图；本地 stdio 运行，Claude Code / OpenCode 即插即用 | `JavaScript` |
| [workbuddy-proxy](https://github.com/me9rez/workbuddy-proxy) | 把 WorkBuddy / CodeBuddy 的模型代理成本地 OpenAI 兼容接口：浏览器登录、多账号、流式对话 | `JavaScript` |
| [dsh-workbuddy-experts](https://github.com/me9rez/dsh-workbuddy-experts) | DeepSeek Harness 插件：输入框里直接选专家，人设与技能按会话注入，选择状态跨重启保留 | `TypeScript` |
| [dsh-vlm-bridge](https://github.com/me9rez/dsh-vlm-bridge) | DSH 插件：提供 `vision_analyze` 工具，给纯文本 Agent 补上读图能力 | `JavaScript` |
| [openclaw-manager](https://github.com/me9rez/openclaw-manager) | 桌面端管理多个 OpenClaw 实例：多版本并行、启停重启、实时日志 | `TypeScript` |
| [electron-acp-ui](https://github.com/me9rez/electron-acp-ui) | 跨平台 ACP 客户端，一个界面连接 Claude、Codex、Copilot、Qwen、OpenCode 等 Agent | `Vue` |

> 更多项目见 [我的仓库列表](https://github.com/me9rez?tab=repositories)。觉得哪个轮子有用，Star 或 Issue 都是最好的打招呼方式。

---

## 📊 GitHub

<p align="center">
<img src="https://streak-stats.demolab.com?user=me9rez&theme=vue&hide_border=true" alt="GitHub Streak" />
</p>

---

<p align="center">
  <sub>愿你今天少踩一个坑 ✨</sub>
</p>
