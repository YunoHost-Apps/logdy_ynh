<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Logdy untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![Pasang Logdy dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Logdy secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Logdy is a single-binary that you add to your PATH so it's available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it's also secure.

**Versi terkirim:** 0.13.0~ynh1

**Demo:** <https://demo.logdy.dev/>

## Tangkapan Layar

![Tangkapan Layar pada Logdy](./doc/screenshots/example.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://logdy.dev/>
- Dokumentasi admin resmi: <https://logdy.dev/docs/quick-start>
- Depot kode aplikasi hulu: <https://github.com/logdyhq/logdy-core>
- Gudang YunoHost: <https://apps.yunohost.org/app/logdy>
- Laporkan bug: <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
atau
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
