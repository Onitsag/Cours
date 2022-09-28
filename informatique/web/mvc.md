---
description: >-
  Le MVC (Modèle Vue Contrôleur) est une structure de fichiers servant de
  référentiel de base dans la création d'un site Web.
---

# MVC

{% file src="../../.gitbook/assets/mini-mvc-sample-1.8.rar" %}
MVC proposé par Valentin Brosseau ([https://cours.brosseau.ovh/](https://cours.brosseau.ovh/))
{% endfile %}

Il est possible de lancer un serveur Web en local:

```shell
# Windows (avec XAMPP)
C:/xampp/php/php -S localhost:9000

# Windows (avec WAMP)
C:/wamp64/bin/php/php7.4.9/php -S localhost:9000

# Linux / OSX
php -S localhost:9000
```

## Création Model & Controller

```shell
#Création d'un Model
C:\xampp\php\php mvc model:create NomModel

#Création d'un Controller
C:\xampp\php\php mvc controller:create NomController
```
