<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Argos для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Состояние работы](https://apps.yunohost.org/badge/state/argos)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/argos)

[![Установите Argos с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Argos быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A monitoring and status board for websites. Test how your websites respond to external checks, get notified when something goes wrong.

### Features

- Server-Agent architecture: The server is responsible for storing the configuration and the results of the checks. The agent is responsible for running the checks and sending the results to the server.
- Extensibility: New checks can be added using python.
- A Website allows to navigate the results of the checks.
- HTTP API: An HTTP API is exposed to get the results of the checks.



**Поставляемая версия:** 0.7.3~ynh1

## Снимки экрана

![Снимок экрана Argos](./doc/screenshots/screenshot.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://argos-monitoring.framasoft.org/#>
- Официальная документация администратора: <https://argos-monitoring.framasoft.org/>
- Репозиторий кода главной ветки приложения: <https://framagit.org/framasoft/framaspace/argos/>
- Магазин YunoHost: <https://apps.yunohost.org/app/argos>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
или
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
