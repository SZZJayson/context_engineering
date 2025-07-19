# Context Engineering for AI Agents
# AI智能体上下文工程指南

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![中文](https://img.shields.io/badge/README-中文-red.svg)](./README_CN.md)

> **Context Engineering**: The art and science of optimizing AI agent interactions through strategic context management, prompt engineering, and system architecture design.

> **上下文工程**: 通过战略性上下文管理、提示工程和系统架构设计来优化AI智能体交互的艺术与科学。

## 🌟 Overview | 概述

This repository provides comprehensive guidance, best practices, and practical implementations for building production-ready AI agents using advanced context engineering techniques. Whether you're building chatbots, autonomous agents, or complex AI systems, this guide will help you optimize performance, reduce costs, and improve reliability.

本仓库提供全面的指导、最佳实践和实际实现，帮助你使用先进的上下文工程技术构建生产就绪的AI智能体。无论你在构建聊天机器人、自主智能体还是复杂的AI系统，本指南都将帮助你优化性能、降低成本并提高可靠性。

## 🎯 Why Context Engineering Matters | 为什么上下文工程很重要

**Performance Impact | 性能影响:**
- 🚀 **10x cost reduction** through KV-cache optimization | 通过KV-cache优化实现10倍成本降低
- ⚡ **Faster inference** with optimized context management | 通过优化上下文管理实现更快推理
- 🎯 **Better accuracy** through strategic attention manipulation | 通过战略性注意力操控提高准确性
- 🔄 **Improved reliability** with robust error handling | 通过强大的错误处理提高可靠性

## 📚 Documentation | 文档

### Core Concepts | 核心概念
- [**Best Practices**](./docs/best-practices.md) - 6 essential context engineering principles | 6个核心上下文工程原则
- [**Development Workflow**](./docs/workflow.md) - Standardized development process | 标准化开发流程
- [**Examples & Case Studies**](./docs/examples.md) - Real-world implementations | 真实世界实现案例

### Quick Start | 快速开始
- [**Implementation Templates**](./templates/) - Ready-to-use project templates | 即用型项目模板
- [**Code Examples**](./examples/) - Practical code implementations | 实用代码实现

## 🏗️ The 6 Pillars of Context Engineering | 上下文工程的6大支柱

### 1. 🎯 KV-Cache Optimization | KV-Cache优化
Maximize cache hit rates for 10x cost savings and faster inference.
最大化缓存命中率，实现10倍成本节省和更快推理。

```python
# ✅ Good: Stable prompt prefix
SYSTEM_PROMPT = "You are an AI assistant. Date: 2024-07-19"

# ❌ Bad: Dynamic timestamp breaks cache
SYSTEM_PROMPT = f"You are an AI assistant. Time: {datetime.now()}"
2. 🎭 Tool Masking | 工具掩码
Control agent behavior through smart masking instead of dynamic tool removal.
通过智能掩码而非动态工具移除来控制智能体行为。

3. 💾 File System as Context | 文件系统作为上下文
Treat the file system as unlimited, persistent external memory.
将文件系统视为无限的、持久的外部记忆。

4. 🔄 Attention Manipulation | 注意力操控
Keep agents focused on goals through strategic repetition and positioning.
通过战略性重复和定位保持智能体对目标的专注。

5. 🚨 Error Preservation | 错误保留
Learn from failures by keeping error context instead of hiding it.
通过保留错误上下文而不是隐藏它来从失败中学习。

6. 🎨 Diversity Management | 多样性管理
Prevent few-shot backfire through controlled context variation.
通过受控的上下文变化防止few-shot反噬。

🚀 Quick Start Guide | 快速开始指南
1. Clone the Repository | 克隆仓库
Bash

git clone [https://github.com/yourusername/context-engineering.git](https://github.com/yourusername/context-engineering.git)
cd context-engineering
2. Choose Your Use Case | 选择你的用例
Bash

# For a new AI agent project
cp -r templates/agent-project my-agent

# For context optimization of existing system
cp templates/requirements.md my-project/
cp templates/design.md my-project/
3. Follow the Workflow | 遵循工作流程
Requirements Analysis | 需求分析 - Define what you are building

Technical Design | 技术设计 - Plan your context architecture

Implementation | 实施 - Apply the 6 pillars

Optimization | 优化 - Measure and improve

📊 Performance Metrics | 性能指标
Track these key metrics to measure context engineering success:
跟踪这些关键指标来衡量上下文工程的成功：

Metric	Target	Impact
KV-Cache Hit Rate	>80%	10x cost reduction
Average Context Length	<50K tokens	Faster inference
Tool Selection Accuracy	>95%	Better task completion
Error Recovery Rate	>90%	Improved reliability

导出到 Google 表格
🛠️ Technology Stack | 技术栈
This guide supports multiple LLM providers and frameworks:
本指南支持多种LLM提供商和框架：

LLM Providers | LLM提供商:

OpenAI GPT-4/GPT-3.5

Anthropic Claude

Google Gemini

Self-hosted models (vLLM, ollama)

Frameworks | 框架:

LangChain

LlamaIndex

Custom implementations

🤝 Contributing | 贡献
We welcome contributions! Please see our contributing guidelines for details.
我们欢迎贡献！详情请参阅我们的贡献指南。

📈 Roadmap | 路线图
[ ] Q3 2024: Advanced caching strategies | 高级缓存策略

[ ] Q4 2024: Multi-modal context engineering | 多模态上下文工程

[ ] Q1 2025: SSM (State Space Model) integration | SSM集成

[ ] Q2 2025: Distributed agent architectures | 分布式智能体架构

📄 License | 许可证
This project is licensed under the MIT License - see the LICENSE file for details.
本项目采用MIT许可证 - 详情请参阅LICENSE文件。

Star ⭐ this repository if you find it helpful!

如果你觉得有用，请给这个仓库点个星 ⭐！

Built with ❤️ for the AI developer community | 为AI开发者社区用心构建
