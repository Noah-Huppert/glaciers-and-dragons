# Design Ideas
Brainstorming and future planning.

# Table Of Contents
- [Overview](#overview)
- [User Experience](#user-experience)

# Overview
This is a design document with future plans. Not documentation of what is implemented.

# User Experience
The bot should perform actions which help facilitate a DnD game. This section examines the different responsibilities required of the bot. As well as how they will appear to the end user.

## Keeping The Game Going
Since the game is asynchronous, unlike traditional DnD sessions, some amount of effort must be spent to facilitate the game moving forward.

The events that hold game play up are:

- Asking players what they want to do
- The dungeon master interpreting the player's wishes
- Rolling for properties of character's actions
- Properties of characters being stored
- Effects of actions on players being recorded

These events can be broken up into 3 different categories:

- Communication
  - Asking players what they want to do
  - The dungeon master interpreting the player's wishes
- Calculation
  - Rolling for properties of character's actions
  - Properties of characters being stored
  - Effects of actions on players being recorded
  
The details of each category is as follows.

### Communication
When one or more players have information which other players require the bot can help the flow of communication. Either by asking questions or broadcasting answers. The bot can also direct message people to 

The Discord bot can ask players in the game channel for public information. Or direct message players for private information.

Information being shown in a public channel also operates as broadcasting to other players.

### Calculation
The random aspects of DnD which determine a property of an action. Such as the effectiveness of an attack.

## Help Tell The Story
Although the dungeon master is responsible for ensuring proper play they are also responsible for telling a story and engaging the players.

Storytelling is responsible for conveying the following information:

- Scale and position in the world
- The current state of the different characters
