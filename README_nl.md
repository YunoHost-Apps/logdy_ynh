<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Logdy voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![Logdy met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Logdy snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Logdy is a single-binary that you add to your PATH so it's available just like any other tool: grep, awk, sed, jq. No installations, no deployments, no compilations. It works locally, so it's also secure.

**Geleverde versie:** 0.13.0~ynh1

**Demo:** <https://demo.logdy.dev/>

## Schermafdrukken

![Schermafdrukken van Logdy](./doc/screenshots/example.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://logdy.dev/>
- Officiele beheerdersdocumentatie: <https://logdy.dev/docs/quick-start>
- Upstream app codedepot: <https://github.com/logdyhq/logdy-core>
- YunoHost-store: <https://apps.yunohost.org/app/logdy>
- Meld een bug: <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
of
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
