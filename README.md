# 零基础开工 · Zero2Dev

> 文科生与非科班的 AI 时代转码与独立开发实战指引  
> From zero to builder: a practical software delivery guide for non-CS creators.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/realchendahuang/zero2dev?style=social)](https://github.com/realchendahuang/zero2dev)
[![GitHub forks](https://img.shields.io/github/forks/realchendahuang/zero2dev?style=social)](https://github.com/realchendahuang/zero2dev/network/members)
[![GitHub issues](https://img.shields.io/github/issues/realchendahuang/zero2dev)](https://github.com/realchendahuang/zero2dev/issues)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/realchendahuang/zero2dev/pulls)
[![Follow @realchendahuang](https://img.shields.io/badge/Follow-%40realchendahuang-1DA1F2?logo=x&logoColor=white)](https://x.com/realchendahuang)

---

## 设立宗旨

随着 AI 编程助手与终端 Agent 的普及，传统的转码路径（先背语法、再刷几百道 LeetCode、最后背死板八股文）已经完全失效。

对于文科生、产品经理与非科班建造者而言，写出软件的关键不再是手敲每一行代码，而是**工坊手感与闭环交付能力**：
1. 抛弃题海战术，以交付一个真实解决自己痛点的小工具为起点；
2. 掌握与 Coding Agent 精准对齐需求的沟通范式，杜绝代码失控腐化；
3. 掌握现代免运维全托管栈，把软件零成本推向全球真实用户。

---

## 核心通关路径图

### 第一关：数字工坊手感建立
不要在死板的代码编辑器里迷失，先掌握开发者的基础底层环境：
- **终端心智**：会用基础文件路径跳转（ls, cd, pwd, cat），明白命令参数的输入输出；
- **纯文本信仰**：熟练运用 Markdown 记录需求与设计规范，理解一切配置皆文本；
- **Git 基础**：把 Git 当作随时可读档的时光机，掌握 status, add, commit, push, branch 基础指令。

### 第二关：与 Coding Agent 精确对齐需求
写不好代码往往是因为需求没写清。掌握规格驱动开发（Spec-Driven）：
- **禁止模糊口令**：别说帮我写个网站，而是明确写出输入数据、页面交互与异常提示；
- **单次只改一个最小切片**：每次对话只完成一个完整功能点并跑通测试，不要贪大求全；
- **保留架构底稿**：在项目根目录维护 ARCHITECTURE.md，让模型始终清楚项目全貌。

### 第三关：极简免运维技术栈
对独立新手而言，避开复杂的 Docker、K8s 和重量级后端数据库：
- **前端页面**：Vite + React / HTML5 + Tailwind CSS（组件样式开箱即用，免写繁琐 CSS）；
- **服务端接口**：Hono.js / Cloudflare Workers（几行代码搞定 API，毫无冷启动延迟）；
- **数据持久化**：Cloudflare D1（边缘 SQLite，零配置）或纯本地 JSON 文件；
- **全球分发**：Cloudflare Pages / GitHub Pages（推送 Git 自动秒级上线）。

### 第四关：常见报错速查与脱困 SOP
非科班新手最容易被一串红字报错劝退。遇到报错按三步走：
1. 抓取终端全量报错信息（包括 Error 堆栈第一行与最后一行）；
2. 把报错原文加出现问题的对应代码文件整体喂给模型；
3. 让模型先解释报错发生的物理原因，再提供可替换代码，绝不盲目试错。

---

## License

MIT License. Copyright (c) 2026 realchendahuang.
