# Unity - Android Snake Game - XAMK University Online Course Project
---
## Technology Used :

|<a title="Unity Technologies, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Unity_Technologies_logo.svg"><img width="128" alt="Unity Technologies logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/19/Unity_Technologies_logo.svg/128px-Unity_Technologies_logo.svg.png"></a>| <a title="Microsoft, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Visual_Studio_Code_1.35_icon.svg"><img width="64" alt="Visual Studio Code 1.35 icon" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/64px-Visual_Studio_Code_1.35_icon.svg.png"></a> | <a title="Jason Groce, Public domain, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:C_Sharp_wordmark.svg"><img width="64" alt="C Sharp wordmark" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/C_Sharp_wordmark.svg/64px-C_Sharp_wordmark.svg.png"></a> |<a title="Wolthera van Hövell tot Westerflier and Timothée Giet, CC BY-SA 4.0 &lt;https://creativecommons.org/licenses/by-sa/4.0&gt;, via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File:Calligrakrita-base.svg"><img width="64" alt="Calligrakrita-base" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Calligrakrita-base.svg/64px-Calligrakrita-base.svg.png"></a>|
|-|-|-|-|

- [**Unity**](https://unity.com/fr) : Game Engine used for this project
- [**Visual Studio Code**](https://code.visualstudio.com/) : The Integrated Development Environment (IDE) used to write all the code for these project
- [**C# (CSharp)**](https://fr.wikipedia.org/wiki/C_Sharp#:~:text=C%23%20est%20un%20langage%20de,ou%20des%20bibliothèques%20de%20classes.) : Language used for all the scrips files.
- [**Krita**](https://krita.org/fr/) : The raster graphic used to for the Game Desgin
---
## Introduction : 

This project is a simple Interactive Combat Card Game that was one of the assignments I had to deliver during the Free Online Course ["INTRODUCTION TO VIDEO GAMES CREATION"](https://cambridge-academy-of-gaming-and-innovation.teachable.com/p/introduction-to-video-games-creation) proposed by ["XAMK South-Eastern Finland University of Applied Sciences"](https://www.xamk.fi/en/frontpage/) (35 ECTS).
With this project, I was able to discover the basics of Unity Engine / C#, and thus develop my first mobile application.

---
## How to Play : 

The game mechanics are really simple: your character "Merlin" has his avatar displayed the left and the enemy on the right side of the screen. Both have their  **HP**  displayed on the top left corner of the avatar card. The "Mana Points" required to use all the "action cards" (offensive or passive cards) are displayed next to each character, with a total of 5  **MP**  maximum for each of them. This  **MP**  can be earned every turn (+1 per round) by killing the NPC (+1).

As for the card system, every card is described by a short text at the bottom of the card. The  **MP**  required to use it is displayed at the top left corner in ${\textsf{\color{green}green}}$. On the top right corner of the card, the Action Points are displayed in ${\textsf{\color{red}red}}$. The `AP` are basically the damage given to the enemy if it's an offensive card (${\textsf{\color{}red cards}}$), or the  **HP**  given if it's a passive card (${\textsf{\color{green}green cards}}$), except for the mirror which has 1 displayed by default but doesn't actually heal 1  **HP** .

You have the possibility of burning cards from your deck if they don't suit you. Finally, for the rest of the UI, the total "Demons Killed" and your total "score" are displayed on the top left corner of the screen. To know whose turn it is, it's displayed right next to the score. Finally, you have a `Quit` button at the top right corner of the screen.

The objective of the game is basically killing as many "Demons" as possible to achieve the best score. There is no technical ending. 

---
## Gameplay Images : 

![Screenshot (34)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/ae19a423-728c-4f1c-ac4f-267d43f54aed)|![Screenshot (36)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/d2e2a6b5-d669-4fef-a0b4-03097027f92c)|![Screenshot (35)](https://github.com/Ralh19/Merlin-s-Demon-War/assets/145393792/3f8cee92-8122-42c0-945a-78ab943af05d)|
|-|-|-|










