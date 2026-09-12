# Haifa Agent

**简体中文** · [English](README.en.md)

> 面向真实产品约束的 Java 优先 Agent Runtime 与 SDK。

Haifa Agent 帮助 AI Agent 开发者和软件工程师在 Java 与 Spring 生态中构建可靠的智能体应用。你可以从轻量集成开始，只在产品需要时再加入模型调用、工具、MCP、Skill、Memory、Workspace 访问、策略、凭据、持久化与恢复等能力。

## 为什么选择 Haifa Agent

- **从原型走向产品。** 当 Agent 必须与业务规则、工具调用和可持久化状态协同工作时，不再局限于一次模型响应。
- **可推理的 Runtime 行为。** Run 生命周期、能力边界、策略决策与恢复行为均明确且可测试，而不是隐藏在黑盒中。
- **Java 优先，按需使用 Spring。** Core 保持轻量、Java 原生；在接入已有服务时，可选择 Spring Boot 支持。

## 已在四类产品实践中落地

Runtime 与 SDK 已在四类产品实践中复用。它们在共享基础之上处理长流程、受控能力、持久化状态与恢复，同时不把所有产品语义强行放入 Core。

- **Coding Agent** — 可恢复的 Coding Session 与受控的开发者工作流。
- **Personal Assistant** — 在受信任本机宿主中运行的交互式助理产品。
- **Mission** — 跨多个任务的持久任务规划与执行。
- **Deep Research** — 有边界、关注证据的研究工作流。

## 从这里开始

| 仓库 | 适合从这里开始 |
| --- | --- |
| [haifa-agent](https://github.com/haifa-agent/haifa-agent) | Runtime、SDK、Agent 应用与示例 |
| [haifa-agent-test-config](https://github.com/haifa-agent/haifa-agent-test-config) | 共享测试配置 |
| [haifa-agent-evals](https://github.com/haifa-agent/haifa-agent-evals) | Agent 评测套件与案例 |
| [haifa-agent-eval-infra](https://github.com/haifa-agent/haifa-agent-eval-infra) | 评测基础设施 |
| [haifa-agent-autonomous-delivery-assets](https://github.com/haifa-agent/haifa-agent-autonomous-delivery-assets) | 自主交付资产 |
