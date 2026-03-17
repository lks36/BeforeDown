# Before Dawn - Projet Unity (Groupe I)

## Présentation du Projet
**Before Dawn** est un jeu hybride mélangeant **Tower Defense** et **RTS** (Stratégie en Temps Réel) développé avec le moteur Unity. Le joueur est plongé dans un univers de fantasy futuriste où il doit défendre son territoire contre une invasion de monstres avant l'aube.

Le projet s'inspire de titres classiques comme *Warcraft III* pour le contrôle et la grille de jeu, ainsi que *Clash Royale* pour la structure de la carte et le mode multijoueur.

## Documentation et Rapport
Pour une analyse détaillée du développement, de l'architecture technique et des défis rencontrés par l'équipe, vous pouvez consulter le rapport complet :
* **Rapport Final (PDF) :** Disponible dans ce dépôt [Rapport](./Final_Report.pdf), il couvre l'intégralité du cycle de vie du projet, de la conception à la présentation finale.
* **Manuel Utilisateur :** Inclus dans la documentation [UserManuel](./UserManuel.pdf) pour guider l'installation et la prise en main du jeu.

## Mécaniques de Jeu
* **Économie :** Extraction d'or via des mineurs qui font la navette entre les mines et la base pour financer l'armée.
* **Système Gacha :** Attribution aléatoire d'un héros au début de chaque partie via une loterie pour varier l'expérience de jeu.
* **Gestion des Unités :** Production de troupes (archers, guerriers, mages) via des camps d'entraînement destructibles.
* **Défense :** Placement libre de tours (Archers, Mages) avec un système de vérification pour éviter les superpositions.

## Fonctionnalités Techniques
* **Intelligence Artificielle :** * Les unités ciblent prioritairement la tour principale ennemie mais attaquent les menaces les plus proches en chemin.
    * Pathfinding automatique pour le héros et les troupes.
* **Multijoueur :** Système de lobby permettant de créer ou de rejoindre des salons avec gestion du "Host" pour lancer la partie.
* **Interface (UI) :** Menus de réglages complets (volume, musique), écrans de chargement asynchrones et panneaux de victoire/défaite.

## L'Équipe (Groupe I)
* **Florent JIN :** Gameplay, IA, Multijoueur et Graphismes.
* **Kun LI :** UI (Jeu & Web), Gacha, Sons et intégration Web.
* **Frédéric LIN :** IA, intégration des assets et support Multijoueur.
* **Daniel ABOU-ORM :** Planning, organisation et support UI/Web.

## Assets et Ressources
* **Graphismes :** Modèles 3D adaptés depuis Mixamo et Unity Free Assets (Kenney) pour une esthétique soignée.
* **Audio :** Effets sonores et musiques d'ambiance provenant de "Soundscrate".

## Installation
Le jeu est prêt à être testé sur macOS :
* **Installation Mac :** Téléchargez le fichier [BeforeDawn.pkg](./BeforeDawn.pkg) présent dans les releases ou à la racine du dépôt. 
* **Note :** Ce package installe l'exécutable complet ainsi que les ressources nécessaires pour jouer sur votre Mac.

---
*Projet réalisé dans le cadre de la première année à l'EPITA, finalisé le 6 juin 2023.*
