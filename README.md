<div align="center">

# 🎓 Campus Life Server

<img src="https://img.shields.io/badge/Spring%20Boot-3.3.5-brightgreen?style=for-the-badge&logo=springboot" />
<img src="https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk" />
<img src="https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql" />
<img src="https://img.shields.io/badge/MyBatis--Plus-3.5.7-red?style=for-the-badge" />

**🚀 为校园生活而生的后端服务**

[📖 API文档](http://localhost:8080/doc.html) · [🐛 报告Bug](https://github.com/lxxxDD/campus-life-server/issues) · [💡 功能建议](https://github.com/lxxxDD/campus-life-server/issues)

</div>

---

## ✨ 项目亮点

```
 ██████╗ █████╗ ███╗   ███╗██████╗ ██╗   ██╗███████╗
██╔════╝██╔══██╗████╗ ████║██╔══██╗██║   ██║██╔════╝
██║     ███████║██╔████╔██║██████╔╝██║   ██║███████╗
██║     ██╔══██║██║╚██╔╝██║██╔═══╝ ██║   ██║╚════██║
╚██████╗██║  ██║██║ ╚═╝ ██║██║     ╚██████╔╝███████║
 ╚═════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝      ╚═════╝ ╚══════╝
```

> 🎯 **一站式校园生活服务平台** - 让校园生活更便捷、更智能！

## 🛠️ 技术栈

<table>
<tr>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=spring" width="48" height="48" alt="Spring" />
<br>Spring Boot
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java" />
<br>Java 17
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="MySQL" />
<br>MySQL
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=redis" width="48" height="48" alt="Redis" />
<br>Redis
</td>
<td align="center" width="96">
<img src="https://skillicons.dev/icons?i=maven" width="48" height="48" alt="Maven" />
<br>Maven
</td>
</tr>
</table>

## 🎯 功能模块

| 模块 | 功能 | 状态 |
|:---:|:---|:---:|
| 👤 **用户中心** | 注册登录 · 个人信息 · 实名认证 | ✅ |
| 🛒 **二手市场** | 商品发布 · 智能搜索 · 收藏关注 | ✅ |
| 🍜 **食堂点餐** | 在线点餐 · 订单追踪 · 评价系统 | ✅ |
| 🔧 **校园报修** | 一键报修 · 进度追踪 · 服务评价 | ✅ |
| 📅 **校园活动** | 活动发布 · 在线报名 · 签到打卡 | ✅ |
| 📰 **校园新闻** | 资讯浏览 · 分类展示 · 热点推送 | ✅ |
| 💬 **即时通讯** | 在线聊天 · 消息推送 · WebSocket | ✅ |
| 🤖 **AI助手** | 智能问答 · 校园导航 · 生活助手 | ✅ |

## 🚀 快速开始

### 📋 环境要求

```yaml
Java: 17+
Maven: 3.6+
MySQL: 8.0+
```

### ⚡ 一键启动

```bash
# 🔽 克隆项目
git clone https://github.com/lxxxDD/campus-life-server.git

# 📂 进入目录
cd campus-life-server

# 🗄️ 导入数据库 (执行 sql/ 目录下的脚本)

# ⚙️ 配置数据库连接
# 编辑 src/main/resources/application.yml

# 🚀 启动项目
mvn spring-boot:run
```

### 📚 API文档

启动后访问: **http://localhost:8080/doc.html**

<img src="https://img.shields.io/badge/Knife4j-API%20Doc-blue?style=flat-square" />

## 📁 项目结构

```
📦 CampusLifeServer
 ┣ 📂 src/main/java
 ┃ ┣ 📂 common        # 🔧 通用组件
 ┃ ┣ 📂 config        # ⚙️ 配置类
 ┃ ┣ 📂 controller    # 🎮 控制器
 ┃ ┣ 📂 entity        # 📋 实体类
 ┃ ┣ 📂 mapper        # 🗺️ Mapper接口
 ┃ ┣ 📂 service       # 💼 业务逻辑
 ┃ ┗ 📂 util          # 🛠️ 工具类
 ┣ 📂 sql             # 📜 数据库脚本
 ┗ 📂 uploads         # 📁 上传文件
```

## 🔗 相关项目

<table>
<tr>
<td align="center">
<a href="https://github.com/lxxxDD/campus-life-app">
<img src="https://img.shields.io/badge/📱-移动端-green?style=for-the-badge" />
</a>
<br><sub>uni-app + Vue</sub>
</td>
<td align="center">
<a href="https://github.com/lxxxDD/campus-life-admin">
<img src="https://img.shields.io/badge/💻-管理后台-blue?style=for-the-badge" />
</a>
<br><sub>Vue 3 + Element Plus</sub>
</td>
</tr>
</table>

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请点个Star支持一下！**

Made with ❤️ by [lxxxDD](https://github.com/lxxxDD)

</div>
