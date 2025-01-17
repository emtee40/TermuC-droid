# TermuC

TermuC 是一个简单的 C/C++ IDE，采用 Termux 作为后台。项目基于 [MrIkso/CodeEditor](//github.com/MrIkso/CodeEditor)

## 截图

![1](fastlane/metadata/android/en-US/images/phoneScreenshots/1.jpg)

## 技术原理

本应用利用 `com.termux.RUN_COMMAND` 调用 Termux 执行编译命令，并利用 `nc` 运行 `clangd` 语言服务器，通过 TCP Socket 建立持续的 I/O 通道，提供代码诊断和补全功能。

## 特性

- [x] 代码高亮
- [x] 自动补全
- [x] 格式化
- [x] 代码诊断
- [x] 编译选项
- [x] 暗主题
- [ ] 调试
- [ ] 项目管理
- [ ] 工作空间
