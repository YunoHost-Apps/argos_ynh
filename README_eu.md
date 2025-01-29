<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Argos YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/argos)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/argos)

[![Instalatu Argos YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Argos YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**Paketatutako bertsioa:** 0.7.3~ynh1

## Pantaila-argazkiak

![Argos(r)en pantaila-argazkia](./doc/screenshots/screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://argos-monitoring.framasoft.org/#>
- Administratzaileen dokumentazio ofiziala: <https://argos-monitoring.framasoft.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://framagit.org/framasoft/framaspace/argos/>
- YunoHost Denda: <https://apps.yunohost.org/app/argos>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
edo
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
