<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Logdy YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![Instalatu Logdy YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Logdy YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Logdy is a single-binary that you add to your PATH so it's available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it's also secure.

**Paketatutako bertsioa:** 0.13.0~ynh1

**Demoa:** <https://demo.logdy.dev/>

## Pantaila-argazkiak

![Logdy(r)en pantaila-argazkia](./doc/screenshots/example.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://logdy.dev/>
- Administratzaileen dokumentazio ofiziala: <https://logdy.dev/docs/quick-start>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/logdyhq/logdy-core>
- YunoHost Denda: <https://apps.yunohost.org/app/logdy>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
edo
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
