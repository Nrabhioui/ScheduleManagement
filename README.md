# Gestion d'École

## Présentation
Cette application C++ permet de gérer les ressources d'une école (professeurs, groupes, locaux, cours) à travers une interface graphique intuitive.  
Elle offre des fonctionnalités complètes de gestion, d'import/export et de sauvegarde des données.

---

## Fonctionnalités principales
- Gestion des professeurs, groupes, salles de classe et cours  
- Ajout, suppression et modification des entités  
- Sérialisation/désérialisation des données (sauvegarde/chargement)  
- Import/export CSV des différentes entités  
- Interface graphique avec **Qt** (ou autre bibliothèque GUI selon ton projet)  
- Authentification utilisateur  

---

## Structure du projet
- **model/entity** : Entités principales (`Professor`, `Group`, `Classroom`, `Course`, `ObjectsContainer`)  
- **model/GestionFichiers** : Gestion de la sérialisation et de l’import/export  
- **controller** : Logique métier et gestion des actions utilisateur  
- **view/GUI** : Interface graphique (fenêtres, dialogues, formulaires)  

---

## Lancement de l'application
1. Ouvrez le projet dans votre IDE C++ préféré (Qt Creator, CLion, Visual Studio, Code::Blocks, etc.)  
2. Assurez-vous d’avoir un compilateur **C++17** ou supérieur installé  
3. Compilez et exécutez le fichier principal situé dans `view/GUI/main.cpp`  

---

## Dépendances
- **C++17** ou supérieur  
- Bibliothèques standards C++ (`<vector>`, `<string>`, `<fstream>`, etc.)  
- Bibliothèque GUI (ex : **Qt**, **SFML** ou autre selon votre choix)  

---

## Utilisation
- Naviguez dans l’interface pour gérer les professeurs, groupes, locaux et cours  
- Utilisez les boutons pour importer/exporter les données ou sauvegarder l’état actuel  
- L’accès à certaines fonctionnalités peut nécessiter une authentification  

---

## Auteurs
Nassim et Salah  

---

## Remarques
- Les données sont sauvegardées automatiquement lors de certaines actions  
- En cas de problème, vérifiez les fichiers de sauvegarde générés dans le dossier du projet  
