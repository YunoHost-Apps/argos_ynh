<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Argos voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/argos)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/argos)

[![Argos met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Argos snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**Geleverde versie:** 0.7.3~ynh1

## Schermafdrukken

![Schermafdrukken van Argos](./doc/screenshots/screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://argos-monitoring.framasoft.org/#>
- Officiele beheerdersdocumentatie: <https://argos-monitoring.framasoft.org/>
- Upstream app codedepot: <https://framagit.org/framasoft/framaspace/argos/>
- YunoHost-store: <https://apps.yunohost.org/app/argos>
- Meld een bug: <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
of
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
