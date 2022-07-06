# YaCy pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/yacy.svg)](https://dash.yunohost.org/appci/app/yacy) ![](https://ci-apps.yunohost.org/ci/badges/yacy.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/yacy.maintain.svg)  
[![Installer YaCy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yacy)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer YaCy rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

The YaCy search engine software provides results from a network of independent peers, instead of a central server. It is a distributed network where no single entity decides what to list or order it appears in.


**Version incluse :** 1.0~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot01.png)

## Documentations et ressources

* Site officiel de l'app : https://yacy.net/
* Dépôt de code officiel de l'app : https://github.com/yacy/yacy_search_server
* Documentation YunoHost pour cette app : https://yunohost.org/app_yacy
* Signaler un bug : https://github.com/YunoHost-Apps/yacy_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/yacy_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade yacy -u https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps