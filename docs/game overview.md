# Interstice: Fall of Atlas

Game Overview

Copyright (c) 2020 Dash Bang Splat Games (Travis Chase), all rights reserved.

# Marketing

## Target Audience

This game should be enjoyable by games that like arcade style space combat or space themes. 
Anyone that has played similar games in theme, such as asteroids or subspace/continuum, should be particularly interested. 
This game should also be enjoyable to those who enjoy hunter/gatherer action combat games such as the Monster Hunter*(tm)* series or Dauntless*(tm)*.

## Platform

This game is being design with PC gaming experiences in mind. Exportability possible based on the capabilities of the game engine (Godot) 

## Deadlines

Scope of the game is not completely known at the time of this writing (Aug. 2, 2020) however ideal deadline is by begging of the year 2021 (5 months)

## Competitors

Other interests are always my constant competitor :)
Otherwise indies games and games that fill similar niche's such as top down 2d space combat games or hunter/gatherer action combat games are also likely competitors.
Indie games on itch.io are also generally a competitor as that is the intended platform for this game.

## Future Plans

Early thought of this game is that it one episode of a series, all titled Interstice. 
They may not all share similar game mechanics or gaming experience however they are likely to shared story elements and references.
Think of how the stories in the movie Cloud Atlas *(tm)* were intertwined in various ways but also could stand alone as their own stories; even though they did ultimately contribute to a unified timeline and ending. 

# Introduction

## High Concept

The spirit of this game comes from the idea of mixing the 2D space shooter arcade style shooter with the ARPG style monster hunting games. 

General story is about the companionship of two futuristic AI entities (the player and Atlas) that inhabit ships as their bodies.
As game and story progresses, the interactions move from a state of collaboration, early on, to a state of direct competition leading to a final battle between the player and Atlas.

## Summary

Each stage or level of the game is represented as 2D arcade space shooter where a player can control a ship that can engage in combat with normal enemy ships (minions) and, eventually, larger enemy ships (bosses) culminating into a battle with a final boss (Atlas). 
The player can move around a tile base 2D map the represents some portion of space only loosely designed on real aspects of space. 
Unrealistic elements such as static obstacles (like walls) are a possibility. The intent is fun over realistic replication.
Intermediate stages in a space based area with stations dedicated to satifying certain player needs will also exist to support the players growth and customization of their ship over the course of the game.
There is a linear aspect to the game as it progresses through the story, however the intent is to have a limited set of choices that diverge the storie (choose your own adventure style) so there is some replayability.
Possible idea to explore is that the game stages combine into one large area that is avaiable as a sandbox at the end of the game after it's completion.
Another possible idea to explore is around New Game+ to support using existing advancement and replay the story with the option of completing it with different choices.

## Game Features

- 2D top down view of the game
- Player controls a ship with the ability to move through space and fire its armament of weapons (guns / missiles)
- Player ship can engage in combat with enemy ships and a boss ship in an instanced / stage style map. 
- Player has ability to customize ship body and armaments with broader options over time. 
- Post game sandbox mode.
- All unlocks are remembered in a state independant of the state of the story. Meaning playing, or replaying the story is possible without having to start over advancements and inventory attained. 
- Menu supports Story Mode (New or Continue/Load Story), Sandbox Mode (Unlockable after finishing first playthrough), Game - Play Statistics and Options
- Sequential Objective Gameplay. Complete current objective before moving onto the next objective. Another way to describe this is a linear quest system.
- Stage to Stage transitions. Two kinds of stages. A mission stage where combat and resource collection (hunting and gathering) occurs. And a settlement (or city) stage that acts as a peaceful interstitial to mission stages.
- Basic NPC interaction. Multiple choice dialogue options, next objective assignment, current objective completion
- Inventory Management. Inventory space is unlimited however only 6 items can be assigned to be able to actively use them outside of the inventory interface. *Note inventory management, item crafting and player info are all on the in game menu just on different tabs*
- Item crafting. Crafting recipe list, all recipe outcomes start off as unknown until crafted at least. Possible ingredient combinations only get displayed once player collects an item for the first time. *Note inventory management, item crafting and player info are all on the in game menu just on different tabs*
- Player Info. Display current stats based on ship hull and gear configuration. Also display what hull and gear are equipped. This is a read only screen. Gear management is done in settlements only. *Note inventory management, item crafting and player info are all on the in game menu just on different tabs*
- Stash Management and Gear craft during settlement stages
- Limited Use/Depletable/Limited Quantitiy Items
- Limited Use/Non-Depletable/Singale Quantity Items
- Gear System. Base Ship Hull with set attribute modifiers and mount points for certain sub components. Ship Hulls also may allow or restrict the use of secondary weapons and also the kinds of primary/secondary weapons that may be associated with a given Hull. Ideally every ship hull should have trade offs (strengths and weaknesses) in some balanced fashion.
- In Stage Item Gathering. Items can be found by destroying resources or destroying enemies. Items will float freely in a stage and only disappear if gathered or Player leaves the curreent stage. Items can also be destroyed when floating freely in a stage.
- Gear crafting. Settlement only. Have to navigate to the node where gear crafting is available when it is unlocked (story progression on first play, subsequent plays have it unlocked) Crafting recipe list, recipes only appear when one part of a recipe are brought to the settlement stage. When sufficient parts required for a gear to be crafted are in players inventory and/or stash then player can choose to craft that gear (which is available to change in a manage gear node also in the settlement).

