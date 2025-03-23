<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# YaCy YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/yacy)](https://ci-apps.yunohost.org/ci/apps/yacy/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/yacy)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/yacy)

[![Instalatu YaCy YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=yacy)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek YaCy YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

The YaCy search engine software provides results from a network of independent peers, instead of a central server.
It is a distributed network where no single entity decides what to list or order it appears in.


**Paketatutako bertsioa:** 1.924~ynh2

## Pantaila-argazkiak

![YaCy(r)en pantaila-argazkia](./doc/screenshots/screenshot01.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://yacy.net/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/yacy/yacy_search_server>
- YunoHost Denda: <https://apps.yunohost.org/app/yacy>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/yacy_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/yacy_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
edo
sudo yunohost app upgrade yacy -u https://github.com/YunoHost-Apps/yacy_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
