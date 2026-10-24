# OrderManagementSystem-Delphi-BIT

**简体中文** | [English](README.en.md)

北京理工大学《数据库设计与开发》课程外卖订单管理项目，Delphi VCL 客户端连接 PostgreSQL，覆盖顾客、餐厅、骑手和管理员角色。

## 环境要求

Windows、Delphi、PostgreSQL 与位数匹配的 PostgreSQL ODBC 驱动。精确版本需结合课程手册和源代码环境确认。

## 获取仓库

```bash
git clone https://github.com/RoxyXu151/OrderManagementSystem-Delphi-BIT.git
cd OrderManagementSystem-Delphi-BIT
```

私有仓库需要先通过 GitHub 认证。以下相对路径与操作均以本仓库为起点。

## 安装与启动

本项目按下方说明使用对应编辑器或阅读工具；当前没有统一的命令行启动步骤。

## 配置与准备

先阅读使用说明书.pdf 和设计文档.pdf。新建测试数据库，审阅 SQL脚本.sql 后再导入；在客户端 connection.ini 与 ODBC 数据源中配置自己的地址、库名和账号。物理备份通常还需匹配 PostgreSQL 版本。

## 使用方法与产物

在源代码目录找到 Delphi .dpr 工程并打开编译，或使用已有课程演示程序。选择用户角色后登录，按下单、接单、配送和管理流程验证。数据库初始化可能创建或覆盖对象，应在独立测试库执行。

## 仓库导览

- [SQL脚本.sql](SQL%E8%84%9A%E6%9C%AC.sql)
- [使用说明书.pdf](%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E%E4%B9%A6.pdf)
- [设计文档.pdf](%E8%AE%BE%E8%AE%A1%E6%96%87%E6%A1%A3.pdf)
- [原有详细资料](README.reference.md)：保留历史设计、截图和说明；涉及启动配置时以上述核对说明为准。

## 验证与常见问题

检查客户端与 ODBC 位数、数据库连接、角色权限和订单状态流转。当前没有统一自动化测试脚本或可在所有机器直接运行的安装器。

## 维护与贡献

修改功能或使用方式时同步更新中英文 README。问题反馈请附复现步骤、环境版本与去除敏感信息后的日志；提交改动时说明实际完成的验证。

## 许可与来源

当前根目录没有独立的许可证文件；不据此推定已授予开源再分发许可。第三方材料按各自条款使用。