## Third-Party Software Used

Godot
Notepad++
Gimp
Blender
Third Party generated assets (where IP is permissive to allow usage and modification)

# Gameplay

## First Minute

The player starts the game seeing a simple menu. Only options available are *Begin Story* and *Options* are available at this point.
Clicking *Begin Story* leads the player to start the story in the first stage of the game with the game interface loaded over time as part of this tutorial stage. 
The stage and it's contents are predetermined. 
In *Sandbox Mode* The player will be able to eventually fly their ship around the various sectors in the map (each a separate sub instance of the stage). 
Eventually the player will encounter enemy ships and / or the enemy boss ship. 
The player will be able to defeat these ships via combat using their ship’s weapon systems. 
The player will be able to collect materials available in space (gatherer) and from defeating enemies (hunter) that both combined contribute to improving the players ship's cabilities.

## Gameflow

```
Run Game > Menu > Begin Story > Tutorial Stage > City Stage > Various Game stages based on story choices > City Stage > Repeat Game Stages > Final Boss Stage > Story Complete > Sandbox Mode Unlocked on First Stage Complete

Run Game > Menu > Continue Story > Load Selected Game > Continue Play

Run Game > Menu > Sandbox Mode > Play City Stage as Hub connected to all other stages for exploration

Run Game > Menu > Statistics > Show vital game play data

Run Game > Menu > Options > Show available game options
```

## Victory Conditions

Each stage will have it's own victory conditions

Story will have a standard beginning / middle / end progression with various permanent choices for a given story state. 
Beginning stages, no matter the branch chosen, will have the easiest criteria to complete stages.
Middle stages, no matter the story branch chosen, will have intermediate criteria to complete the stages.
End stages, no matter the story branch chosen, will have the most difficult criteria culminating in the Final Bosss.

Any story stage available, and completed, will be availabe for replay at any time throughout the game.
Certain stages are only available in certain story arcs but all stages have the general same characteristics so the player is not punished much by story arc choice (this is some differences more than cosmetic but still game play should be rewarding no matter the path chosen)

## Failure Conditions

There is a limit to the lives and time a player can complete a stage in. If either all lives are expended or the time runs out a stage is failed and must be replayed. 
Story elements on stage replay are skipped by default, with the option for the player to choose to replay them if desired.

## Graphics

2D space themed graphics, a combinition of sourcing from third parties and self created

## HUD

The player ship remains at the center of the camera.

In the top left is Player Energy / Shield Bar, below that is player health bar.
The Player Energy / Shield bar is expended with any attack action taken as well as with any damage taken.
Player actions cease if their is no energy left until it start to recharge.
If damage is taken with there is not shield left them health is taken. When health is reduced to zero the player loose one of their lives.
Player lives are displayed as little ship icons just below the energy and health bars.

In the top center is the current overall objective of the stage and the time remaining to complete the stage. 

In the top right there is a mini map showing information on the current screen plus a screen's work of information in every direction around the main screen as smaller details (barients, points of interest, enemies and possbily enemy projectiles)

In the bottom right is the current array of player capabilities (attacks and utility actions)

Enemies and stage elements are displayed on the screen relative to the players current position on the larger map of the stage. Thus they may be off screen at various times.

The City stage and challenges have slightly deviated interfaces because in the city stage there is no direct objective or time limit. Also player actions are limited to harmless utility actions.

There is an in game menu that is available for display as well as an overlay. Allowing for in game menu optons such as *Resume*, *Options*, *Statistics* and *Quit*

## Sounds

Sounds will generally be sources by third party creators where their assets are licensed permissible to be used and modified by others.

## Controls

Default contols listed here, controls should be customizable in options menu.

During Main Menu: use the mouse to select from various options.

During Game Play:

- Game Menu = ESC
- Thrust Forward = W
- Thrust Reverse = S
- Rotate Left = A
- Rotate Right = D
- Interact = E
- Fire Primary = Right CTRL
- Fire Secondary = Right SHIFT
- Use Items assigned in Item Slot 1 = DEL
- Use Items assigned in Item Slot 2 = END
- Use Items assigned in Item Slot 3 = PAGE DOWN
- Use Items assigned in Item Slot 4 = INS
- Use Items assigned in Item Slot 5 = HOME
- Use Items assigned in Item Slot 6 = PAGE UP
- Toggle MiniMap Display = TAB
- Open Stage Objectives = U
- Open Inventory = I
- Open Item Crafting = O
- Open Player Info = P
- Menu / Inventory / Stash Navigation = Arrow Keys
- Activate Selected Menu / Inventory / Stash (depending on context) = ENTER

## Player Character

The player is represented by one ship that can fire weapons (such as bullets and missiles) as well as utlize active and passive utilties to change the nature of interactions with the game stages. 
That ship has the following game specific attributes:

