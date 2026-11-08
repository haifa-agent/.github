# Haifa Agent

[简体中文](https://github.com/haifa-agent) · English · [Website](https://haifa-portal.pages.dev/en/)

Add agents to Java applications with the Haifa Agent SDK, build a coding client with Agent Host, or get to work with Coding Agent and Super Harness.

## Build your own application

### Haifa Agent SDK

Bring models, conversations, and business tools into an existing Java or Spring Boot application. For example, expose order lookup as a tool, let the agent draft a support ticket, and hand the draft back to your application's review and submission flow.

[Java quickstart](https://haifa-portal.pages.dev/en/docs/agent/get-started/quickstart/) · [Java tool example](https://haifa-portal.pages.dev/en/docs/agent/examples/typed-tool/)

### Agent Host (developer preview)

Build an interface for code review, test troubleshooting, or an internal engineering workspace. Your client displays sessions, tool activity, and approvals. Agent Host manages authorized workspaces and runs the task. Compare the same task in the terminal and Coding Web to see how both connect to a local Host. Coding Web is also in developer preview.

[Build a client with the Coding SDK](https://haifa-portal.pages.dev/en/docs/agent/coding-sdk/) · [Terminal and web examples](https://haifa-portal.pages.dev/en/docs/agent/coding-agent/#reference-products) · [Agent Host protocol and API](https://haifa-portal.pages.dev/en/docs/agent/agent-host/)

## Use the applications

### Coding Agent

Open a terminal in your project and describe the change you want. Follow Coding Agent as it reads code, edits files, and runs builds and tests. Review actions that require your approval.

[Download Coding Agent](https://github.com/haifa-agent/haifa-agent/releases/latest) · [Watch the task demos](https://haifa-portal.pages.dev/en/docs/agent/coding-agent/#coding-task-demos)

### Super Harness

Add source material and describe the task in a local workspace. Follow progress, handle approvals, and inspect or download the finished files. For example, turn a set of research notes into a briefing. Super Harness reuses the interface and interactions from ByteDance's open-source DeerFlow project and runs tasks through the Haifa Agent SDK.

[Install Super Harness](https://haifa-portal.pages.dev/en/docs/super-harness/get-started/installation/) · [Complete your first task](https://haifa-portal.pages.dev/en/docs/super-harness/get-started/first-task/) · [DeerFlow upstream](https://github.com/bytedance/deer-flow)

## Shared execution

The general SDK and Agent Host both build on Haifa Agent Runtime for model calls, tool execution, human interaction, and run state. Haifa Agent also includes Personal Assistant for local conversations and research.

[Products and technology stack](https://haifa-portal.pages.dev/en/#product-stack) · [Haifa Agent source](https://github.com/haifa-agent/haifa-agent) · [Super Harness source](https://github.com/haifa-agent/haifa-agent-super-harness)
