![Setup Story Teller](https://static.wikia.nocookie.net/whitewolf/images/a/a0/Caine.png/revision/latest/top-crop/width/360/height/360?cb=20190504162356)
# CaineBot

[[README Page]](https://github.com/nfanaropoulos/CaineBot/blob/main/README.md)

# | Documentation - NPC command

-----------------------------------------
  * Register NPC
-----------------------------------------
```C#
/Caine NPC Register <NPC Name> <Clan> <NPC Location> <Image URL> <NPC Areas of Influence> <NPC Notes>
```
* Registering an NPC to the database, doesn't make him visible to the players. In order for players to see the NPC, the Story Teller must publish him first (see below).
* NPC Name: This field is obligatory, it can be a real name or an allias but be carefull, each NPC must have a unique name.
* Clan: This field is obligatory, it rapresents the Clan of the NPC, if the players don't know the clan yet you can choose 'Unknown'.
* NPC Location: This field is obligatory and it rapresents the area where players met this NPC.
* Image URL: This field is obligatory and it is the image the players see when they met the NPC.
* NPC Areas of Influence: This field is optional and it rapresents the areas where the NPC has influence (church, Goverment etc) or the locations where the NPC has influence (Los Angeles, Florence etc) or it can be set to Unknown if the players don't know this information
* NPC Notes: This is an optional field that rapresents small bits of information for the NPC that players or Story Teller feel it's good for having as references. Players and Story teller can add / edit / delete those (See below).

![Register NPC](https://i.ibb.co/ZJT9Jp9/download-6.png)
![Register NPC](https://i.ibb.co/ZWnM7sV/download-7.png)

** Note: This command is available only to Story Tellers.
** Note: You can add multiple Areas of Influence and Notes by seperating each one with the character '|' (without the quotes). For example Church|Athens|Florence .

-----------------------------------------
  * Update NPC
-----------------------------------------
```C#
/Caine NPC Update <NPC Name> <Clan> <Location> <Image URL> <Area of Influence>
```
* NPC Name: This field is obligatory and it's dynamically refresh the list of current available NPCs who are registered to the database.
* Clan: This field is optional (you choose what to change).
* Location: This field is optional (you choose what to change). In case of wrong register entry.
* Image URL: This field is optional (you choose what to change). In case of wrong register entry or in case of Obfuscate or other reasons.
* Area of Influence: This field is optional (you choose what to change). In case of wrong register or new available information to the players.

![Update NPC](https://i.ibb.co/6wt8Fym/download-8.png)
![Update NPC](https://i.ibb.co/Qk8rCQG/download-9.png)

** Note: This command is available only to Story Tellers.

-----------------------------------------
  * Publish NPC
-----------------------------------------
```C#
/Caine NPC Publish <NPC Name> 
```
* NPC Name: This field is obligatory and it's dynamically refresh the list of current available NPCs who are registered to the database.

![Publish NPC](https://i.ibb.co/VMbSHVQ/download-10.png)

** Note: This command is available only to Story Tellers.

-----------------------------------------
  * Show NPC
-----------------------------------------
```C#
/Caine NPC Show <NPC Name> 
```
* NPC Name: This field is required and it's dynamically refresh the list of current available NPCs who are registered to the database.

![Show NPC](https://i.ibb.co/qxk5vgn/download-1.png)

** Note: Using this command will show to the players ONLY the NPCs which have been Published (see the command above). However the Story Teller can use this command to see the npcs who haven't been update yet in his private channel.

-----------------------------------------
  * Search NPC
-----------------------------------------
```C#
/Caine NPC Search <Keyword> 
```
* Keyword: This field is required and it can be either a Clan, Location or Area of Influence.

![Search NPC](https://i.ibb.co/F6rzgQ9/download-2.png)

** Note: Using this command will show to the players ONLY the NPCs which have been Published (see the command above). However the Story Teller can use this command to see the npcs who haven't been update yet in his private channel.

-----------------------------------------
  * ADD Note
-----------------------------------------
```C#
/Caine NPC Add_Note <NPC Name> <Note> 
```
* NPC Name: This field is obligatory and it's dynamically refresh the list of current available NPCs who are registered to the database.
* Notes can be set by either Story Teller or players.

![Add Note](https://i.ibb.co/FVSc129/download-11.png)
![Add Note](https://i.ibb.co/dkJz1nx/download-12.png)

-----------------------------------------
  * Edit Note
-----------------------------------------
```C#
/Caine NPC Edit_Note <NPC Name> <Old_Note> <New_Note> 
```
* NPC Name: This field is required and it's dynamically refresh the list of current available NPCs who are registered to the database.
* Old_Note: This field is required as well and it has to be copied and paste without the name of the player who made it. For example if the note on the NPC profile reads "Fabrizio: Test", you should copy the "Test" only!
* Notes can be edited by the players who made them only. Of course the Story Teller can edit all notes.

![Edit Note](https://i.ibb.co/KKBgxfq/download.png)

Discord Bot for Vampire Tabletop RPG
