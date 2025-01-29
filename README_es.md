<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Argos para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Estado funcional](https://apps.yunohost.org/badge/state/argos)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/argos)

[![Instalar Argos con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarArgos rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**Versión actual:** 0.7.3~ynh1

## Capturas

![Captura de Argos](./doc/screenshots/screenshot.jpg)

## Documentaciones y recursos

- Sitio web oficial: <https://argos-monitoring.framasoft.org/#>
- Documentación administrador oficial: <https://argos-monitoring.framasoft.org/>
- Repositorio del código fuente oficial de la aplicación : <https://framagit.org/framasoft/framaspace/argos/>
- Catálogo YunoHost: <https://apps.yunohost.org/app/argos>
- Reportar un error: <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
o
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
