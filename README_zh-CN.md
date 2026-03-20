<div align="center">

# Zora

**AI 原生浏览器内核**

**浏览器不再以“页面渲染”为核心，而是以“任务执行”为核心。**

---

[![Rust](https://img.shields.io/badge/github-repo-blue?logo=rust)](https://rust-lang.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

[English](README.md) | [简体中文](README_zh-CN.md)

</div>

> ⚠️ **开发状态**：项目当前仍在积极开发中，功能和 API 可能会发生变化，请谨慎用于生产环境。

## 项目简介

**Zora 是一个使用 Rust 构建的 AI 原生浏览器内核。**

它打破了传统浏览器以“渲染”为核心的设计范式，将 Web 重新定义为一个**可执行环境（Executable Web Environment）**。

在 Zora 中：

- 网页会被解析为结构化的语义数据（**语义层 / Semantic Layer**）
- AI Agent 基于语义进行任务规划（**规划系统 / Planning System**）
- 所有操作通过高层语义化 Action 执行，而非直接操作 DOM

此外，Zora 提供：

- **Agent Memory**：支持跨任务的上下文记忆
- **状态感知执行（State-aware Execution）**
- **多步骤任务编排能力（Multi-step Orchestration）**

这使浏览器从“以人为中心的交互界面”，进化为“以 AI 为核心的执行引擎”。

> 网页不再只是用户界面，而是 AI 的运行环境。
