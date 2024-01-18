# Unity - Merlin's Demon War - Jeu de cartes Interactif - XAMK University Online Course Project

---

## Langues README :

[![EN](https://img.shields.io/badge/lang-EN-red.svg)](https://github.com/Ralh19/Merlin-s-Demon-War/blob/main/README.md)

---

## Technologies Utiliées :

|<a title="Unity Technologies, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Unity_Technologies_logo.svg"><img width="128" alt="Unity Technologies logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Unity_Technologies_logo.svg/128px-Unity_Technologies_logo.svg.png"></a>| <a title="Microsoft, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Visual_Studio_Code_1.35_icon.svg"><img width="64" alt="Visual Studio Code 1.35 icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/64px-Visual_Studio_Code_1.35_icon.svg.png"></a> | <a title="Jason Groce, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:C_Sharp_wordmark.svg"><img width="64" alt="C Sharp wordmark" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/C_Sharp_wordmark.svg/64px-C_Sharp_wordmark.svg.png"></a> |<a title="Wolthera van Hövell tot Westerflier and Timothée Giet, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Calligrakrita-base.svg"><img width="64" alt="Calligrakrita-base" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Calligrakrita-base.svg/64px-Calligrakrita-base.svg.png"></a>|
|-|-|-|-|

- [**Unity**](https://unity.com/fr) : Le moteur de jeu utilisé pour ce projet
- [**Visual Studio Code**](https://code.visualstudio.com/) : L'environnement de développement intégré (IDE) utilisé pour saisir les scripts du projet
- [**C# (CSharp)**](https://fr.wikipedia.org/wiki/C_Sharp#:~:text=C%23%20est%20un%20langage%20de,ou%20des%20bibliothèques%20de%20classes.) : Langage utilisé dans tous les fichiers scripts du projet
- [**Krita**](https://krita.org/fr/) : L'outil d'édition et retouches d'images matricielles utilisé pour le Game Design  

---

## Introduction : 

Ce projet est un simple jeu de combat de cartes interactif créer à partir du moteur de jeu Unity. Il s'agit de l'un des devoirs que j'ai dû rendre lors de ma formation en ligne "INTRODUCTION TO VIDEO GAMES CREATION" proposée par "XAMK South-Eastern Finland University of Applied Sciences" (35 ECTS). Ce projet m'a permis de découvrir les bases du moteur de jeux Unity ainsi que du langage C#.

---

## Comment Jouer : 

Le mécaniques du jeu sont vraiment simple : votre personnage "Merlin", a son avatar affiché à gauche et l'ennemi à droite de l'écran. Les deux ont leurs HP affichés en haut à gauche de leurs carte d'avatar. Les "Points de Mana" (MP) nécessaires pour utiliser toutes les "cartes d'action" (cartes offensives ou passives) sont affichés à côté de chaque personnage, avec un maximum de 5 MP pour chacun d'eux. Ces MP peuvent être gagnés à chaque tour (+1 par tour) ou en tuant le PNJ (+1).

En ce qui concerne le système de cartes, chacune d'elles sont décrite par un court texte au niveau de leurs parties inférieurs. Les MP nécessaires pour les utiliser sont affichés en haut à gauche en ${\textsf{\color{green}vert}}$. En haut à droite de la carte, les" Points d'Action" (AP) sont affichés en ${\textsf{\color{red}rouge}}$. Les AP sont essentiellement les dégâts infligés à l'ennemi s'il s'agit d'une carte offensive (${\textsf{\color{}cartes rouges}}$), ou les HP donnés s'il s'agit d'une carte passive (${\textsf{\color{green}cartes vertes}}$), à l'exception de la carte miroir qui affiche 1 par défaut mais qui ne soigne effectivement pas 1 HP.

Vous avez la possibilité de brûler des cartes de votre deck si elles ne vous conviennent pas. Enfin, pour le reste de la GUI, le total des "Démons tués" ainsi que votre "score" total sont affichés en haut à gauche de l'écran. Pour savoir à qui est le tour, c'est affiché juste à côté du score. Enfin, vous avez un bouton Quit en haut à droite de l'écran.

L'objectif de ce jeu est globalement de tué un maximum de "Démons" pour avoir le meilleur score.   

---

## Images du Gameplay : 

![Screenshot (34)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/ae19a423-728c-4f1c-ac4f-267d43f54aed)|![Screenshot (36)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/d2e2a6b5-d669-4fef-a0b4-03097027f92c)|![Screenshot (35)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/3f8cee92-8122-42c0-945a-78ab943af05d)|
|-|-|-|










