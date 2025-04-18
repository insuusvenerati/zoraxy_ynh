<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Zoraxy

[![集成程度](https://apps.yunohost.org/badge/integration/zoraxy)](https://ci-apps.yunohost.org/ci/apps/zoraxy/)
![工作状态](https://apps.yunohost.org/badge/state/zoraxy)
![维护状态](https://apps.yunohost.org/badge/maintained/zoraxy)

[![使用 YunoHost 安装 Zoraxy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zoraxy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Zoraxy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Zoraxy is a new kid in reverse-proxy world written in Go, designed to simplify and streamline web routing and proxying. Zoraxy simplifies the process of setting up a reverse proxy, It serves as an intermediary between client requests and backend servers, effectively managing traffic flow. Whether you're running a small personal website or managing a complex web infrastructure, Zoraxy is designed to make these tasks accessible to all, regardless of your networking expertise.


**分发版本：** 3.1.8~ynh1

## 截图

![Zoraxy 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://zoraxy.arozos.com/index.html>
- 官方管理文档： <https://github.com/tobychui/zoraxy/wiki/Getting-Started>
- 上游应用代码库： <https://github.com/tobychui/zoraxy>
- YunoHost 商店： <https://apps.yunohost.org/app/zoraxy>
- 报告 bug： <https://github.com/YunoHost-Apps/zoraxy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
或
sudo yunohost app upgrade zoraxy -u https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
