# Haifa Agent

简体中文 · [English](https://github.com/haifa-agent/.github/blob/master/profile/README.en.md) · [官网](https://haifa-portal.pages.dev/zh-cn/)

用 Haifa Agent SDK 把 Agent 接入 Java 应用，用 Agent Host 构建自己的编程客户端，或直接使用 Coding Agent 和 Super Harness 完成任务。

## 构建自己的应用

### Haifa Agent SDK

把模型、多轮对话和业务工具接进现有 Java 或 Spring Boot 应用。例如，把订单查询注册为工具，让 Agent 根据用户需求整理工单草稿，再交给应用原有的确认和提交流程。

[Java 快速开始](https://haifa-portal.pages.dev/zh-cn/docs/agent/get-started/quickstart/) · [Java 工具示例](https://haifa-portal.pages.dev/zh-cn/docs/agent/examples/typed-tool/)

### Agent Host（开发预览）

为代码审查、测试排障或内部工程工作台做自己的界面。客户端呈现会话、工具活动和审批，Agent Host 管理授权工作区并推进任务。可以对照终端和 Coding Web 的同任务示例，了解两种界面怎样接入本机 Host。Coding Web 也处于开发预览。

[Coding SDK 自建教程](https://haifa-portal.pages.dev/zh-cn/docs/agent/coding-sdk/) · [终端与 Web 示例](https://haifa-portal.pages.dev/zh-cn/docs/agent/coding-agent/#reference-products) · [Agent Host 协议与 API](https://haifa-portal.pages.dev/zh-cn/docs/agent/agent-host/)

## 直接使用

### Coding Agent

在项目目录打开终端，描述你想做的改动。跟着 Coding Agent 阅读代码、修改文件、运行构建和测试，并在需要时确认操作。

[下载 Coding Agent](https://github.com/haifa-agent/haifa-agent/releases/latest) · [查看任务演示](https://haifa-portal.pages.dev/zh-cn/docs/agent/coding-agent/#coding-task-demos)

### Super Harness

在本地工作台提供资料、说明目标，跟进执行和审批，再检查并下载生成的成果。例如，把几份调研资料整理成一份简报。Super Harness 复用字节跳动开源项目 DeerFlow 的界面与交互方式，由 Haifa Agent SDK 驱动任务执行。

[安装 Super Harness](https://haifa-portal.pages.dev/zh-cn/docs/super-harness/get-started/installation/) · [跟做第一次任务](https://haifa-portal.pages.dev/zh-cn/docs/super-harness/get-started/first-task/) · [DeerFlow 上游项目](https://github.com/bytedance/deer-flow)

## 共享执行基础

通用 SDK 和 Agent Host 都建立在 Haifa Agent Runtime 上，共享模型调用、工具执行、人工交互和运行状态管理。Haifa Agent 还内置 Personal Assistant，可用于本地对话和资料研究。

[产品与技术栈](https://haifa-portal.pages.dev/zh-cn/#product-stack) · [Haifa Agent 源码](https://github.com/haifa-agent/haifa-agent) · [Super Harness 源码](https://github.com/haifa-agent/haifa-agent-super-harness)
