<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Logdy

[![集成程度](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![使用 YunoHost 安装 Logdy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Logdy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Logdy is a single-binary that you add to your PATH so it's available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it's also secure.

**分发版本：** 0.13.0~ynh1

**演示：** <https://demo.logdy.dev/>

## 截图

![Logdy 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://logdy.dev/>
- 官方管理文档： <https://logdy.dev/docs/quick-start>
- 上游应用代码库： <https://github.com/logdyhq/logdy-core>
- YunoHost 商店： <https://apps.yunohost.org/app/logdy>
- 报告 bug： <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
或
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
