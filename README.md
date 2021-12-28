# raft-visualization

Raft前后端可视化项目

## 1. 技术栈选型：（目前暂定）

- 前端：React/Vue (需要调研一下两个框架的animation和UI库，以及websocket框架)
- 后端：Springboot（有快速的Websocket-Stater支持，我自己对这部分技术栈比较熟悉，同时跨平台）
- 其他技术：
  - WebSocket（用于后端实时把状态同步到前端，前端也可以向后端发送指令）
  - RPC用与不同broker的通信

## 2. 主要任务

### 2.1 在后端复现raft的结构，以功能重现为主，暂时无需过多测试

### 2.2 完成manager类，用于和前端WebSocket通信，同步状态

### 2.3 前端将后端发送过来的状态信息显示在画布上，并能实时调整后端状态