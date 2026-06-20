---
tags: [实体, AI-Agent, 编排]
created: 2026-06-20
updated: 2026-06-20
sources: ["[[2026-06-20-agent-harness-engineering-full-stack]]"]
---

# Agent Harness

> 位于应用与运行时之间、负责组织 Agent 行为和生命周期的编排核心。

## 简介

Agent Harness 把业务目标转成可执行过程。图中将其拆为工作流编排、任务调度、策略路由、多智能体协作、状态管理和上下文管理，并把规划、记忆、工具调用、反思、学习、自适应列为核心能力。

## 关键信息

- **类型**：概念 / 架构层
- **领域**：AI Agent 系统工程
- **输入**：业务目标、上下文、状态、策略与可用能力
- **输出**：任务计划、路由决定、工具或 Agent 调用、状态变更
- **相关概念**：[[Agent Runtime]]、[[Agent 可观测性]]、[[Agent 安全治理]]

## 工程要点

- 将工作流、状态和策略从具体模型供应商中解耦。
- 明确持久状态、短期上下文与长期记忆的边界。
- 为路由、重试、超时、回退和人工接管定义显式策略。
- 多智能体只在角色分工或并行收益清晰时引入，否则会放大协调成本。

## 不同素材中的观点

- [[2026-06-20-agent-harness-engineering-full-stack|Agent Harness Engineering 全栈开发技术]]：把 Harness 定义为全栈架构的“编排核心”。

## 相关页面

- [[AI Agent 全栈工程]]
- [[Agent Runtime]]
- [[Agent 可观测性]]
- [[Agent 安全治理]]
