# 校园生活APP - 后端服务

## 项目简介
校园生活APP后端服务，基于Spring Boot 3.3.5开发，为移动端和管理后台提供API接口。

## 技术栈
- **框架**: Spring Boot 3.3.5
- **ORM**: MyBatis-Plus 3.5.7
- **数据库**: MySQL 8.0
- **认证**: JWT
- **文档**: Knife4j (Swagger)
- **构建**: Maven

## 功能模块
| 模块 | 说明 |
|------|------|
| 用户管理 | 注册、登录、个人信息 |
| 二手市场 | 商品发布、浏览、收藏 |
| 食堂点餐 | 菜品浏览、下单、订单管理 |
| 校园报修 | 报修提交、进度查询、评价 |
| 校园活动 | 活动浏览、报名参与 |
| 校园新闻 | 新闻资讯浏览 |
| 消息通知 | 系统通知、站内消息 |
| AI助手 | 智能问答服务 |

## 快速开始

### 环境要求
- JDK 17+
- Maven 3.6+
- MySQL 8.0+

### 运行步骤
```bash
# 1. 克隆项目
git clone https://github.com/lxxxDD/campus-life-server.git

# 2. 导入数据库
# 执行 sql/ 目录下的SQL脚本

# 3. 修改配置
# 编辑 src/main/resources/application.yml 配置数据库连接

# 4. 运行项目
mvn spring-boot:run
```

### API文档
启动后访问: http://localhost:8080/doc.html

## 项目结构
```
src/main/java/
├── common/          # 通用类
├── config/          # 配置类
├── controller/      # 控制器
├── entity/          # 实体类
├── mapper/          # Mapper接口
├── service/         # 服务层
└── util/            # 工具类
```

## 相关项目
- [移动端](https://github.com/lxxxDD/campus-life-app)
- [管理后台](https://github.com/lxxxDD/campus-life-admin)
