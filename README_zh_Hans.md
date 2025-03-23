<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 YaCy

[![集成程度](https://apps.yunohost.org/badge/integration/yacy)](https://ci-apps.yunohost.org/ci/apps/yacy/)
![工作状态](https://apps.yunohost.org/badge/state/yacy)
![维护状态](https://apps.yunohost.org/badge/maintained/yacy)

[![使用 YunoHost 安装 YaCy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yacy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 YaCy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

The YaCy search engine software provides results from a network of independent peers, instead of a central server.
It is a distributed network where no single entity decides what to list or order it appears in.


**分发版本：** 1.924~ynh2

## 截图

![YaCy 的截图](./doc/screenshots/screenshot01.png)

## 文档与资源

- 官方应用网站： <https://yacy.net/>
- 上游应用代码库： <https://github.com/yacy/yacy_search_server>
- YunoHost 商店： <https://apps.yunohost.org/app/yacy>
- 报告 bug： <https://github.com/YunoHost-Apps/yacy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/yacy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
或
sudo yunohost app upgrade yacy -u https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
