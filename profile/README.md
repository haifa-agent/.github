# Haifa Agent

Haifa Agent helps AI agent developers and software engineers build dependable agent applications in Java and Spring.<br>
It provides a composable runtime and SDK for model calls, tools, MCP, skills, memory, workspace access, policy, credentials, persistence, and recovery.<br>
You can begin with a small agent integration and add only the capabilities your product actually needs.<br>
Its runtime is designed for the engineering problems behind long-running agent work, including failures, restarts, approvals, external side effects, and configuration changes.<br>
Haifa Agent is built for the point where an agent prototype becomes a real product: when model output must coexist with business rules, tools, and durable state.<br>
Instead of hiding the hard parts behind opaque magic, it makes run lifecycles, capability boundaries, policy decisions, and recovery behavior explicit and testable.<br>
The result is a Java-native foundation that lets teams move quickly without giving up control over safety, reproducibility, or operational clarity.<br>
The project keeps its core Java-first, while optional Spring Boot support makes it practical to integrate into existing services.

Haifa Agent 面向 AI Agent 开发者和软件工程师，帮助你在 Java 与 Spring 生态中构建可靠的智能体应用。<br>
它提供可组合的 Runtime 与 SDK，覆盖模型调用、工具、MCP、Skill、Memory、Workspace 访问、策略、凭据、持久化与恢复。<br>
你可以先从一个轻量的 Agent 集成开始，只在产品确实需要时再增加能力。<br>
对于长流程中的失败、重启、审批、外部副作用和配置变化等工程问题，Runtime 提供清晰且可测试的运行语义。<br>
Haifa Agent 面向 Agent 原型走向真实产品的阶段：模型输出需要与业务规则、工具调用和可持久化状态协同工作。<br>
它不以黑盒方式掩盖复杂性，而是将 Run 生命周期、能力边界、策略决策与恢复行为明确化、可测试化。<br>
团队因此可以在保持安全性、可复现性和运行可见性的同时，更快地交付 Java 原生的 Agent 产品。<br>
项目坚持 Java 优先的核心设计，并提供可选的 Spring Boot 支持，方便接入已有服务。

## Repositories / 仓库

| Repository | Purpose / 用途 |
| --- | --- |
| [haifa-agent](https://github.com/haifa-agent/haifa-agent) | Runtime, SDK, and agent applications / Runtime、SDK 与 Agent 应用 |
| [haifa-agent-test-config](https://github.com/haifa-agent/haifa-agent-test-config) | Shared test configuration / 共享测试配置 |
| [haifa-agent-evals](https://github.com/haifa-agent/haifa-agent-evals) | Agent evaluation suites / Agent 评测套件 |
| [haifa-agent-eval-infra](https://github.com/haifa-agent/haifa-agent-eval-infra) | Evaluation infrastructure / 评测基础设施 |
| [haifa-agent-autonomous-delivery-assets](https://github.com/haifa-agent/haifa-agent-autonomous-delivery-assets) | Assets for autonomous delivery / 自主交付资产 |
