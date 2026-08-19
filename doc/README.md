# TokenSoft Token 文档

本目录包含 TokenSoft Token 项目的合约架构与核心逻辑说明。

## 文档索引

| 文档 | 说明 |
|------|------|
| [TokenSoftTokenV2-架构与核心逻辑.md](./TokenSoftTokenV2-架构与核心逻辑.md) | 工程概览、继承架构、ERC1404 限制逻辑、角色权限、V2 新增能力 |
| [合约模块参考.md](./合约模块参考.md) | 各 Capability 与 Role 模块的 API 与状态变量速查 |

## 快速导航

- **主合约**：`contracts/TokenSoftTokenV2.sol`
- **V1 基类**：`contracts/TokenSoftToken.sol`
- **代理升级**：`contracts/Proxy.sol` + `contracts/capabilities/Proxiable.sol`
- **测试**：`test/` 目录（Truffle + OpenZeppelin Test Helpers）
- **部署脚本**：`migrations/2_deploy_contracts.js`
