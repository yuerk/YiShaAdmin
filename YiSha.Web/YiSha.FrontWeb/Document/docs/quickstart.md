﻿## 简介

<code>YiShaAdmin</code>是一款基于.NET Core + Bootstrap的企业级快速后台开发框架。内置模块如：用户管理、部门管理、菜单管理、角色权限设置、日志管理、新闻管理等。
在线定时任务配置；支持Sql Server，MySql和Oracle数据库。

## 主要特性

* 部分响应式布局（电脑端完全支持，手机端对数据添加和修改的体验不友好）
* 强大的一键生成功能（包括视图、控制器、业务类、实体类、服务类、菜单）
* 支持Sql Server、MySql和Oracle数据库
* 基于角色的权限控制（Role-Based Access Control），可控制到按钮
* 对常用js插件进行二次封装，使js代码变得简洁，更加容易维护
* 完善的日志记录体系

## 技术框架
- 前端：Bootstrap
- 核心框架：.NET Core 2.2
- 缓存层：Memory Cache、Redis(即将支持)
- 持久层框架：Entity Framework Core
- 数据库支持：SqlServer、MySql、Oracle
- 定时任务：Quartz.Net
- API文档显示工具：Swagger UI
 
## 内置功能

- 员工管理：员工是系统操作者，该功能主要完成系统用户配置
- 部门管理：配置系统组织机构（公司、部门、小组）
- 职位管理：配置系统用户所担任职务
- 文章中心：管理新闻及公司案例
- 角色管理：角色菜单权限分配，角色对应权限，员工属于某个角色
- 菜单管理：配置系统菜单，操作权限，按钮权限标识
- 通用字典：系统里动态改变的数据，像文章类型，用字典进行维护，不变的数据，可以用枚举
- 行政区划：全国的省市县三级数据，展示树形数据的使用
- 系统日志（登录日志、操作日志、Api日志）：查看系统的登录、操作、Api调用日志
- 定时任务：在线（添加、修改、删除）任务调度，包含执行结果日志
- 系统Api：Api文档与测试工具
- 数据表管理：查看当前数据库所有表、字段及记录总数
- 代码生成：快速生成对单表的增删改查
- 服务器信息：查看服务器的基本信息