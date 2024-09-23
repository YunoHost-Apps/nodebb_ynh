<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# NodeBB YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/nodebb.svg)](https://ci-apps.yunohost.org/ci/apps/nodebb/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/nodebb.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/nodebb.maintain.svg)

[![Instalatu NodeBB YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nodebb)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek NodeBB YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

NodeBB is built using the Node.js server-side Javascript platform, delivering unmatched performance.
Building on this high performance platform means fast and dependable performance that will support even the biggest and most active community.

**Paketatutako bertsioa:** 3.7.3~ynh1

**Demoa:** <https://try.nodebb.org>

## Pantaila-argazkiak

![NodeBB(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://nodebb.org>
- Administratzaileen dokumentazio ofiziala: <https://docs.nodebb.org>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/NodeBB/NodeBB>
- YunoHost Denda: <https://apps.yunohost.org/app/nodebb>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/nodebb_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/nodebb_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/nodebb_ynh/tree/testing --debug
edo
sudo yunohost app upgrade nodebb -u https://github.com/YunoHost-Apps/nodebb_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
