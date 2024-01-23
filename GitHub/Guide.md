# Guide Pratique

## Introduction à Git

Git est un système de contrôle de version distribué conçu pour gérer tout, des petits aux grands projets, avec rapidité et efficacité. Il est utilisé pour suivre les modifications dans le code source au cours du temps.

## Initier un projet Git avec GitHub

Pour créer un repo Git sur GitHub rien de plus simple.


<img src="/img/1-create-repo.png" height="150px" />

1. **git init**
   - Description : Initialise un nouveau dépôt Git local.
   - Utilisation : 
        ```bash
        git init
        ```

2. **git clone**
   - Description : Clone un dépôt depuis une source externe.
   - Utilisation : 
        ```bash
        git clone [url]
        ```

3. **git checkout**
   - Description : Crée une nouvelle branche
   - Utilisation : 
        ```bash
        git checkout -b [nom de la branche]
        ```

4. **git add**
   - Utilisation fréquente:
  
        Description : Ajoute tout les fichiers à la zone de préparation (staging area) pour le prochain commit.
        ```bash
        git add .
        ```
   - Utilisation recommendée
    
        Description : Ajoute un fichier à la zone de préparation (staging area) pour le prochain commit.
  
        Pour éviter de publier maladroitement des fichiers d'environnement, des cédentials de base de données ou tout autres fichier qui ne devrait pas l'être je recommand d'utiliser cette commande
        ```bash
        git add [fichier]
        ```
5. **git status**
   - Description : Montre l'état des fichiers (modifiés, ajoutés, non suivis).
   - Conseil ne pas hésitez à faire un git status avant un git add ou un git commit
   - Utilisation : 
        ```bash
        git status
        ```
   

6. **git commit**
   - Description : Enregistre les modifications dans le dépôt avec un message descriptif.
   - Utilisation : 
        ```bash
        git commit -m "[message de commit]"
        ```



7. **git push**
   - Description : Envoie les modifications de votre dépôt local vers un dépôt distant (appelé remote)
   - Utilisation : 
        ```bash
        git push [remote] [branche]
        ```

8. **git pull**
   - Description : Met à jour le dépôt local avec les modifications du dépôt distant.
   - Utilisation : 
        ```bash
        git pull [remote] [branche]
        ```

9. **git branch**
   - Description : Affiche les branches locales. Crée ou supprime des branches.
   - Utilisation : 
        ```bash
        git branch
        ```

10. **git checkout**
    - Description : Change de branche
    - Utilisation : 
        ```bash
        git checkout [nom de la branche]
        ```

11. **git merge**
    - Description : Fusionne une branche dans la branche active.
    - Utilisation : 
        ```bash
        git merge [nom de la branche]
        ```
