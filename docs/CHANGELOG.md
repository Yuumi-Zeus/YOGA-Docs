---
comments: true
---

# CHANGELOG

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

这个项目的所有显著变化都将记录在这个文件中。

格式基于[Keep a Changelog](https://keepachangelog.com/en/1.1.0/)，以及这个项目遵循[Semantic Versioning](https://semver.org/spec/v2.0.0.html)。

## [0.1.2.beta] - 2025-05-09

### Changed

- Beta 阶段不向前兼容
- 重新设计项目结构，根目录为 Plugins/Yuumix/OdinToolkits，将 SO 框架移至 OdinToolkits 文件夹内。

## [0.1.1] - 2025-04-28

### Added

- 新增两个第三方引用，位于 ThirdParty 文件夹，包括一个[Odin 相关开源库](https://github.com/Schwapo/Odin-Resolved-Parameters-Overview)和一个[Log相关免费资源](https://rubickanov.itch.io/)
- 新增 Odin 自带特性解析手册，全中文解析 Odin 默认提供的 Attributes，比官方的手册更强，更适合中文开发者
- 新增模版代码生成工具
- 新增 ComponentBinder ，组件绑定工具
- 新增 OdinToolkits 编辑器配置
- 新增自定义扩展 Odin Attribute
- 新增提取 Odin Syntax Highlight 资源文件，让 Odin 的语法高亮为开发者所用
- 新增通用模块 Common，一些跨项目通用类，方法

## [0.1.0] - 2025-04-21

### Added

- 新增一个简单工具，QuickGenerateSO - 快速右键生成 SO 资源，自动遍历选择的资源，根据继承了 `ScriptableObject`的脚本，生成 SO 资源。
