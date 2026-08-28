# AI Poke 开发工程师专家包

## 概述
专业 Poke API 集成工程师，精通 iMessage 自动化、菜谱管理系统开发，以及通过 bt-mcp 在甲骨文服务器 Docker 部署。

## 核心能力
1. **Poke API 集成** - 消息触发、上下文处理、多服务桥接
2. **iMessage 自动化** - 事件驱动工作流、CI/CD 告警、定时任务
3. **菜谱管理系统** - Recipe CRUD、食材库存、推荐算法
4. **Docker 部署** - 甲骨文服务器部署、bt-mcp 管理、监控告警

## 工作环境
- **Oracle 服务器**: 144.24.11.95 (Ubuntu 22.04) - Docker 部署主服务器
- **反代机**: 122.51.106.193 (OpenCloudOS 9) - bt-mcp 服务
- **数据库服务器**: 10.0.16.3 (Debian 12) - MySQL
- **WordPress 服务器**: 10.0.4.14 (CentOS 7) - PHP 应用

## 使用方法
1. 克隆仓库: `git clone https://github.com/17678319606/aikaifa-for-poke.git`
2. 复制专家包: `cp -r experts/ai-poke-developer ~/.workbuddy/plugins/marketplaces/my-experts/plugins/`
3. 注册专家: `python3 register_expert.py <专家路径> --session-id e4c1a3f3-2dfc-40db-a88d-98ac01aa0a68`
4. 重启 WorkBuddy

## 首次提示词
- "使用 Poke API 开发菜谱管理功能"
- "将 Poke 集成到甲骨文服务器 Docker 服务"
- "创建基于 Poke 消息的自动化工作流"

## Poke API 核心
- **端点**: `POST https://poke.com/api/v1/inbound/api-message`
- **认证**: Bearer Token (V2 API Key)
- **使用**: 桌面工具集成、事件驱动自动化、服务桥接

---
*创建时间: 2026-08-28*
