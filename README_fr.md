<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# TLDraw pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/tldraw.svg)](https://dash.yunohost.org/appci/app/tldraw) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/tldraw.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/tldraw.maintain.svg)

[![Installer TLDraw avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tldraw)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer TLDraw rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

TLDraw est une petite application de dessin.

### Caractéristiques

- UX très propre et agréable
- Empreinte mémoire vive et très faible sur le serveur
- Prêt pour PWA
- Mode multijoueur (compatible iFrame)

**Version incluse :** 1.24.5~ynh3

**Démo :** <https://tldraw.com>

## Captures d’écran

![Capture d’écran de TLDraw](./doc/screenshots/TLDraw_screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://tldraw.com>
- Dépôt de code officiel de l’app : <https://github.com/tldraw/tldraw>
- YunoHost Store : <https://apps.yunohost.org/app/tldraw>
- Signaler un bug : <https://github.com/YunoHost-Apps/tldraw_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tldraw -u https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
