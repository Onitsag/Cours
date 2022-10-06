---
description: >-
  Le MVC (Modèle Vue Contrôleur) est une structure de fichiers servant de
  référentiel de base dans la création d'un site Web.
---

# MVC



{% embed url="https://github.com/c4software/mini-mvc-sample/releases" %}
MVC proposé par Valentin Brosseau ([https://cours.brosseau.ovh/](https://cours.brosseau.ovh/))
{% endembed %}

Il est possible de lancer un serveur Web en local:

```shell
# Windows (avec XAMPP)
C:/xampp/php/php -S localhost:9000

# Windows (avec WAMP)
C:/wamp64/bin/php/php7.4.9/php -S localhost:9000

# Linux / OSX
php -S localhost:9000
```

### Configurer le PC pour une commande simplifiée

**Commande simplifiée**

```shell
php
php mvc serve
```

Recherchez les variables d'environnement dans la barre de recherche Windows

<figure><img src="../../.gitbook/assets/Screenshot_1 (1).png" alt=""><figcaption></figcaption></figure>

Modifier les variables d'environnement

<figure><img src="../../.gitbook/assets/Screenshot_2.png" alt=""><figcaption></figcaption></figure>

Modifier la variable Path

<figure><img src="../../.gitbook/assets/Screenshot_3.png" alt=""><figcaption></figcaption></figure>

Ajouter la variable PHP

<figure><img src="../../.gitbook/assets/Screenshot_5.png" alt=""><figcaption></figcaption></figure>

## Création Model & Controller

```shell
#Création d'un Model
C:\xampp\php\php mvc model:create NomModel

#Création d'un Controller
C:\xampp\php\php mvc controller:create NomController
```
