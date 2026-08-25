# 🛠️ 工具库项目

系统工具库、驱动程序、硬件集成等底层工具库。

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
**特性**:
- 将代码库索引到持久知识图
- 支持 158 种语言
- 平均索引时间：毫秒级
- 亚毫秒查询
- 减少 99% 的 token 使用
- 单个静态二进制文件
- 零依赖

**用途**:
- 代码理解和分析
- 智能代码补完
- 项目导航
- 代码检索

**链接**: https://github.com/yanlei183/codebase-memory-mcp

---

### 5. markitdown
**描述**: Python 文件转 Markdown 工具  
**特性**:
- 支持多种文件格式
- 办公文档转换
- Python 编写
- 批量处理能力

**用途**:
- 文档格式转换
- 文档化自动化
- 知识库建设

**链接**: https://github.com/yanlei183/markitdown

---

### 6. ollama
**描述**: LLM 推理引擎  
**特性**:
- 支持多种开源模型
- 简单部署
- 快速推理

**支持模型**:
- Kimi-K2.6
- GLM-5.2
- MiniMax
- DeepSeek
- gpt-oss
- Qwen
- Gemma
- 其他模型

**用途**:
- 本地 LLM 部署
- 快速模型评估
- 离线推理

**链接**: https://github.com/yanlei183/ollama

---

### 7. vllm
**描述**: 高效 LLM 推理和服务引擎  
**特性**:
- 高吞吐处理
- 内存高效
- 批量推理优化
- 生产级别稳定性

**用途**:
- LLM 服务部署
- 大规模推理
- API 服务

**链接**: https://github.com/yanlei183/vllm

---

## 技术栈

- **编程语言**: C++、Node.js、C (51单片机汇编)、Python
- **通信协议**: 串口通信、CNC 协议
- **集成方式**: 库文件、模块、SDK、MCP 服务
- **AI 框架**: LLM 推理框架

## 应用领域

🔌 硬件集成  
🔐 生物识别  
🏭 工业控制  
📡 物联网  
🤖 嵌入式系统  
🧠 代码智能  
📚 文档处理  
🔬 LLM 推理  

## 使用建议

### CSerialPort
```cpp
// 引入库
#include "CSerialPort.h"

// 创建串口实例并通信
```

### nodejs-fingure
```javascript
// Node.js 调用示例
const fingerprint = require('nodejs-fingure');
```

### -public-apis
访问列表快速查找所需 API，减少开发时间。

### codebase-memory-mcp
用于 AI 编辑器和代码助手的集成，提供高性能代码智能。

### ollama/vllm
用于本地或服务器部署 LLM，支持多种模型。

---

**返回**: [项目索引主页](../README.md)