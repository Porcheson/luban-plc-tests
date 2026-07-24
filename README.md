# Procheson PLC ST测试报告

[![Deploy to GitHub Pages](https://github.com/Porcheson/luban-plc-tests/actions/workflows/deploy.yml/badge.svg)](https://github.com/Porcheson/luban-plc-tests/actions/workflows/deploy.yml)
[![Netlify Status](https://api.netlify.com/api/v1/badges/54569b5a-27c3-4de8-b977-42dd96f4efb8/deploy-status)](https://app.netlify.com/projects/luban-plc-tests/deploys)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D24.0.0-brightgreen)](https://nodejs.org/)
[![Platform](https://img.shields.io/badge/platform-VitePress-blue)](https://vitepress.dev/)

📚 **在线文档**：

| 平台 | 地址 |
|------|------|
| GitHub Pages | [https://porcheson.github.io/luban-plc-tests/](https://porcheson.github.io/luban-plc-tests/) |
| Netlify | [https://luban-plc-tests.netlify.app/](https://luban-plc-tests.netlify.app/) |

---

## 📖 项目简介

本项目是一套完整的PLC指令测试套件，基于IEC 61131-3标准，全面覆盖各类PLC指令，为工业自动化工程师、系统集成商和教育机构提供高质量的测试工具和参考文档。

## 🎯 主要内容

| 分类 | 说明 |
| --- | --- |
| 📄 **基础指令测试** | 位操作、比较、算术、类型转换、选择等指令的测试验证 |
| ⚙️ **高级指令测试** | 计数器、定时器、移位寄存器、移位指令、字符串操作、触发器等 |
| 🔧 **扩展指令测试** | 扩展计数器、扩展类型转换、数学函数、时间算术等 |
| 📊 **统计报告** | 测试统计报告、明细表、项目成果汇报总结 |

## ⚡ 项目特点

- **全面覆盖**：实现对200+个PLC指令的完整测试覆盖
- **标准化**：遵循IEC 61131-3国际标准
- **兼容性**：Luban（基于Beremiz二开）平台，确保在开源PLC环境中的良好运行
- **易用性**：提供完整的测试程序和详细文档
- **可扩展性**：建立模块化测试框架，便于后续扩展

## 🛠️ 技术栈

| 技术 | 说明 |
| --- | --- |
| IEC 61131-3 ST | PLC编程语言标准 |
| Beremiz / Luban | 开源自动化IDE |
| VitePress | 文档站点框架 |

## 📁 文档结构

```
docs/
├── index.md                      # 首页
├── 1.1 前言.md                   # 前言
├── LubanTest/                    # 测试文档目录
│   ├── 2.1 位操作指令测试说明.md
│   ├── 2.2 比较指令测试说明.md
│   ├── 2.3 算术指令测试说明.md
│   ├── 2.4 类型转换指令测试说明.md
│   ├── 2.5 选择指令测试说明.md
│   ├── 3.1 计数器指令测试说明.md
│   ├── 3.2 定时器指令测试说明.md
│   ├── 3.3 移位寄存器指令测试说明.md
│   ├── 3.4 位移指令测试说明.md
│   ├── 3.5 字符串操作指令测试说明.md
│   ├── 3.6 触发器指令测试说明.md
│   ├── 4.1 扩展计数器指令测试说明.md
│   ├── 4.2 扩展数据类型转换指令测试说明.md
│   ├── 4.3 数学函数指令测试说明.md
│   ├── 4.4 时间算术指令测试说明.md
│   ├── 5.1 PLC指令测试统计报告.md
│   ├── 5.2 PLC指令测试明细表.md
│   ├── 5.3 类型转换指令详细统计表.md
│   └── 5.4 项目成果汇报总结.md
└── public/
    └── logo.png
```

## 📞 联系方式

- **项目负责人**：汪勇强
- **联系电话**：13971612060
- **QQ**：94114148

---

*本项目将持续维护和更新，欢迎提出宝贵意见和建议。*
