# Rapport du TP 1 - DevOps & Automation
**Réalisé par :** Hicham Imlahi

## Introduction
Ce dépôt contient le travail réalisé pour le TP 1. L'objectif de ce TP est de mettre en pratique les commandes de base de Git et d'utiliser la plateforme GitHub pour la gestion de versions, en respectant un flux de travail avec des branches et une Pull Request.

---

## 1. Création du dépôt sur GitHub
Pour commencer, le dépôt distant a été créé directement sur l'interface de GitHub.

![Bouton Nouveau Dépôt](./capture/Screenshot%202026-03-26%20202110.png)
*Clic sur le bouton pour créer un nouveau dépôt.*

![Configuration du Dépôt](./capture/Screenshot%202026-03-26%20202207.png)
*Configuration du nom du dépôt en respectant la nomenclature demandée.*

---

## 2. Initialisation locale et Premier Commit (Branche `main`)
Le dossier du projet a été créé localement, suivi de l'initialisation de Git et de la création du répertoire pour stocker les captures d'écran.

![Initialisation Git](./capture/Screenshot%202026-03-26%20202340.png)
*Initialisation du dépôt Git local et création du dossier de captures.*

![Rédaction du README](./capture/Screenshot%202026-03-26%20202451.png)
*Création et édition de base du fichier README.md.*

![Ajout des fichiers](./capture/Screenshot%202026-03-26%20202803.png)
*Vérification du statut et ajout du fichier README.md à l'index.*

![Premier commit](./capture/Screenshot%202026-03-26%20202839.png)
*Exécution du tout premier commit sur le projet.*

![Liaison au dépôt distant](./capture/Screenshot%202026-03-26%20202936.png)
*Ajout du dépôt distant GitHub (origin).*

![Push de la branche main](./capture/Screenshot%202026-03-26%20212023.png)
*Envoi de la branche principale `main` vers GitHub.*

---

## 3. Travail sur la branche `dev`
Afin de ne pas impacter la branche principale, une nouvelle branche nommée `dev` a été créée pour le développement.

![Création de la branche dev](./capture/Screenshot%202026-03-26%20221244.png)
*Création et basculement sur la branche `dev`.*

![Création du fichier code](./capture/Screenshot%202026-03-26%20222725.png)
*Création d'un fichier source `hello.c` pour simuler le développement.*

![Ajout des modifications](./capture/Screenshot%202026-03-26%20223144.png)
*Ajout du nouveau fichier à l'index Git.*

![Commit sur dev](./capture/Screenshot%202026-03-26%20230726.png)
*Création d'un commit spécifique sur la branche `dev`.*

![Push de la branche dev](./capture/Screenshot%202026-03-26%20230924.png)
*Envoi de la branche `dev` vers le dépôt distant GitHub.*

---

## 4. Pull Request et Merge
Le travail sur la branche `dev` étant terminé, une Pull Request a été ouverte sur GitHub pour fusionner le code avec la branche `main`.

![Détection de la branche dev](./capture/Screenshot%202026-03-26%20231223.png)
*GitHub détecte le push récent et propose de créer une Pull Request.*

![Création de la Pull Request](./capture/Screenshot%202026-03-26%20231418.png)
*Ouverture et rédaction de la Pull Request.*

![Confirmation du Merge](./capture/Screenshot%202026-03-26%20231510.png)
*Validation de la fusion (Merge) dans la branche `main`.*

![Merge réussi](./capture/Screenshot%202026-03-26%20231529.png)
*Confirmation que la Pull Request a été fusionnée et fermée avec succès.*

---
**Conclusion :** L'ensemble du processus de versioning et de collaboration via Git/GitHub a été respecté et validé.