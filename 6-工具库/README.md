# 🛠️ 工具库项目

系统工具库、驱动程序、硬件集成、LLM 推理等底层工具库。

## 项目列表

### 1. CSerialPort
**描述**: 轻量级跨平台串口类库  
**特性**:
- 基于 C++ 开发
- 跨平台支持 (Windows、Linux、macOS)
- 轻量级设计
- 易于集成

**功能**:
- 串口数据读写
- 波特率配置
- 超时控制
- 实时通信

**应用场景**:
- 单片机通信
- 嵌入式设备控制
- IoT 设备集成
- 串行协议实现

**链接**: https://github.com/yanlei183/CSerialPort

---

### 2. nodejs-fingure
**描述**: R303 指纹模块集成方案  
**特点**:
- 多语言实现 (Node.js、C/51单片机)
- 与 CNC 机床集成
- 完整的接口规范

**支持平台**:
- Node.js (后端接口)
- 51单片机 (嵌入式实现)
- 三菱 CNC (工业应用)

**用途**:
- 生物识别集成
- 工业设备控制
- 访问控制系统
- 身份验证

**语言**: QML (主要)、JavaScript、C  
**链接**: https://github.com/yanlei183/nodejs-fingure

---

### 3. -public-apis
**描述**: 免费公开 API 汇总列表  
**内容**:
- 来自各行业的免费 API
- 按分类整理
- 包含使用文档链接

**用途**:
- API 集成参考
- 快速原型开发
- 三方服务调用

**特点**:
- 持续更新
- 社区贡献
- 易于查找

**链接**: https://github.com/yanlei183/-public-apis

---

### 4. codebase-memory-mcp
**描述**: 高性能代码智能 MCP 服务器  
**中文说明**:
- **codebase-memory-mcp** 是为 AI 编码代理设计的高性能代码智能引擎
- 将代码库索引到持久化知识图中
- 平均代码库索引耗时：毫秒级
- Linux 内核（28M 行代码，75K 文件）：3 分钟完成索引

**核心特性**:
- ⚡ **极速索引**: 平均代码库毫秒级索引，Linux 内核 3 分钟
- 🔧 **开箱即用**: 单个静态二进制文件，无需 Docker 或语言运行时
- 🌍 **158 种语言**: 内置 tree-sitter 语法，支持所有主流编程语言
- 💾 **高效内存**: 减少 99% 的 token 使用（~3,400 vs ~412,000）
- 🎯 **43+ 客户端支持**: 自动检测和配置主流 IDE 和编码助手
- 📊 **3D 可视化**: 内置图形化界面探索知识图
- 🔍 **15+ MCP 工具**: 
  - 代码搜索
  - 依赖追踪
  - 架构分析
  - 影响分析
  - 死代码检测
  - Cypher 查询
  - 跨服务分析
  - ADR（架构决策记录）管理

**支持的分析类型**:
- 语义搜索 - 按意图查找代码
- 调用链分析 - 追踪函数调用路径
- 架构分析 - 理解系统结构
- 影响分析 - 评估变更影响范围
- 死代码检测 - 找到未使用的代码
- 基础设施索引 - Docker、Kubernetes、Kustomize
- HTTP 跨服务链接 - 微服务依赖分析

**技术亮点**:
- 🎨 **Tree-Sitter AST 分析**: 高保真代码解析
- 🔗 **知识图**: 结构化代码表示
- 📈 **混合 LSP**: 10 种语言的语义类型解析
- 🔐 **安全可靠**: 通过 SLSA 3、OpenSSF 评分验证
- 📦 **零依赖**: 包含在单个二进制中

**应用场景**:
- 代码库导航和理解
- AI 编码助手集成
- 大型项目重构
- 代码审查和质量分析
- 技术债务评估
- 系统设计决策支持

**支持的编码助手**:
- Claude Code
- Cursor
- GitHub Copilot
- VSCode IntelliCode
- 和 40+ 其他工具

**快速开始**:
```bash
# macOS/Linux 一行安装
curl -fsSL https://raw.githubusercontent.com/DeusData/codebase-memory-mcp/main/install.sh | bash
```

**研究成果**:
- arXiv 论文：*Codebase-Memory: Tree-Sitter-Based Knowledge Graphs for LLM Code Exploration via MCP*
- 预印本：2603.27277

**链接**: https://github.com/yanlei183/codebase-memory-mcp

---

### 5. markitdown
**描述**: Python 文件转 Markdown 工具  
**中文说明**:
- **MarkItDown** 是微软 AutoGen 团队开发的轻量级 Python 工具
- 将各种文件格式转换为 Markdown
- 专为 LLM 和文本分析管道优化
- Token 高效，兼容主流 LLM

**支持的输入格式**:
- 📄 PDF（包括扫描 PDF）
- 📊 PowerPoint（PPTX）
- 📝 Word（DOCX）
- 🗂️ Excel（XLSX）
- 🖼️ 图片（带 EXIF 和 OCR）
- 🎵 音频（元数据和转录）
- 🌐 HTML
- 📋 CSV、JSON、XML
- 📦 ZIP 文件（迭代内容）
- 🎥 YouTube URL
- 📖 EPUB
- ... 更多格式

**核心特性**:
- ✨ **Markdown 优先**: 输出高效的 Markdown，LLM 原生支持
- 🤖 **LLM 友好**: GPT-4o 等模型广泛支持 Markdown
- ⚡ **Token 高效**: 减少不必要的格式标记
- 🔌 **插件支持**: OCR、Azure Content Understanding
- 🛠️ **多个选项**:
  - 命令行工具
  - Python API
  - MCP 服务器

