<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Logdy for YunoHost

[![Integration level](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![Working status](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![Install Logdy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Logdy quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Logdy is a single-binary that you add to your PATH so it's available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it's also secure.

**Shipped version:** 0.13.0~ynh2

**Demo:** <https://demo.logdy.dev/>

## Screenshots

![Screenshot of Logdy](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://logdy.dev/>
- Official admin documentation: <https://logdy.dev/docs/quick-start>
- Upstream app code repository: <https://github.com/logdyhq/logdy-core>
- YunoHost Store: <https://apps.yunohost.org/app/logdy>
- Report a bug: <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
or
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
