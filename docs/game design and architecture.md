# Interstice: Fall of Atlas

Game Design and Architecture

Copyright (c) 2020 Dash Bang Splat Games (Travis Chase), all rights reserved.

# Game Engineering 

## Criteria

- High speed
- Low memory
- No spiking in resources
- Scalability - O(n) expected
- Believabilty
- Control
- Low cost development

# Game Structure (Description and Diagrams)

## User Interface

### Main Menu

There are three states for the main menu depending on if it is the first time the game is played (no saved data), has saved data but no game completion or has saved data and has completed the game at least once.

#### First time played (no saved data)

<img src="images/main_menu_wireframe.png" width="400px" height="300px">

#### Has saved data but no game completion

<img src="images/main_menu_after_starting_to_play_wireframe.png" width="400px" height="300px">

#### Has saved data and has completed the game at least once 

<img src="images/main_menu_after_first_completion_wireframe.png" width="400px" height="300px">

### In Game UI

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

<img src="images/game_ui_wireframe.png" width="400px" height="300px">

### In Game Menu Overlay

There is an in game menu that is available for display as well as an overlay. Allowing for in game menu optons such as *Resume*, *Options*, *Statistics* and *Quit*

<img src="images/in_game_menu_wireframe.png" width="400px" height="300px">

## Event Handling

### Main Menu

The Main Menu will support both mouse pointer and keyboard directional interactions. 

Keyboard: 

- Pressing up/down arrows or w/s keys will allow highlighting of the selected option. 
- Pressing enter on the highlighted option will perform the menu item action.

Mouse:

- Hovering over an item will highlight the option.
- Left clicking on the highlighted option will perform the menu item action.

#### Menu Item Actions

*New Story* - This will allow the player to reset the story back to the beginning state. There is not intent to allow saved game sessions at this time, except the current save, so this will overwrite existing story progress. Players will still keep all inventory obtained thus far into the new game.

*Begin Story* - This will initialize a new game taking the player into the tutorial level and beginning of the story.

*Continue Story* - This will bring the player to restore the current game. 

*Sandbox Mode* - This will bring the player to an open exploration version of the game maps.

*Options* - This will provide basic game options. For now the only intended options are changing the keyboard mapping of keys from their defaults.

*Statistics* - This will display a screen showing all statistics monitored by the game. Such as number of deaths, number of times game story has been completed, fasted time completion for each story level, number of enemies destroyed, number of time each weapon / utility were used, amount of time in each armor chassis.

### In Game

## Data Engines

### Overal Game Data

### Per Stage Game Data

## In Game Dynamic Systems (collisions, physics)

## In Game Logic Engine

## Graphics Engine

## Sound Engine

## Music System

## Control Abstraction Layer (keyboard / mouse)

## Game configuration system (options)

## Help System

# Game Loop Sequences (Description and Diagrams)

## User Interface

### Main Menu

### In Game UI

### In Game Menu Overlay

## Event Handling

### Main Menu

### In Game

## Data Engines

### Overal Game Data

### Per Stage Game Data

## In Game Dynamic Systems (collisions, physics)

## In Game Logic Engine

## Graphics Engine

## Sound Engine

## Music System

## Control Abstraction Layer (keyboard / mouse)

## Game configuration system (options)

## Help System