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

## 技术栈

- **编程语言**: C++、Node.js、C (51单片机汇编)
- **通信协议**: 串口通信、CNC 协议
- **集成方式**: 库文件、模块、SDK

## 应用领域

🔌 硬件集成  
🔐 生物识别  
🏭 工业控制  
📡 物联网  
🤖 嵌入式系统  

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

---

**返回**: [项目索引主页](../README.md)