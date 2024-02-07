# OpenClassrooms Projet 09 : Billed

**Objectif :** Débugger et tester un SaaS RH.

## Contexte

SaaS de l’entreprise imaginaire “Billed”.

L’entreprise produit des solutions SaaS destinées aux équipes de ressources humaines.

Dans cette perspective, ma mission était d’implémenter des tests unitaires et d'intégration ainsi que de corriger une liste de bugs. Le détail de la procédure peut être trouvé dans le fichier PDF "TODO_list" ainsi qu'une capture d'écran de la couverture des différents tests, présents dans le dossier "Docs" de ce Repo.

De plus, je devais écrire un plan de test End to End pour guider la personne qui devra faire le test manuellement. Ce document "plan_tests_E2E.pdf" est également présent dans le dossier "Docs" de ce Repo.

## L'architecture du projet

Ce projet, le back-end de l'application, doit être lancé en local avec le front-end de celle-ci.

Le projet front-end se trouve ici: https://github.com/Cycle9898/OC_Projet-9_Billed_Front

## Lancement de l'application en local

### Cloner le projet:

```
git clone https://github.com/Cycle9898/OC_Projet-9_Billed_Back.git
```

### Acceder au repertoire du projet :

```
cd Billed-app-FR-Back
```

### Installer les dépendances du projet :

```
yarn
```

### Lancer l'API :

```
yarn run:dev
```

### Accéder à l'API :

L'api est accessible sur le port `5678` en local: `http://localhost:5678`

## Utilisateurs par défaut:

### administrateur :

```
utilisateur : admin@test.tld
mot de passe : admin
```

### employé :

```
utilisateur : employee@test.tld
mot de passe : employee
```
