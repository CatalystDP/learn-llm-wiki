---
tags: [实体, AI-Agent, 运行时]
created: 2026-06-20
updated: 2026-06-20
sources: ["[[2026-06-20-agent-harness-engineering-full-stack]]"]
---

# Agent Runtime

> 把 Agent 的编排决策转化为受控、可扩展执行的运行时底座。

## 简介

Agent Runtime 负责真正运行模型调用、工具动作和插件逻辑。图片列出的组成包括执行引擎、LLM 适配器、工具适配器、插件系统、安全沙箱以及并发与异步机制。

## 关键信息

- **类型**：概念 / 基础软件层
- **领域**：AI Agent 系统工程
- **职责**：执行、适配、隔离、资源控制、并发和错误处理
- **支持形态**：ReAct、Plan-and-Execute、Reflection、多智能体和自定义 Agent
- **相关概念**：[[Agent Harness]]、[[Agent 安全治理]]、[[Agent 可观测性]]

## 工程要点

- 用统一适配接口隔离模型与工具供应商差异。
- 默认限制工具权限、执行时间、资源额度和可访问数据。
- 对调用链设置超时、取消、幂等、重试与故障隔离机制。
- 把每次模型和工具执行暴露给追踪、审计与成本统计。

## 不同素材中的观点

- [[2026-06-20-agent-harness-engineering-full-stack|Agent Harness Engineering 全栈开发技术]]：把 Runtime 视为多种 Agent 类型共享的执行底座。

## 相关页面

- [[AI Agent 全栈工程]]
- [[Agent Harness]]
- [[Agent 安全治理]]
- [[Agent 可观测性]]
