<div align="center">

<!-- 动态打字机效果 Banner -->
<a href="https://github.com/lxxxDD/campus-life-server">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=40&duration=3000&pause=1000&color=2094F7&center=true&vCenter=true&width=600&lines=Campus+Life+Server;Spring+Boot+Eco-System;Next+Gen+Campus+Solution" alt="Typing SVG" />
</a>

<br>

<!-- 核心徽章矩阵 -->
<p>
  <a href="https://github.com/lxxxDD/campus-life-server">
    <img src="https://img.shields.io/github/repo-size/lxxxDD/campus-life-server?style=for-the-badge&logo=github&color=9C27B0" />
  </a>
  <a href="https://github.com/lxxxDD/campus-life-server/issues">
    <img src="https://img.shields.io/github/issues/lxxxDD/campus-life-server?style=for-the-badge&logo=github&color=F44336" />
  </a>
  <a href="https://github.com/lxxxDD/campus-life-server/stargazers">
    <img src="https://img.shields.io/github/stars/lxxxDD/campus-life-server?style=for-the-badge&logo=github&color=FFC107" />
  </a>
  <a href="https://github.com/lxxxDD/campus-life-server/commits">
    <img src="https://img.shields.io/github/last-commit/lxxxDD/campus-life-server?style=for-the-badge&logo=github&color=4CAF50" />
  </a>
</p>

<!-- 技术栈徽章 -->
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-3.3.5-brightgreen?style=for-the-badge&logo=springboot" />
  <img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk" />
  <img src="https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql" />
  <img src="https://img.shields.io/badge/MyBatis_Plus-3.5.7-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Redis-Latest-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-Auth-000000?style=for-the-badge&logo=jsonwebtokens" />
</p>

<br>

<h3 align="center">🚀 让校园生活从未如此极客</h3>

<p align="center">
  <a href="#-系统架构">🗺️ 系统架构</a> •
  <a href="#-快速部署">⚡ 快速部署</a> •
  <a href="http://localhost:8080/doc.html">📖 接口文档</a> •
  <a href="#-贡献指南">🤝 贡献指南</a>
</p>

</div>

---

## 📊 极客统计 (GitHub Stats)

<div align="center">
  <table style="border: none;">
    <tr>
      <td style="border: none; padding-right: 20px;">
        <!-- 你的代码能力值卡片 -->
        <img src="https://github-readme-stats.vercel.app/api?username=lxxxDD&show_icons=true&theme=radical&count_private=true&hide_border=true" alt="lxxxDD's Stats" />
      </td>
      <td style="border: none;">
        <!-- 语言使用分布 -->
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lxxxDD&layout=compact&theme=radical&hide_border=true&langs_count=6" alt="Top Langs" />
      </td>
    </tr>
  </table>
</div>

## 🗺️ 系统架构 (System Architecture)

```mermaid
graph TD
    Client[📱 移动端 / 💻 管理后台] -->|RESTful API| Gateway[🌐 Nginx 网关]
    
    subgraph "Core Server (Spring Boot)"
        Gateway --> Auth[🔐 认证授权 (JWT)]
        Auth --> Controller[🎮 控制层 (Web)]
        
        subgraph "Business Logic"
            Controller --> UserService[👤 用户服务]
            Controller --> MarketService[🛒 市场服务]
            Controller --> LifeService[🌈 生活服务]
        end
        
        Business Logic --> MP[🛠️ MyBatis-Plus]
    end
    
    subgraph "Data Storage"
        MP --> MySQL[(�️ MySQL 主库)]
        LifeService --> Redis[(� Redis 缓存)]
        MarketService --> OSS[(☁️ 文件存储)]
    end
    
    subgraph "External"
        LifeService --> AI[🤖 AI 大模型接口]
    end

    style Client fill:#f9f,stroke:#333,stroke-width:2px
    style Gateway fill:#bbf,stroke:#333,stroke-width:2px
    style Core Server fill:#dfd,stroke:#333,stroke-width:2px
    style Data Storage fill:#ffd,stroke:#333,stroke-width:2px
```

## ⚡ 核心能力 (Core Capabilities)

<details>
<summary><b>🔥 点击展开查看硬核功能列表</b></summary>
<br>

| 领域 | 核心功能 | 技术实现 |
| :--- | :--- | :--- |
| **� 安全架构** | JWT无状态认证、RBAC权限模型 | `HandlerInterceptor`, `@CheckToken` |
| **🚀 高性能** | 多级缓存架构、连接池优化 | `Redis`, `HikariCP` |
| **� 即时通讯** | WebSocket全双工通信、消息持久化 | `ServerEndpoint`, `ConcurrentHashMap` |
| **🤖 AI集成** | 智能对话上下文管理、流式响应 | `OkHttp`, `SSE` |
| **� 文档工程** | 自动化接口文档、在线调试 | `Knife4j`, `Swagger 3` |
| **�️ 代码生成** | 快速构建CRUD、统一响应体 | `MyBatis-Plus Generator`, `Result<T>` |

</details>

## 🚀 极速部署 (Quick Start)

> ⚠️ **Warning**: 下面的操作可能会导致你不仅帅，而且快。

```bash
# 1. ⬇️ 下载神器的源代码
git clone https://github.com/lxxxDD/campus-life-server.git

# 2. 🚀 进入发射基地
cd campus-life-server

# 3. 💣 装填弹药 (数据库)
# 执行 sql/init.sql 初始化数据库结构

# 4. ⚙️ 调整参数
# vim src/main/resources/application.yml

# 5. 🔥 点火发射！
mvn spring-boot:run
```

## 🤝 贡献者 (Contributors)

<a href="https://github.com/lxxxDD/campus-life-server/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=lxxxDD/campus-life-server" />
</a>

---

<div align="center">

**Code with ☕ and ❤️**

[![Star History Chart](https://api.star-history.com/svg?repos=lxxxDD/campus-life-server&type=Date)](https://star-history.com/#lxxxDD/campus-life-server&Date)

</div>

