<div align="center">
  <h2>SPAdmin</h2>
  <a href="#" target="_blank">
      <img src="https://images.gitee.com/uploads/images/2021/0224/195754_b55ad391_87650.png" width="200">
  </a>
</div>

#### 介绍

市面上权限框架大多都是采用SpringBoot、MyBatis、Shiro的居多，这里来一个SpringBoot、JPA、Shiro的。

#### 基础环境

JDK1.8、Maven、Mysql、Redis、IntelliJ IDEA、minio、fastdfs、OpenOffice


#### 相关组件

- [ok-admin](https://gitee.com/bobi1234/ok-admin)
- [vue](https://cn.vuejs.org/)
- [iView](http://v1.iviewui.com/)
- [echarts](https://echarts.apache.org/zh/index.html)
- clipboard
- cropperjs
- lightbox
- nprogress
- webuploader
- ztree

#### 内置功能

- 组织机构：机构管理、用户管理、角色管理、行政区域。

- 系统监控：系统日志、在线用户，后期会慢慢追加完善。

- 应用管理：任务调度、邮件管理、图片管理、文章管理、人工智能，每个模块只需要你稍作修改就可以打造成一个项目了。

- 爪哇妹子：一个妹子图小程序后台管理。

- 工作流：一个简单的工作流功能，后期慢慢完善。

- 文档管理：文档上传、转换、预览功能，后期慢慢完善。

- 系统管理：敏捷开发、系统菜单、全局配置、在线代码编辑器，小伙伴们只需要设计好表结构，三秒中就能撸出一个增删查改的模块。



#### 安装教程

- 启动前请配置 `application-dev.properties` 中相关`mysql`、`redis`以及非启动强依赖配置邮件、鉴黄、阿里云存储、分布式文件存储。

- 数据库脚本位于企鹅群 `933593697`共享文件`炒鸡工具箱基础语句`，启动前请自行导入。

- 请自行启动 `redis`，见基础环境目录，里面有配置教程。

- 请自行安装 `OpenOffice`，文件过大，不易上传，见群文件。

- 配置完成，运行`Application`中的 `main `方法。

- 测试账号：admin 密码：admin2020

- 最后如果不想安装各种依赖，请切换分支到纯净版

