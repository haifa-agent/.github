# Haifa Agent

> A Java-first Runtime and SDK for agent applications that have to survive real product constraints.

Haifa Agent helps AI agent developers and software engineers build dependable agent applications in Java and Spring. Start with a small integration, then add model calls, tools, MCP, skills, memory, workspace access, policy, credentials, persistence, and recovery only when your product needs them.

## Why Haifa Agent

- **From prototype to product.** Build beyond a single model response when your agent must work with business rules, tools, and durable state.
- **Runtime behavior you can reason about.** Run lifecycles, capability boundaries, policy decisions, and recovery behavior are explicit and testable rather than opaque.
- **Java first, Spring when it helps.** Keep the core lightweight and Java-native, with optional Spring Boot support for integration into existing services.

## Proven in product implementations

The Runtime and SDK already underpin Coding Agent, Personal Assistant, Mission, and Deep Research. These product implementations exercise a shared foundation for long-running work, controlled capabilities, durable state, and recovery without forcing all product semantics into the core.

## Start here

| Repository | Start here for |
| --- | --- |
| [haifa-agent](https://github.com/haifa-agent/haifa-agent) | Runtime, SDK, agent applications, and examples |
| [haifa-agent-test-config](https://github.com/haifa-agent/haifa-agent-test-config) | Shared test configuration |
| [haifa-agent-evals](https://github.com/haifa-agent/haifa-agent-evals) | Agent evaluation suites and cases |
| [haifa-agent-eval-infra](https://github.com/haifa-agent/haifa-agent-eval-infra) | Evaluation infrastructure |
| [haifa-agent-autonomous-delivery-assets](https://github.com/haifa-agent/haifa-agent-autonomous-delivery-assets) | Assets for autonomous delivery |

<details>
<summary><strong>中文介绍</strong></summary>

> 面向真实产品约束的 Java 优先 Agent Runtime 与 SDK。

Haifa Agent 帮助 AI Agent 开发者和软件工程师在 Java 与 Spring 生态中构建可靠的智能体应用。你可以从轻量集成开始，只在产品需要时再加入模型调用、工具、MCP、Skill、Memory、Workspace 访问、策略、凭据、持久化与恢复等能力。

### 为什么选择 Haifa Agent

- **从原型走向产品。** 当 Agent 必须与业务规则、工具调用和可持久化状态协同工作时，不再局限于一次模型响应。
- **可推理的 Runtime 行为。** Run 生命周期、能力边界、策略决策与恢复行为均明确且可测试，而不是隐藏在黑盒中。
- **Java 优先，按需使用 Spring。** Core 保持轻量、Java 原生；在接入已有服务时，可选择 Spring Boot 支持。

### 已在产品实践中落地

Runtime 与 SDK 已支撑 Coding Agent、Personal Assistant、Mission 和 Deep Research。它们在共享基础之上处理长流程、受控能力、持久化状态与恢复，同时不把所有产品语义强行放入 Core。

仓库入口请见上方 **Start here** 表格。

</details>
