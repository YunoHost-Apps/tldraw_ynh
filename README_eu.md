<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# TLDraw YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/tldraw.svg)](https://ci-apps.yunohost.org/ci/apps/tldraw/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/tldraw.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/tldraw.maintain.svg)

[![Instalatu TLDraw YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tldraw)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek TLDraw YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

TLDraw is a tiny little drawing app.

### Features

- Very clean and nice UX
- Snappy and very low memory footprint on the server
- PWA ready
- Multiplayer mode (iFrame compatible)


**Paketatutako bertsioa:** 1.24.5~ynh3

**Demoa:** <https://tldraw.com>

## Pantaila-argazkiak

![TLDraw(r)en pantaila-argazkia](./doc/screenshots/TLDraw_screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://tldraw.com>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/tldraw/tldraw>
- YunoHost Denda: <https://apps.yunohost.org/app/tldraw>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/tldraw_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing --debug
edo
sudo yunohost app upgrade tldraw -u https://github.com/YunoHost-Apps/tldraw_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
