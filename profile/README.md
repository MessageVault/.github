# MessageVault 信驿云储

MessageVault是一个开源项目，用于备份、同步和分析短信和通话记录。

## 项目组件

- **[MessageVault-Mobile](MessageVault-Mobile/README.md)**: Android应用，读取短信和通话记录，支持备份和恢复
  - [变更日志](MessageVault-Mobile/CHANGELOG.md) | [AI编辑日志](MessageVault-Mobile/AI_EDIT_LOG.md) | [测试目录](MessageVault-Mobile/tests/)
- **[MessageVault-Server](MessageVault-Server/README.md)**: 基于Go的后端服务器，提供RESTful API
  - [变更日志](MessageVault-Server/CHANGELOG.md) | [AI编辑日志](MessageVault-Server/AI_EDIT_LOG.md) | [测试目录](MessageVault-Server/tests/)
- **[MessageVault-Web](MessageVault-Web/README.md)**: 基于Vue.js的前端，用于显示和分析数据
  - [变更日志](MessageVault-Web/CHANGELOG.md) | [AI编辑日志](MessageVault-Web/AI_EDIT_LOG.md) | [测试目录](MessageVault-Web/tests/)
- **[MessageVault-Docs](MessageVault-Docs/README.md)**: 项目文档
  - [变更日志](MessageVault-Docs/CHANGELOG.md) | [AI编辑日志](MessageVault-Docs/AI_EDIT_LOG.md) | [测试目录](MessageVault-Docs/tests/)

## 项目规范

开发本项目前，请务必阅读[项目规范文档](NOTICE.md)，其中包含:

- 编码标准和命名规范
- 注释要求
- 可扩展性指南
- 测试要求
- 变更记录与AI编辑日志规范
- 文档要求

## 快速开始

请参考各组件目录中的README.md文件以获取详细的设置和使用说明。

## 项目结构

```
MessageVault/
├── .gitignore                # 全局忽略文件
├── README.md                 # 项目概述
├── NOTICE.md                 # 项目规范文档
├── scripts/                  # 工具脚本目录
│   └── aggregate_logs.sh     # 日志聚合工具
├── MessageVault-Mobile/      # Android应用
│   ├── README.md
│   ├── CHANGELOG.md
│   ├── AI_EDIT_LOG.md
│   ├── logs/                 # 日志目录
│   ├── tests/                # 测试目录
│   └── app/...               # 应用代码
├── MessageVault-Server/      # Go后端
│   ├── README.md
│   ├── CHANGELOG.md
│   ├── AI_EDIT_LOG.md
│   ├── logs/                 # 日志目录
│   ├── config/               # 配置目录
│   ├── tests/                # 测试目录
│   └── ...                   # 服务器代码
├── MessageVault-Web/         # Vue.js前端
│   ├── README.md
│   ├── CHANGELOG.md
│   ├── AI_EDIT_LOG.md
│   ├── logs/                 # 日志目录
│   ├── tests/                # 测试目录
│   └── src/...               # 前端代码
└── MessageVault-Docs/        # 文档
    ├── README.md
    ├── CHANGELOG.md
    ├── AI_EDIT_LOG.md
    ├── tests/                # 测试目录
    └── docs/...              # 文档文件
```

## 许可证

暂无
