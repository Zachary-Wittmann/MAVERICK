# MAVERICK
Finalized Build of MAVERICK, a game created by my team "Atlas Development" for the 2024 Borderlands Glitch Game Jam. Won *Most Technical* Award and 4th Place Overall. 

<p align="center">
<img src="https://github.com/Azaze7/MAVERICK/blob/main/ReadMeAssets/Maverick_TitleScreen.png" > 
</p>

## 🔎 Table of Contents.

1. What is MAVERICK?
* What Design Decisions did we make?
2. Team Composition [Atlas Development]
3. What Files are Enclosed Here?
4. Video Demonstration.
5. SteamOS Integration.
6. The Cutting Room Floor.
7. Closing Thoughts.

##  What is Maverick? 

* Powershell-Empire was an open-source post-exploitation agent that ran through Windows Powershell.
* It allowed for a user to generate attack scripts for use against other Windows machines, MacOS, or Linux subsystems.
* It is not offically maintained as of August of 2019, but a fork was used as a base for the creation of this cybersecurity excercise.

## 🎏 Team Composition [Atlas Development]

**This Project was completed with the assistance of *four* group members!**

* Awarded [*4th Place Overall*] & [*Most Technical Award*].

Special Thanks to All Team Members!

[William Dunlap](https://github.com/unit098 "William's Github") - *Code Lead*: Major Game Logic, Level Loading, Enemy Behaviors, Smoke Trail System, and Bullet System.

[Gilbert I. Guzman](https://github.com/Azaze7 "Gilbert's Github") - *Team Coordinator*: Main Menu System, Game Logos/Emblems, Powerup Design, Code Assistance, SteamOS Support/Artwork, Communicated with Staff.

[Dante Lopez](https://github.com/dragons6612 "Dante's Github") - *Art Support*: Assisted In Creation of all Assets and Consulted on Jet Design/Pixel Art.

[Jesus Torres]() - *Composing lead*: Composed All Music, Ending Screen, and Main Playtester.

[Zachary Whittman](https://github.com/Zachary-Wittmann "Zachary's Github") - *Art Lead*: Requested Assets from Members, Code Assistance, Background Creation and Effects, and Powerup Design. 

<p align="center">
<img src="https://github.com/Azaze7/MAVERICK/blob/main/ReadMeAssets/Atlas_Development_Team_Photo.jpg" height="375px"> 
</p>

## 🗂️ What Files are Enclosed Here?

| Filename | Type | Description | 
| --------------- | --------------- | --------------- |
| DemoPresentation_Software... | .pptx | PowerPoint used during live demo. |
| InfoPresentation_Software... | .pptx | PowerPoint used to inform audience about PowerShell-Empire. |
| Poster_Software... | .pptx | PowerPoint that contains a single slide "poster" about PowerShell-Empire. |
| Exercise_Software... | .docx | Word Document that contains instructions on how to use PowerShell-Empire, in the same format used in CS4177. |
| Final_Powershell_Command_Encoded_Base64 | .ps1 | Script used in Windows PowerShell. It contains instructions to take control of a Windows 7 Professional Virtual Machine. |
| Powershell_Empire_Screenshot | .png | Sample Screenshot of Kali Linux & Windows 7 Professional. Used for this README. |

## 🎞️ Video Demonstration.

* A video demonstrating a full run of the one level we completed for our vertical slice was recorded by myself for this project.
* Since it is too big to upload here, it can be found at this link:
  * https://www.youtube.com/watch?v=DJutJYl7XlY 

## 🕹️ SteamOS Integration.

* Since Maverick was made playable on both standard computers and the Steam Deck, artwork was created so that it wouldn't look out of place next to other video games.

<p align="center">
<img src="https://github.com/Azaze7/MAVERICK/blob/main/SteamGridAssets/Maverick_SteamOS_Demonstration.gif" height="375px"> 
</p>

* It is a great source of pride that my team's GameJam Project is able to sit next to games that were part of both our childhood and adulthood.
* If you would like to use these artworks for your copy of MAVERICK, please look at the [SteamGridAssets](https://github.com/Azaze7/MAVERICK/tree/main/SteamGridAssets "Steam Grid Artwork") folder. :)

## The Cutting Room Floor.

* Due to the strict timing of the Game Jam, we were unable to fully complete our original vision of MAVERICK.

### Second Level & "Realistic" Artstyle.
* The original intention was for the green line level to act as a tutorial, teaching the player how the game worked since it was a "simulation".
* This tutorial took inspiration from military radar equiptment and games like Atari® BattleZone, which used simple lines and vectors for their visuals.
* After the first level was completed, a secondary level was to be loaded in with a more "realistic" artstyle and harder enemies. This level was to have fully animated water and sandy beaches, along with an additional, already completed but unused song.

* Below are some of the additional sprites we had created for it. Keep in mind, in our code every single sprite had the same hitbox regardless if it was in the tutorial or real version of the level.
* (Every asset we created had a tutorial and realistic version created, though they went unused.)

| | Tutorial | Realistic |
|----------|----------|----------|
| Player Character [F-14 Tomcat] | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/Tutorial_Ship_Player.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/F-14_Tomcat_Player.png" > |
| Enemy (Side-to-side) [MIG-28] | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MIG-28_Tutorial_Ship_Enemy.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MIG-28_Enemy.png" > |
| Enemy (Stationary Missle) [MIG-29] | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MIG-29_Tutorial_Ship_Enemy.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MIG-29_Enemy.png" > |
| Enemy (Divebombers) [YAK-141] | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/YAK-141_Tutorial_Ship_Enemy.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/YAK-141_Enemy.png" > |
| Enemy Missle     | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/Enemy_Missile_Tutorial.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/Enemy_Missile_Real.png" > |

### Powerups.
* It was the team's intention that enemies that were destroyed would periodically drop powerups.
* These powerups were loosely based off the Top Gun© Movie, and included things like a pair of avaitor sunglasses and a volleyball.
* Their sprites and intended functions are shown below.

| | Tutorial | Realistic | Function |
|----------|----------|----------|----------|
| Volleyball | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/Volleyball_Tutorial.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/Volleyball_real.png" > | Summoned an additonal jet that would fly next to yours for double firepower. (Inspired by double ships in NAMCO's Galaga.) |
| Sunglasses | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/sunglasses_Tutorial.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/sunglasses_real.png" > | Created a shield that would be at the front of the player's jet. This shield could be used to block enemy fire for a short while. |
| Maverick Emblem | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MaverickEmblem_Tutorial.png" > | <img src="https://github.com/Azaze7/MAVERICK/blob/main/SpriteComparisonAssets/MaverickEmblem_Real.png" > | Made all shots fired by the player into missles for a short while. (Design based powerups in Konami's Contra.) |

## Closing Thoughts.

