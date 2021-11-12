<!--
    需要填充的占位符：
    
    README.md
    
        ApacheCN 数据库译文集：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        db：域名前缀
        飞龙：负责人名称
        wizardforcel：负责人 Github 用户名
        562826179：负责人 QQ
        apachecn-db-zh：ApacheCN 的 Github 仓库名称
        apachecn-db-zh：DockerHub 仓库名称
        apachecn-db-zh：PYPI 包名称
        apachecn-db-zh：NPM 包名称
    
    CNAME
    
        db：域名前缀

    index.html
    
        ApacheCN 数据库译文集：文档中文名
        {color}：显示颜色
        apachecn-db-zh：ApacheCN 的 Github 仓库名称

    asset/docsify-apachecn-footer.js
    
        apachecn-db-zh：ApacheCN 的 Github 仓库名称
-->

# ApacheCN 数据库译文集

> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 人最大的痛苦就是说一些自己都不相信的话。

* [在线阅读](https://db.apachecn.org)
* [在线阅读（Gitee）](https://apachecn.gitee.io/doc-template/)
* [ApacheCN 学习资源](http://docs.apachecn.org/)

## 目录

+   [创建你的 Mysql 数据库](docs/create-your-mysql-db/SUMMARY.md)
+   [Redis 学习手册](docs/learn-redis/SUMMARY.md)
+   [精通 MongoDB 4.x](docs/master-mongodb-4x/SUMMARY.md)
+   [精通 PHPMyAdmin 3.4 高效 MySQL 管理](docs/master-phpma-34-effec-mysql-mgt/SUMMARY.md)
+   [MongoDB 秘籍](docs/mongodb-cb/SUMMARY.md)
+   [MongoDB 数据建模](docs/mongodb-data-mod/SUMMARY.md)
+   [MongoDB 基础知识](docs/mongodb-fund/SUMMARY.md)
+   [MySQL8 管理手册](docs/mysql8-admin-guide/SUMMARY.md)
+   [MySQL8 秘籍](docs/mysql8-cb/SUMMARY.md)
+   [MySQL 管理手册](docs/mysql-mgt-admin/SUMMARY.md)

## 贡献指南

本项目需要校对，欢迎大家提交 Pull Request。

> 请您勇敢地去翻译和改进翻译。虽然我们追求卓越，但我们并不要求您做到十全十美，因此请不要担心因为翻译上犯错——在大部分情况下，我们的服务器已经记录所有的翻译，因此您不必担心会因为您的失误遭到无法挽回的破坏。（改编自维基百科）

## 联系方式

### 负责人

* [飞龙](https://github.com/wizardforcel): 562826179

### 其他

*   在我们的 [apachecn/apachecn-db-zh](https://github.com/apachecn/apachecn-db-zh) github 上提 issue.
*   发邮件到 Email: `apachecn@163.com`.
*   在我们的 [组织学习交流群](http://www.apachecn.org/organization/348.html) 中联系群主/管理员即可.

## 下载

### Docker

```
docker pull apachecn0/apachecn-db-zh
docker run -tid -p <port>:80 apachecn0/apachecn-db-zh
# 访问 http://localhost:{port} 查看文档
```

### PYPI

```
pip install apachecn-db-zh
apachecn-db-zh <port>
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g apachecn-db-zh
apachecn-db-zh <port>
# 访问 http://localhost:{port} 查看文档
```

## 赞助我们

![](http://data.apachecn.org/img/about/donate.jpg)
