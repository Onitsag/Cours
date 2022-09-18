---
description: Utilisation générale de Git
---

# 💾 Git

## Configuration

Se mettre à **l'emplacement du dossier** où l'on veut **créer le dépôt**, puis faire:

```
git init
```

Configurer l'utilisateur et l'email:

```
git config --global user.name "Prénom Nom"
git config --gobal user.email "exemple@gmail.com"
```

Se lier au lien du projet GitHub:

```
git remote add origin Lien-Du-Projet
```

## Récupérer le contenu distant

Faire un pull:

```
git pull
```

## Envoyer le contenu local

Ajouter tous les fichiers modifs:

```
git add .
```

Créer un commit:

```
git commit -m "Nom du commit"
```

Faire un push:

```
git push
```
