<div align="center">

# 📱 MessageVault 信驿云储

🔒 **安全、私密、自主可控的短信与通话记录备份解决方案**

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red.svg)](https://github.com/MessageVault)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/MessageVault)

</div>

MessageVault是一个开源项目，为Android用户提供安全、私密的短信和通话记录备份与分析解决方案。作为一个完整的全栈式开源项目，所有数据都存储在用户自己控制的服务器上，无需依赖第三方云服务。

## 🚀 项目愿景

- 🔒 **完全自主**: 数据完全在用户控制下，无第三方依赖
- 🛡️ **隐私优先**: 所有数据本地存储或自托管服务器
- 🔄 **跨设备同步**: 支持多设备备份和数据管理
- 📊 **智能分析**: 本地AI分析，保护隐私的数据洞察
- 🔧 **模块化设计**: 可扩展的架构，便于添加新功能
- 🎯 **全栈理念**: 从移动端到服务端，从数据存储到用户界面的完整解决方案

## 📦 项目组件

### 🎯 已发布仓库

- **[📱 MessageVault-Mobile](https://github.com/MessageVault/MessageVault-Mobile)** `v0.1.4` ⭐ **主力仓库**
  
  现代化Android应用，采用Material Design 3设计
  - ✅ **短信备份**: 完整支持SMS备份，包含所有元数据
  - ✅ **通话记录备份**: 完整支持通话历史记录备份
  - ✅ **联系人备份**: 完整支持联系人信息备份
  - ✅ **智能恢复**: 支持选择性恢复，带进度显示
  - ✅ **Material You**: 支持动态取色和深色主题
  - ✅ **多语言**: 中文/英文界面支持
  - [📋 变更日志](https://github.com/MessageVault/MessageVault-Mobile/blob/master/CHANGELOG.md) | [📝 AI编辑日志](https://github.com/MessageVault/MessageVault-Mobile/blob/master/AI_EDIT_LOG.md)

- **[🔍 SMS-Previewer](https://github.com/MessageVault/SMS-Previewer)** `v0.0.1` ⭐ **工具仓库**
  
  优雅的短信备份预览工具，基于Web技术
  - ✅ **文件预览**: 支持SMS Backup & Restore导出的XML文件
  - ✅ **智能分析**: 消息统计和联系人互动分析
  - ✅ **美观界面**: 对话气泡式界面，支持深色模式
  - ✅ **隐私保护**: 完全本地运行，无需上传服务器
  - [📋 变更日志](https://github.com/MessageVault/SMS-Previewer/blob/MainMaster/CHANGELOG.md)

### 🚧 开发中组件

- **[🖥️ MessageVault-Server](MessageVault-Server/README.md)** `v0.1.0` 🔨 **开发中**
  
  基于Go的后端服务器，提供RESTful API
  - ⏳ 基础API框架已完成
  - ⏳ 数据存储和管理功能开发中
  - [📋 变更日志](MessageVault-Server/CHANGELOG.md) | [📝 AI编辑日志](MessageVault-Server/AI_EDIT_LOG.md)

- **[🌐 MessageVault-Web](MessageVault-Web/README.md)** 🔨 **开发中**
  
  基于Vue.js的前端，用于数据管理和可视化
  - ⏳ 基础框架已搭建
  - ⏳ 界面和功能开发中
  - [📋 变更日志](MessageVault-Web/CHANGELOG.md) | [📝 AI编辑日志](MessageVault-Web/AI_EDIT_LOG.md)

- **[📚 MessageVault-Docs](MessageVault-Docs/README.md)** 🔨 **开发中**
  
  项目文档，使用MkDocs构建
  - ⏳ 基础文档结构已完成
  - ⏳ 详细文档内容补充中
  - [📋 变更日志](MessageVault-Docs/CHANGELOG.md) | [📝 AI编辑日志](MessageVault-Docs/AI_EDIT_LOG.md)

## 🎯 开发进度状态

### 📊 总体进度
- **MessageVault-Mobile**: 🟢 **高度可用** (核心功能完备，生产环境可用，持续优化中)
- **SMS-Previewer**: 🟢 **功能完备** (独立工具，稳定运行)
- **MessageVault-Server**: 🟡 **积极开发中** (基础框架完成，API和数据库功能开发中)
- **MessageVault-Web**: 🟡 **积极开发中** (基础结构搭建，界面和功能开发中)
- **MessageVault-Docs**: 🟡 **积极开发中** (文档框架完成，内容持续补充)

### 🏃‍♂️ 当前重点
1. **MessageVault-Mobile**: 🚀 持续优化用户体验和功能增强
2. **MessageVault-Server**: 🔧 API完善、数据库集成和性能优化
3. **MessageVault-Web**: 🎨 用户界面开发和数据可视化功能实现
4. **项目生态**: 📚 文档完善和开发者工具改进

> 💡 **开发理念**: 作为我的第一个全栈式开源项目，MessageVault致力于打造一个完整、可靠的数据备份解决方案，所有组件均在积极开发和不断完善中。

## 🛠️ 技术栈

### Mobile (Android)
- **框架**: Jetpack Compose + Material Design 3
- **语言**: Kotlin
- **架构**: MVVM + Repository Pattern
- **并发**: Kotlin Coroutines + StateFlow
- **测试**: JUnit + Mockito + Espresso

### Server (后端)
- **语言**: Go
- **框架**: Gin Web Framework
- **数据库**: SQLite (规划支持PostgreSQL)
- **部署**: Docker + Docker Compose
- **日志**: 结构化日志 + 文件轮转

### Web (前端)
- **框架**: Vue.js 3 + Composition API
- **UI**: Element Plus / Vuetify
- **状态管理**: Pinia
- **构建**: Vite
- **样式**: SCSS + CSS Variables

### Previewer (工具)
- **框架**: Vue 3 + Vite
- **样式**: Tailwind CSS
- **特性**: 纯前端，无服务器依赖

## 📋 项目规范

开发本项目前，请务必阅读[项目规范文档](NOTICE.md)，其中包含:

- 🏗️ **编码标准**: 命名规范、代码风格、架构原则
- 💬 **注释要求**: 文档化标准、API注释规范
- 🔧 **可扩展性**: 模块化设计、接口设计原则
- 🧪 **测试要求**: 单元测试、集成测试、E2E测试
- 📝 **变更记录**: CHANGELOG和AI编辑日志规范
- 📚 **文档要求**: README、API文档、用户手册标准

## 🚀 快速开始

### 👤 普通用户
1. **下载MessageVault-Mobile APK**: [Releases页面](https://github.com/MessageVault/MessageVault-Mobile/releases)
2. **使用SMS-Previewer**: [在线版本](https://messagevault.github.io/SMS-Previewer/) 或本地部署

### 👨‍💻 开发者
```bash
# 克隆主仓库
git clone https://github.com/MessageVault/MessageVault.git
cd MessageVault

# 克隆独立仓库（注意不同仓库的主分支名称）
git clone https://github.com/MessageVault/MessageVault-Mobile.git  # 主分支: master
git clone https://github.com/MessageVault/SMS-Previewer.git        # 主分支: MainMaster

# 选择要开发的组件
cd MessageVault-Mobile  # Android应用开发
cd MessageVault-Server  # 后端服务开发  
cd MessageVault-Web     # 前端界面开发
cd SMS-Previewer        # 预览工具开发

# 查看各组件的README.md获取详细开发指南
```

## 🏗️ 系统架构

```
┌─────────────────┐    HTTPS/API    ┌─────────────────┐
│  Android App    │◄──────────────► │   Go Server     │
│ (MessageVault-  │                 │ (MessageVault-  │
│     Mobile)     │                 │     Server)     │
└─────────────────┘                 └─────────────────┘
         │                                    │
         │ JSON Export                        │ Database
         ▼                                    ▼
┌─────────────────┐                 ┌─────────────────┐
│ SMS-Previewer   │                 │   SQLite/       │
│  (Web Tool)     │                 │  PostgreSQL     │
└─────────────────┘                 └─────────────────┘
                                              ▲
                           Web Interface     │
                          ┌─────────────────┐│
                          │   Vue.js Web    ││
                          │ (MessageVault-  ││
                          │      Web)       ││
                          └─────────────────┘│
                                    ▲────────┘
                                    │
                               ┌─────────────────┐
                               │     Users       │
                               │ (Web Browser)   │
                               └─────────────────┘
```

## 🤝 参与贡献

我们欢迎所有形式的贡献！无论是代码、文档、测试、反馈还是建议。

### 🐛 报告问题
- [MessageVault-Mobile Issues](https://github.com/MessageVault/MessageVault-Mobile/issues)
- [SMS-Previewer Issues](https://github.com/MessageVault/SMS-Previewer/issues)

### 💡 功能建议
- [MessageVault Discussions](https://github.com/MessageVault/MessageVault/discussions)

### 📝 贡献代码
1. Fork 相应的仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 📋 开发规范
- 遵循项目编码标准
- 编写单元测试
- 更新相关文档
- 遵循Git提交规范

## 🏆 致谢

### 🙏 特别感谢
- **[SMS Backup & Restore](https://play.google.com/store/apps/details?id=com.riteshsahu.SMSBackupRestore)**: 启发了SMS-Previewer项目的创建
- **Android开源社区**: 提供了优秀的Jetpack Compose和Material Design 3组件
- **Go社区**: 提供了强大的Gin框架和丰富的生态系统
- **Vue.js社区**: 提供了现代化的前端开发框架
- **开源精神**: 无数开源项目和开发者的贡献，让我学会了如何构建和维护一个全栈项目

### 💻 核心技术支持
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - 现代化Android UI框架
- [Material Design 3](https://m3.material.io/) - Google设计系统
- [Gin Web Framework](https://gin-gonic.com/) - 高性能Go Web框架
- [Vue.js](https://vuejs.org/) - 渐进式JavaScript框架
- [Tailwind CSS](https://tailwindcss.com/) - 实用优先的CSS框架

### 🎓 学习与成长
MessageVault是我探索全栈开发的第一个完整项目，从中学到了：
- 移动端开发的最佳实践
- 后端API设计和数据库管理
- 前端框架和用户体验设计
- 开源项目的协作和维护
- GPL许可证的价值和意义

## 📊 项目统计

<div align="center">

![Project Status](https://img.shields.io/badge/Project%20Status-Active%20Development-brightgreen)
![Mobile App](https://img.shields.io/badge/Mobile%20App-v0.1.4%20Highly%20Usable-success)
![SMS Previewer](https://img.shields.io/badge/SMS%20Previewer-v0.0.1%20Stable-success)
![Backend](https://img.shields.io/badge/Backend-v0.1.0%20Active%20Development-orange)
![Frontend](https://img.shields.io/badge/Frontend-Active%20Development-orange)
![License](https://img.shields.io/badge/License-GPL%20v3-blue)

**最近更新**: 2025年6月11日 | **主要语言**: Kotlin, Go, Vue.js, TypeScript | **首个全栈开源项目** 🎯

</div>

---

<div align="center">

### 📱 开始您的数据备份之旅

**[下载Android应用](https://github.com/MessageVault/MessageVault-Mobile/releases)** 
• 
**[在线预览工具](https://messagevault.github.io/SMS-Previewer/)**
•
**[查看文档](https://github.com/MessageVault/MessageVault-Docs)**

---

*MessageVault - 您的数据，您的控制权* 🔒

[![Website](https://img.shields.io/badge/Website-messagevault.org-blue)](https://messagevault.org)
[![Documentation](https://img.shields.io/badge/Docs-Read%20Now-green)](https://github.com/MessageVault/MessageVault-Docs)
[![Community](https://img.shields.io/badge/Community-Join%20Us-purple)](https://github.com/MessageVault/MessageVault/discussions)

</div>

## 📄 许可证

本项目采用 [GNU General Public License v3.0](LICENSE) - 查看许可证文件了解详情。

### 🛡️ GPL 3.0 核心原则
- ✅ **自由使用**: 可以自由运行程序
- ✅ **自由研究**: 可以研究程序工作原理并修改
- ✅ **自由分发**: 可以重新分发原始版本
- ✅ **自由改进**: 可以分发修改后的版本
- 🔒 **Copyleft保护**: 衍生作品必须以相同许可证分发
- 📝 **源码开放**: 分发二进制文件时必须提供源代码

### 🎯 选择GPL 3.0的原因
作为我的第一个全栈式开源项目，选择GPL 3.0是为了：
- 确保项目及其衍生作品始终保持开源
- 保护用户的自由和隐私权利
- 促进开源社区的良性发展
- 为未来的可持续发展模式提供法律保障

## 🛡️ 项目独立性声明

### 📜 核心承诺
面对当前开源生态中部分项目被商业收购的现状，我们郑重声明：

- 🔒 **数据自主权**: 本项目的所有子项目、功能**绝对不会**与任何第三方共享用户数据
- 🏠 **本地优先**: 坚持数据本地可控的设计理念，用户完全掌控自己的数据
- 👤 **用户选择权**: 保留用户高度自定义权利，由用户自行选择是否接入第三方服务
- 🔧 **可选集成**: 支持用户自主选择第三方API（云盘备份、AI分析等）服务提供商

### 🛡️ 独立性保障
- 📅 **长期维护**: 即使项目不盈利，也会持续投入时间进行维护和更新
- 🚫 **抗收购承诺**: 如遇不可抗力强制收购，将**立即封存归档**整个组织账户
- 🌱 **社区传承**: 确保开源社区能够Fork项目并继续发扬光大
- 💎 **价值坚持**: 即使存在众多替代品，仍坚持数据自主的核心价值观

> 🔥 **我们的信念**: 用户数据属于用户本人，任何人和组织都无权在未经明确授权的情况下访问、使用或共享用户数据。

### 💼 项目可持续发展计划
MessageVault采用**开源优先**的发展模式：
- 🆓 **当前阶段**: 所有功能完全开源免费
- 🚀 **未来Pro版本**: 当项目高度成熟后，将推出Pro版本用于体验最新功能
- 📦 **版本策略**: Pro版本领先开源版本两个版本，旧Pro版本将自动开源发布
- 🤝 **收益分配**: Pro版本收入将与贡献者按贡献量公平分配
- 🎯 **核心承诺**: 基础功能永远保持开源，确保用户数据自主权

> 💡 **重要说明**: 目前专注于开源版本的完善，Pro版本计划仅在整个项目生态高度可用后才会考虑推出。
