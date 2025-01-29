<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Argos

[![集成程度](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![工作状态](https://apps.yunohost.org/badge/state/argos)
![维护状态](https://apps.yunohost.org/badge/maintained/argos)

[![使用 YunoHost 安装 Argos](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Argos。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**分发版本：** 0.7.3~ynh1

## 截图

![Argos 的截图](./doc/screenshots/screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://argos-monitoring.framasoft.org/#>
- 官方管理文档： <https://argos-monitoring.framasoft.org/>
- 上游应用代码库： <https://framagit.org/framasoft/framaspace/argos/>
- YunoHost 商店： <https://apps.yunohost.org/app/argos>
- 报告 bug： <https://github.com/YunoHost-Apps/argos_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/argos_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
或
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