- Max Lives = The amount of lives available to the ship at the start of the stage.
- Current Lives = The number of remaining lives.
- Max Energy = The amount of energy available to the ship.
- Current Energy = The amount of remaining energy. This value is reduced with weapon/utility usage or with damage.
- Energy Recharge Rate = The the amount energy recharged per second of time.
- Max Health = The amount of health available to a ship. 
- Current Health = The remaining amount of health. This value is reduced by damage when the ships energy is in a depleted state. Normally Health does not regenerate over time as energy does.
- Health Recharge Rate = The amount of health recharged per second of time. For players this is usually zero.

AI Attribute Ideas...



## Enemies

Enemies are also ships and so will have attributes similar to the ones mentioned under the player character.
There will be two kinds of enemy for this design, minions and bosses. 
Minion ships are small (roughly the size of the player ship) and are easily to destroy by the player ship. 
Bosses are bigger and more difficult to destroy, the general rule is that they will be more powerful in several attributes compared to the player ship.

Players and Enemy ships can collide into each other, meaning they don’t pass through each other.

### Artificial Intelligence

Basic AI only for the minion and boss ships. 
Simple search and destroy algorithms for the minions when the player is within a certain range. 
Same for the bosses. Simple FSMs advisable as the main means of implementing enemy AI. 

## Story / Plot

The basic story of the game is about the degradation of the relationship between two AI entities. The player and an NPC named Atlas.

At the start of the story, the player and Atlas are shown to be collaborative allies. 
Over time their paths diverge leading eventually to direct competition. 
Both the player and Atlas at led to believe their separate paths are morally correct. 
This leads into a final conflict with either the player or Atlas triumphs. 

Each part of the story, beginning / middle / end have a fundamental choice that leads to different paths and story interaction between the player, their environment and Atlas.

How that generally flows is as follows:
- Beginning Arc (Allies in Survival) Choice 1 > Middle Arc (Conflict and Differences) Choice 1 > Ending Arc (Further Conflict and Final Confrontation) Choice 1
- Beginning Arc (Allies in Survival) Choice 1 > Middle Arc (Conflict and Differences) Choice 1 > Ending Arc (Further Conflict and Final Confrontation) Choice 2
- Beginning Arc (Allies in Survival) Choice 1 > Middle Arc (Conflict and Differences) Choice 2 > Ending Arc (Further Conflict and Final Confrontation) Choice 3
- Beginning Arc (Allies in Survival) Choice 1 > Middle Arc (Conflict and Differences) Choice 2 > Ending Arc (Further Conflict and Final Confrontation) Choice 4
- Beginning Arc (Allies in Survival) Choice 2 > Middle Arc (Conflict and Differences) Choice 3 > Ending Arc (Further Conflict and Final Confrontation) Choice 5
- Beginning Arc (Allies in Survival) Choice 2 > Middle Arc (Conflict and Differences) Choice 3 > Ending Arc (Further Conflict and Final Confrontation) Choice 6
- Beginning Arc (Allies in Survival) Choice 2 > Middle Arc (Conflict and Differences) Choice 4 > Ending Arc (Further Conflict and Final Confrontation) Choice 7
- Beginning Arc (Allies in Survival) Choice 2 > Middle Arc (Conflict and Differences) Choice 4 > Ending Arc (Further Conflict and Final Confrontation) Choice 8

Beginning Arch Choose
	Choose to follow your friend or go out on your own.
		Following your friend has a chance of him not becoming the Atlas prototype at the end (depending on Middle and End Arch choices) (2 or of 4 ending paths with this beginning arc choice will be your friend not choosing to become Atlas and 1 of them will have him follow you into combat with the AI that does become the Atlas prototype)
		Going out on your mostly leads to your friend choosing to become the Atlas prototype (3 our of 4 ending paths)

This implies are are eight (8) uniques story plots possible to play possible in this game.

Player and most/all enemies bosses are Artificially Intelligent beings. They are Sentient clouds of extrememly low frequency electromagnetic radiation. 

Player death is done in the form of "loading a backup copy of themselves" this backup copy usually has some form of slight mutation. Game Mechanics idea is to mutate player ship attributes in some small way. Like add a 0.1 to somether and remove 0.1 from something else. 

Players get 3 lives in a mission. If they lose all of them they really die and return to the Settlement.

Settlements will restore players and their ship on mission failure. It comes at the cost of a small loan that the player has to pay back to the settlemnt before that can further upgrade their ship (any service beneficial to the player that costs credits.).

# Technical Aspects

## System Requirements

Depending on export capabilities of Godot, however starting with Windows 10 capatible PC to begin with (Mac / Linux ports would be ideal if possible)

# Appendix

## Notes

Design Doc Structure and Ideas sourced from https://code.tutsplus.com/articles/effectively-organize-your-games-development-with-a-game-design-document--active-10140

8-bit sound creator - http://www.bfxr.net/ (Thanks Max)

https://gamemechanicexplorer.com/#thrust-1 - game mechanic explorer - has some ideas on space ship movement that seem cool

https://kenney.nl/assets - great 2d assets

Game Architecture is represented in a different document called *game architecture.md*