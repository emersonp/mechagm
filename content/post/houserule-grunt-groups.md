---
title: "Houserule: Grunt Groups"
date: 2019-05-23T14:13:15-07:00
draft: true
image: "img/grunt_groups_header.png"
thumbnail: "img/grunt_groups_tn.png"
credit: "http://wallpapercraze.com/images/wallpapers/Fear%20the%20Fiddler%5b2%5d-441850.jpeg"
---

4E encounter design was something else entirely. And I mean that in the best way. It did a lot of cool things that were somewhat novel for the time (and very novel for D&D), and its DNA is very evident in Lancer.

The notion of Minions (4E) or Grunts (Lancer) is one of my favorite additions provided by 4E. There are issues, though. As noted by [The Angry GM](https://theangrygm.com) in their post [More Grist For The Mill: Minion Groups in D&D 5E](https://theangrygm.com/more-grist-for-the-mill-minion-groups-in-dd-5e/), Minions really break the action economy.

Even moreso in Lancer, where the greater number of adversaries with ranged abilities means you're always in range of a half dozen Grunts ready to murder you. While they're quick and easy to kill, if you don't do so quickly, you're in a world of hurt. And the action economy gets real funky.

In Lancer, a perfectly^[I mean, not really.] balanced encounteris 4 players and 16 Grunts. However, if the players aren't able to cut that number down from 16 quickly, they're in for a world of hurt. Grunts do all the damage regular adversaries do, and have access to all the abilities. 8 Snipers and 8 Witches, even if they're Grunts, can get very messy very quickly.

### The Angry GM's Solution

One possible solution? The Angry GM's Minion Groups house rule. The tl,dr for those unwilling to click through^[Shame on you.] is this:

1. Minions should have the same number of hit points (in total) as a regular enemy.
1. Minions should have the same number of actions (in total) as a regular enemy.
1. Minions should have the same amount of movement (in total) as a regular enemy.
1. Minion status effects should be tracked separately.


The more I think about this, the more I like the idea of porting this house rule over to Lancer. #3 makes me a little concerned, given how important cover and flanking is in Lancer. I might end up changing the house rule such that a given group has a total move equal to ```(Regular Minion Move) + 3```, but no given Grunt within the group can move more than ```Regular Minion Move```.

So I present: Grunt Squads.

### Grunts Squads

A Grunt Squad is a template for NPC mechs. 4 Mechs collectively form a Grunt Squad, and one Grunt Squad is a proper encounter for 1 PC Mech.

All Grunt Squads get the following features added to their base NPC type:  

* **Cheap:** Each Grunt in the Grunt Squad has 1/4 the HP of its base type (rounded up), and cannot gain more. Grunts don’t take damage if they pass a successful save (such as on certain area of effect attacks) but otherwise take damage normally.
* **Weak:** The Grunt only has 1 structure and stress maximum. It has a heat capacity equal to 1/4 the heat of its base type (rounded up).
* **Squad Space:** Each Grunt in a Grunt Squad takes up the same number of spaces as a regular unit of its base type. Each Grunt in a Grunt Squad tracks its own conditions separately.
* **Squad Speed:** Each Grunt Squad gets a Speed equal to that of its base type, split at will amongst the Grunt Units.^[A Grunt Squad with a Speed of 5 could move 3 Grunts 1 Space and one Grunt 2 Spaces, or 1 Grunt 5 Spaces anad the rest 0, or any other combination that adds up to 5.] 
* **Squad Turns:** Each Grunt Squad has 1 Turn, and may split its actions up amongst its composite members.^[One Grunt could Skirmish, and nother take a Quick Tech Action, or one Grunt could Barrage, or two different Grunts in a Squad could each Skirmish.] The Grunt Squad as a whole may duplicate actions, but no Grunt in the Grunt Squad may do so. The Grunt Squad as a whole gets 1 Reaction per turn, and any Grunt may take the Reaction.^[If the Reaction is triggered by circumstances, the Grunt must be part of those circumstances. If an opponent triggers Overwatch against Grunt A, Grunt B on the other side of the map may not attack an enemy within Threat range.]
* **Exclusive templates:** The Grunt can't take the Veteran, Squad, Elite, or Ultra templates.

### Example Grunt Squads

---

#### Harrison Armory Sherman MkI

| HP | Evade | E-D | Heat | H | A | S | E | Armor | Spd | Sense | Save | Size |
|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
| 3 | 8 | 8 | 2 | +1 | +0 | +0 | +1 | 2 | 4 | 10 | 10 | 1 |

_Grunt Squad, Mech, Tier 1_  

**Thermal Lance**  
Heavy Cannon  
4 heat (self)  
+1 vs evasion with +1 Accuracy  
Range 8  
6 energy damage

**Focus Down**  
Trait  
If the Sherman MkI hits a character with the Thermal Lance that it already hit with the Thermal Lance in the previous turn, that character also takes burn 5.

**Cooling Module**  
System  
If the Sherman MkI does not move (even involuntarily) between the end of its turn and start of its next  turn, it reduces its heat to 0 at the start of its turn.

**Ablative Shielding**   
System  
The Sherman MkI has resistance to energy damage.

---

#### Ursa Major GATEKEEPER, Refurbished

| HP | Evade | E-D | Heat | H | A | S | E | Armor | Spd | Sense | Save | Size |
|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
| 4 | 8 | 8 | 2 | -1 | +2 | +2 | -1 | 0 | 5 | 15 | 11 | 1 |

_Grunt Squad, Mech, Tier 1_

**LMG**  
Main Cannon  
Reliable 2 
Range 10  
+2 vs evasion  
4 kinetic damage  

**Suppress**  
Trait, Quick Action  
One target in range 10 and line of sight of the Gatekeeper is impaired. If it starts any movement, the Gatekeeper can attack it once with any weapon as a reaction, but this effect ends after the Gatekeeper attacks, hit or miss. The target can also immediately end this effect by damaging the Gatekeeper. It also ends if the Gatekeeper loses line of sight to its target, if the Gatekeeper is stunned, jammed, or destroyed, if the Gatekeeper chooses a new target, or ends this effect as a free action.

**Superior Sentinel**  
Trait  
The Gatekeeper has +1 accuracy on all reaction fire (overwatch, etc).  

---

### Implications

The most obvious implication is weapons that do tiny damage. For example, the Pegasus's Ushabti Omnigun becomes significantly less powerful when it can't one-shot Grunts. This is a natural side-effect of the Grunt Squads being tougher; however, there's a difference between doing a little damage and something that clearly targets Grunts. I suspect upping the Ushabti Omnigun to 1d3 AP damage wouldn't be unreasonable in light of the Grunt Squad houserule. Other weapons as well, though I'm not finding any off the top of my head.

Area control becomes a little less effective against Grunt Squads, but since Grunt Squads can only make one turn per round, player character mechs can afford a round or three to kill them.

I'm sure there are more, but I felt like writing out a starting draft would be worth a conversation. Some serious playtesting would be needed to evaluate such a significant change.