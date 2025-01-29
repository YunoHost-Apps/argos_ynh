<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Argos untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Status kerja](https://apps.yunohost.org/badge/state/argos)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/argos)

[![Pasang Argos dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Argos secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**Versi terkirim:** 0.7.3~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Argos](./doc/screenshots/screenshot.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://argos-monitoring.framasoft.org/#>
- Dokumentasi admin resmi: <https://argos-monitoring.framasoft.org/>
- Depot kode aplikasi hulu: <https://framagit.org/framasoft/framaspace/argos/>
- Gudang YunoHost: <https://apps.yunohost.org/app/argos>
- Laporkan bug: <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
atau
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
