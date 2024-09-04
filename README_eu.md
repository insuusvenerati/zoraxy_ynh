<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zoraxy YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/zoraxy.svg)](https://ci-apps.yunohost.org/ci/apps/zoraxy/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/zoraxy.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/zoraxy.maintain.svg)

[![Instalatu Zoraxy YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zoraxy)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zoraxy YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Zoraxy is a new kid in reverse-proxy world written in Go, designed to simplify and streamline web routing and proxying. Zoraxy simplifies the process of setting up a reverse proxy, It serves as an intermediary between client requests and backend servers, effectively managing traffic flow. Whether you're running a small personal website or managing a complex web infrastructure, Zoraxy is designed to make these tasks accessible to all, regardless of your networking expertise.


**Paketatutako bertsioa:** 3.1.1~ynh1

**Demoa:** <https://demo.example.com>

## Pantaila-argazkiak

![Zoraxy(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://zoraxy.arozos.com/index.html>
- Administratzaileen dokumentazio ofiziala: <https://yunohost.org/packaging_apps>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/tobychui/zoraxy>
- YunoHost Denda: <https://apps.yunohost.org/app/zoraxy>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zoraxy_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zoraxy -u https://github.com/YunoHost-Apps/zoraxy_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
