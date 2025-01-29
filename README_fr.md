<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Argos pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/argos)](https://ci-apps.yunohost.org/ci/apps/argos/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/argos)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/argos)

[![Installer Argos avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=argos)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Argos rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un tableau de contrôle et d'état pour les sites web. Testez la façon dont vos sites web réagissent aux contrôles externes et recevez une notification lorsque quelque chose ne va pas.

### Caractéristiques

- Architecture serveur-agent : Le serveur est chargé de stocker la configuration et les résultats des contrôles. L'agent est chargé d'exécuter les contrôles et d'envoyer les résultats au serveur.
- Extensibilité : De nouveaux contrôles peuvent être ajoutés à l'aide de python.
- Un site web permet de naviguer dans les résultats des contrôles.
- API HTTP : Une API HTTP est exposée pour obtenir les résultats des contrôles.


**Version incluse :** 0.7.3~ynh1

## Captures d’écran

![Capture d’écran de Argos](./doc/screenshots/screenshot.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://argos-monitoring.framasoft.org/#>
- Documentation officielle de l’admin : <https://argos-monitoring.framasoft.org/>
- Dépôt de code officiel de l’app : <https://framagit.org/framasoft/framaspace/argos/>
- YunoHost Store : <https://apps.yunohost.org/app/argos>
- Signaler un bug : <https://github.com/YunoHost-Apps/argos_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/argos_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
ou
sudo yunohost app upgrade argos -u https://github.com/YunoHost-Apps/argos_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
