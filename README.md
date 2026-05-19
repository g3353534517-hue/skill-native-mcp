# Native MCP / MCP协议原生客户端

![分类](https://img.shields.io/badge/分类-协议-blue)

## 项目简介

MCP（Model Context Protocol）协议原生客户端技能。直接与MCP兼容的服务端通信，无需中间层。

## MCP协议简介

MCP是Anthropic提出的模型上下文协议，标准化了AI模型与外部工具/数据源之间的通信方式。

本技能实现了原生MCP客户端，可以：
- 发现服务端提供的工具列表
- 调用远程工具并获取结果
- 处理MCP协议的消息格式

## 文件结构

```
SKILL.md
_meta.json
```

## 许可证

MIT License
