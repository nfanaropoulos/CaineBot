![Setup Story Teller](https://static.wikia.nocookie.net/whitewolf/images/a/a0/Caine.png/revision/latest/top-crop/width/360/height/360?cb=20190504162356)
# CaineBot

[[README Page]](https://github.com/nfanaropoulos/CaineBot/blob/main/README.md)

# | Bot Installation

-----------------------------------------
  * Set up Story Teller and his channels
-----------------------------------------
```C#
!AddST <Mentioned User> <Link Channel 1> <Link Channel 2> <Link Channel 3> <Link Channel 4> <Link Channel 5> <Link Channel 6>
```
* Channel 1: This is the hidden to players channel for the Story Teller where he can inspect and review NPC profiles
* Channel 2: This is the public channel where Story Teller introduce NPCs to the players
* Channel 3: This is the hidden to players channel for the Story Teller where he can check the Player Profiles
* Channel 4: This is the hidden to players channel for the Story Teller where he can check the Boons of the players
* Channel 5: This is the hidden to players channel for the Story Teller where he can check the Random Encounters he create
* Channel 6: This is the hidden to players chanenl for the Story Teller where he can roll his dices

**Note : A channel can be set up to be both hidden to players for dice rolls and for hidden to players Random Encounters checks

![Setup Story Teller](https://i.ibb.co/tpr4k3R/download-2.png)

-----------------------------------------
  * Set up Player and his channels
-----------------------------------------
```C#
!AddPlayer <Mentioned User> <Link Channel 1> <Link Channel 2> <Link Channel 3> <Link Channel 4>
```
* Channel 1: This is the hidden to other players channel taged as General channel or lobby
* Channel 2: This is the hidden to other players channel exclusive for the player Boons
* Channel 3: This is the hidden to other players channel exclusive for the player Experience Points
* Channel 4: This is the hidden to other players channel exclusive for the player Dice rolls

**Note : A channel can be set up to be both for Dice rolls and General.

![Setup Campaign Player](https://i.ibb.co/L0FH5hy/download-3.png9)

-----------------------------------------
  * Remove Story Teller
-----------------------------------------
```C#
!RemoveST <Mentioned User> 
```

![Remove Story Teller](https://i.ibb.co/Smc3j3w/download-4.png)

-----------------------------------------
  * Remove Player
-----------------------------------------
```C#
!RemovePlayer <Mentioned User> 
```

![Remove Story Teller](https://i.ibb.co/9VsRV5Y/download-5.png)

Discord Bot for Vampire Tabletop RPG