**安装方式**:
```bash
# 完整安装（所有可选依赖）
pip install 'markitdown[all]'

# 自定义安装
pip install 'markitdown[pdf,docx,pptx]'
```

**使用示例**:
```bash
# 命令行
markitdown document.pdf > output.md
markitdown document.pdf -o output.md
cat document.pdf | markitdown

# Python API
from markitdown import MarkItDown
md = MarkItDown()
result = md.convert("document.pdf")
```

**高级功能**:
- 🎨 **Azure Content Understanding**: 云端高级提取和字段识别
- 🖼️ **OCR 插件**: 使用 LLM Vision 提取图像文本
- 📑 **结构提取**: YAML 前置元数据和字段提取
- 🎬 **多模态**: 支持文档、图像、音频、视频

**应用场景**:
- 文档自动化处理
- 知识库建设
- 数据预处理
- RAG 系统数据准备
- 批量文档转换
- AI 训练数据准备

**链接**: https://github.com/yanlei183/markitdown

---

### 6. ollama
**描述**: LLM 推理引擎  
**中文说明**:
- **Ollama** 是一个强大的开源 LLM 推理引擎
- 支持在本地快速运行开源大语言模型
- 零配置部署，开箱即用
- 支持 CPU 和 GPU 加速

**特点**:
- 🚀 **快速部署**: 一条命令快速启动
- 🤖 **模型丰富**: 支持 Kimi、GLM、MiniMax、DeepSeek、Qwen、Gemma 等
- 📦 **预编译**: macOS、Linux、Windows 原生支持
- 🔌 **API 服务**: REST API 完全兼容 OpenAI
- 🎯 **集成广泛**: 支持 Claude Code、Codex、Copilot 等
- 💻 **AI 助手**: 通过 OpenClaw 支持多平台对话
- 🎮 **易于使用**: 直观的 CLI 和 API

**支持的模型**:
- **Kimi-K2.6** - 深度思考能力
- **GLM-5.2** - 多语言支持
- **MiniMax** - 高效推理
- **DeepSeek** - 开源优秀模型
- **GPT-oss** - OpenAI 兼容
- **Qwen** - 阿里大模型
- **Gemma** - Google 开源模型
- 和其他 100+ 模型

**安装**:
```bash
# macOS
curl -fsSL https://ollama.com/install.sh | sh

# Windows PowerShell
irm https://ollama.com/install.ps1 | iex

# Linux
curl -fsSL https://ollama.com/install.sh | sh
```

**快速开始**:
```bash
# 运行模型
ollama run gemma4

# 启动 AI 助手
ollama launch claude

# 启动 OpenClaw 多平台助手
ollama launch openclaw
```

**REST API**:
```bash
curl http://localhost:11434/api/chat -d '{
  "model": "gemma4",
  "messages": [{"role": "user", "content": "Why is the sky blue?"}],
  "stream": false
}'
```

**Python 客户端**:
```python
from ollama import chat

response = chat(model='gemma4', messages=[
  {'role': 'user', 'content': 'Why is the sky blue?'}
])
print(response.message.content)
```

**应用场景**:
- 本地 AI 模型部署
- 离线 AI 助手
- 隐私保护的 AI 应用
- 企业内部 AI 系统
- AI 研究和开发
- 模型比较和评估

**社区生态**:
- 📱 Web UI - Open WebUI、Onyx、LibreChat 等
- 🖥️ 桌面应用 - AnythingLLM、Dify、Witsy 等
- 💬 聊天接口 - 40+ 集成应用
- 📚 教程资源 - 官方文档和社区指南

**链接**: https://github.com/yanlei183/ollama

---

### 7. vllm
**描述**: 高吞吐 LLM 推理和服务引擎  
**中文说明**:
- **vLLM** 是一个高效的大语言模型推理和服务引擎
- 针对高吞吐量场景优化
- 高效的内存管理
- 生产级别的稳定性

**特性**:
- ⚡ **高吞吐量**: 专为批量推理优化
- 💾 **内存高效**: 优化的张量管理和内存分配
- 🎯 **多模型支持**: 广泛支持主流开源和商用模型
- 📊 **可扩展性**: 支持分布式部署
- 🔌 **API 兼容**: OpenAI 兼容 API
- 🚀 **生产就绪**: 企业级稳定性

**应用场景**:
- 大规模 API 服务部署
- 批量推理任务
- 实时聊天服务
- 多用户并发处理
- 企业 LLM 服务
- 研究与开发

**链接**: https://github.com/yanlei183/vllm

---

## 技术栈

- **编程语言**: C++、Node.js、C (51单片机汇编)、Python
- **通信协议**: 串口通信、CNC 协议
- **集成方式**: 库文件、模块、SDK、MCP 服务
- **AI 框架**: LLM 推理框架
- **知识图**: Tree-sitter、AST 分析

## 应用领域

🔌 硬件集成  
🔐 生物识别  
🏭 工业控制  
📡 物联网  
🤖 嵌入式系统  
🧠 代码理解  
📄 文档处理  
🤖 AI 推理  
💻 编码助手  

## 使用建议

### CSerialPort
```cpp
#include "CSerialPort.h"
// 创建串口实例并通信
```

### nodejs-fingure
```javascript
const fingerprint = require('nodejs-fingure');
// 指纹识别集成
```

### -public-apis
访问列表快速查找所需 API，减少开发时间。

### codebase-memory-mcp
为 AI 编码助手提供高性能代码智能能力。

### markitdown
```bash
markitdown --use-plugins document.pdf --llm-model gpt-4o
```

### ollama / vllm
选择合适的部署方案（本地 vs 服务器）实现 LLM 推理。

---

**返回**: [项目索引主页](../README.md)