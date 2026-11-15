# [Flask] Web 框架分步入门

**课程与代码（2026 年 9 月）**：👉 **[https://stahe.github.io/zh-flask-sept-2026/](https://stahe.github.io/zh-flask-sept-2026/)**

## 作者

代码和课程完全由 Anthropic 的 AI **Claude** 应 Serge Tahé 的请求编写，Claude 是**唯一作者**。

## 概述

本课程分步讲解如何使用 **Flask**（Python）框架构建 MVC Web 应用程序。HTML 页面由服务器通过 **Jinja2** 视图生成，不使用客户端 JavaScript 框架。

它紧接在课程《[[Spring MVC](https://stahe.github.io/zh-springmvc-sept-2026/) Web 框架分步入门》之后，并遵循完全相同的进程。该课程本身又遵循课程 [ASP.NET Core MVC](https://stahe.github.io/aspnetcoremvc-sept-2026/) 和 [NestJS](https://stahe.github.io/nestjs-html-sept-2026/)。示例的编号相同，涵盖的主题也相同：熟悉其中任何一门课程的读者，都可以逐个示例地比较这些框架。

课程分为两个部分：

- **28 个简短示例**，每个示例聚焦一个具体概念：
  - 动作、路由、响应和重定向；
  - 参数绑定和验证（Pydantic）；
  - Jinja2 视图、模板和宏；
  - WTForms 表单、Post/Redirect/Get 模式和 CSRF 防护；
  - 国际化；
  - 数据作用域；
  - 请求生命周期；
  - JWT 身份验证、角色和验证码（CAPTCHA）；
  - 使用 SQLAlchemy 和 MySQL 的分层架构。
- **一个完整的案例研究**：*RdvMedecins*，一个医疗诊所的预约管理应用程序。它具有三种用户角色（管理员、医生、患者），支持法语和英语，并能防范机器人。课程对其所有文件都加以注释。

## 技术

Python 3.12+ · Flask 3.1 · Jinja2 · Werkzeug · Flask-WTF / WTForms · Pydantic · SQLAlchemy 2.1 · PyMySQL · PyJWT · bcrypt · Babel · waitress · Bootstrap 5.3 · MySQL 8 / MariaDB

## 先决条件

- Python 3.12 或更高版本；
- Visual Studio Code，以及 Microsoft 的“Python”扩展；
- MySQL 8（例如在 Windows 上使用 Laragon）或 MariaDB；
- curl。

这些工具的安装说明见课程附录。

## 代码仓库内容

- `examples/`：28 个示例，每个都是一个小型 Flask 应用程序（端口 5000）；
- `rdvmedecins2-flask/`：案例研究（端口 8081），包含其 SQL 脚本和 `README.md`；
- `directory.txt`：完整的目录结构。
