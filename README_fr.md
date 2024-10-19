<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Logdy pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/logdy.svg)](https://ci-apps.yunohost.org/ci/apps/logdy/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/logdy.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/logdy.maintain.svg)

[![Installer Logdy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=logdy)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Logdy rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Logdy est un binaire unique que vous ajoutez à votre PATH afin qu'il soit disponible comme n'importe quel autre outil : grep, awk, sed, jq. Aucune installation, aucun déploiement, aucune compilation. Il fonctionne localement, il est donc également sécurisé.

**Version incluse :** 0.13.0~ynh1

**Démo :** <https://demo.logdy.dev/>

## Captures d’écran

![Capture d’écran de Logdy](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://logdy.dev/>
- Documentation officielle de l’admin : <https://logdy.dev/docs/quick-start>
- Dépôt de code officiel de l’app : <https://github.com/logdyhq/logdy-core>
- YunoHost Store : <https://apps.yunohost.org/app/logdy>
- Signaler un bug : <https://github.com/YunoHost-Apps/logdy_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/logdy_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade logdy -u https://github.com/YunoHost-Apps/logdy_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
