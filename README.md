OccyStrap [![Build Status](https://travis-ci.org/GoEnder/OccyStrap.png)](https://travis-ci.org/GoEnder/OccyStrap)
===========


What is OccyStrap
-----------

OccyStrap is a piece of Java software that allows a user to link multiple Minecraft servers together, Giving players the ability to teleport and travel from one to the other.  
This makes it perfect for servers looking to distribute the load on their servers or include multiple conflicting gamemodes.  

  
  

History
-----------
OccyStrap is based off of BungeeCord, Originally created by @md_5  
We've created OccyStrap to improve upon BungeeCord and create changes we felt were necessary to make.  

#### Changes  
 - Move Tablist settings to Server block, added the ability for tablist types to change when going from server to server
 - Remove MOTD settings from Listener block
 - Add a "Player Count" setting to allow the motd to display the player count for just that server
  
#### Changes to come 
 - Forge Detection in the API
 - Fix the tablist API
 - Merge some of the long-ignored PR's for BungeeCord (May break some plugins)
  

Installation and Usage
-----------
A guide for BungeeCord installation and usage is [avaliable here](http://www.spigotmc.org/threads/bungeecord.392/)  
It might not be an exact guide due to the changes we have made in OccyStrap, our own guide is coming soon

  
  
Want to help out?
----------
Just submit a pull request and we'll check it out

  
  

How to compile
----------
We use Maven to handle our dependencies.  

Clone this repo using git  
`git submodule update --init`  
`./applyPatches.sh`  
`mvn clean install` 
