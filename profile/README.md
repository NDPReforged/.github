<div align="center">

# NDPReforged

**跨平台 Minecraft 服务器联合封禁系统**

[官网](https://ndpreforged.com) · [在线文档](https://ndpreforged.com/wiki.php) · [QQ 交流群](https://qm.qq.com/q/t2fAP3Smbu)

![License](https://img.shields.io/badge/license-MIT-blue.svg)

</div>

---

## 📖 简介

NDPReforged（NDPR）是专业的跨平台 Minecraft 服务器联合封禁系统。多个服务器共享同一个云端封禁数据库，实现**统一封禁、实时同步**。支持 ID / UUID / IPv4 / IPv6 多维封禁检查、封禁审核、拦截统计，以及 **HWID 设备验证**（浏览器指纹反作弊机器验证）。

## 📦 项目仓库

| 仓库 | 说明 |
|------|------|
| [NDPR-MCDR](https://github.com/NDPReforged/NDPR-MCDR) | MCDR 插件（Java 版，Python） |
| [NDPR-plugin](https://github.com/NDPReforged/NDPR-plugin) | Bukkit / Spigot / Paper / Folia 插件 |
| [NDPR-mod](https://github.com/NDPReforged/NDPR-mod) | Fabric / Forge / NeoForge Mod |
| [NDPR-Proxy](https://github.com/NDPReforged/NDPR-Proxy) | Velocity + BungeeCord 代理端插件（单 jar） |
| [NDPR-BE](https://github.com/NDPReforged/NDPR-BE) | 基岩版客户端（LeviLamina / BDSX / BDSpyrunner / Nukkit / Allay / gomint） |
| [PluginCatalogue](https://github.com/NDPReforged/PluginCatalogue) | MCDReforged 插件目录 |

## ✨ 核心特性

- 🔐 **Token 认证**：安全认证 + 权限控制
- 🔗 **实时同步**：多服务器封禁数据即时同步
- 🖥️ **多维封禁**：ID / UUID / IPv4 / IPv6 检查
- 🧬 **HWID 设备验证**：浏览器指纹（Canvas + GPU ID）反作弊验证
- 📋 **封禁审核**：提交封禁申请，云端审核后同步
- 📊 **拦截统计**：完整的拦截数据上报
- 🔄 **自动更新**：封禁库定时同步 + GitHub 版本检查

## 🎮 支持平台

| 类别 | 平台 |
|------|------|
| Java 版插件 | MCDR 2.8+、Bukkit / Spigot / Paper / Folia |
| Java 版 Mod | Fabric、Forge、NeoForge |
| 代理端 | Velocity 3.x、BungeeCord |
| 基岩版 | LeviLamina、BDSX、BDSpyrunner、Nukkit、Allay、gomint |

## 🚀 快速开始

1. 安装对应平台的客户端（见各仓库 README）
2. 首次启动自动获取服务器 UUID
3. 前往[官网](https://ndpreforged.com)绑定邮箱获取 Token
4. 填写 Token 并配置 `onlinemode`
5. 完成！封禁数据自动同步

> 详细文档见 [在线文档](https://ndpreforged.com/wiki.php)

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

<div align="center">

**Made with ❤️ by NDPReforged Team**

</div>