# ms365-mcp

Microsoft 365 MCP server for Claude Code, powered by [@softeria/ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server).

## 安装

```bash
npm install -g @softeria/ms-365-mcp-server
```

## Claude Code 全局配置（~/.claude.json）

```json
"ms365": {
  "type": "stdio",
  "command": "ms-365-mcp-server",
  "args": ["--org-mode", "--preset", "mail"],
  "env": {}
}
```

## 首次授权

```bash
ms-365-mcp-server --login
```

## 当前版本

v0.46.1

## 功能覆盖

- 邮件：读取、发送、回复、转发、草稿、附件、共享邮箱
- 日历：CRUD、查找空闲时间、多日历支持
- Teams：消息、频道、会议记录
- OneDrive：文件上传/下载/管理
- SharePoint、OneNote、Planner、Todo、联系人

共 114 个工具。
