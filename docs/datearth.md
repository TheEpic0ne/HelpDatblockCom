# Datearth
_This page is a work in progress. What is currently written may not be accurate._

Datearth is a geopolitical Minecraft server with a real world earth map where towns and nations strive for power with war and diplomacy. The server is on 1.13.2 but compatible with 1.13.2 to the latest version at play.datblock.com. 

![image](_images/gladia.png)

Live map of Gladia at [gladia.datearth.com](https://gladia.datearth.com) and Nova at [nova.datearth.com](https://nova.datearth.com).


## Towns

You can create a new town with `/t new` for $2000. A town can claim territory with `/t claim` for $200 per chunk. Residents are protected from outsiders in the town's territory unless their nation is at war. You can view all town commands with `/t ?`.

## Nations

A nation is a collection of united towns. A nation has a capital town whose mayor is the leader of the nation. You can create a nation with `/n new` for $20000. Being in a nation comes with benefits such as being able to teleport to each town in the nation, making trade and travel easier. You can view all nation commands with `/n ?`.

## War

### Sieging

As a king or general, place a coloured banner in the wilderness close to a town to initiate a siege. Starting a siege will cost the attacking nation $1500. This money will be recovered by the siege winner. 

New towns are immune from sieging for 7 days. A town recently sieged is immune from sieging for the length of the previous siege times 2.5.

#### Score

The town under siege has a score shown in `/t` that will determine the siege winner. The attacking nation requires a positive score to win and the defending town requires a negative score to win. A siege lasts 3 days and a timer is shown in `/t` for the town under siege.

#### Occupying
As an attacker or a defender with a military rank, occupy the wilderness area within 16 blocks of the siege banner to increase or decrease the score by 10 points every 30 seconds occupied. After 15 minutes while remaining in the siege zone, to resume scoring points, the player will need to exit then re-enter the siege zone. All residents in the nation and allies with a military rank can contribute to the score.

#### Killing
As an attacker or a defender with a military rank, kill enemy players within a 100 block radius of the siege banner to increase or decrease the score by 200 points. Allies with a military rank can contribute. All residents in the nation and allies with a military rank can contribute to the score.

#### Military ranks

The military ranks for towns are guard, sheriff, and mayor. The military ranks for nations are soldier, general, and king.

#### Abandon attack
As a king or general, place an all-white banner near the siege-attack-banner to abandon the attack. The attacker can abandon the attack 24 hours after the siege started.

#### Surrender town
As a mayor, place an all-white banner anywhere in the town to surrender. The defender can surrender 24 hours after the siege started.

#### Plunder town
As a king or general, after the siege is won, place a chest in the wilderness close to the town. This will rob the town $100 per plot the sieged town has, transferring it to the plundering nation. If the town does not have enough money it will go into a ruined state, where all perms will be enabled. The ruined state persists for 2 days, after which full deletion of the town occurs.

#### Capturing town
As a king or general, after the siege is won, place a coloured banner in the wilderness close to the town. This action will forcibly add the town to the nation, and will put the town into an 'occupied' state, in which its residents cannot affect siege points in other wars. 

### Commands

View detailed information on any siege affecting the town, using `/t`.

View a list of any sieges the nation is involved in, using `/n`.

#### Town neutrality
As a mayor, declare your town to be neutral using `/t toggle neutral`. A neutral town cannot voluntarily join any nation and is immune to siege-forced-pvp, plunder, and occupation taxes. Attackers can still invade if they manage to defeat the town, but the occupation is in-name-only, with no material benefits provided except to increase nation town count.

It takes 7 days to confirm a town neutrality status change after the mayor toggles neutrality.

#### Town revolt
As a mayor, when a 7 days has passed after an invasion, the town can revolt and be free of the occupying nation. This is done using `/n leave`.

#### Nation deletion
As a king, if your nation gets deleted for any reason, including capture of your last town, you will be refunded 50% of the initial cost of creating the nation. This can be triggered voluntarily using `/n delete`.

### Tips

#### Fortify towns
Walls are important. During sieges they help stop enemies from infiltrating towns and killing residents.

#### Fortify or abandon outposts
Outposts are important. Towns can be besieged anywhere they have claimed territory.  Make provisions to defend valuable outposts, and abandon the rest.

#### Assign military ranks
Find residents who can be trusted to fight for your town or nation, and assign them the ranks of guard or sheriff in the town or soldier or general in the nation.

#### Watch your town bank balance
As a mayor, keep enough money in the bank for sieges. If a town is plundered of all its gold by a siege attacker, the town will be destroyed, entering a ruined state for some time. During this time the town blocks cannot be reclaimed, but all perms will be enabled, after which it will be deleted.

#### Make friends & allies
Diplomacy is critical.  As a mayor, diplomacy can be the difference between your town remaining independant, within a friendly nation, or occupied by an expansionistic empire. As a king, diplomacy can be the difference between your nation succeeding, and its annihilation.

#### You are not entitled to power
As a king, your claim to power will be tested. Defend your nation's towns to prove yourself a true nation leader.

## Economy

### Missions
Complete missions to earn money. You receive a mission each time you vote. When you complete a mission, you will earn $200 as a reward. Missions can be shared with town members or traded.

### Shops
You can sell items without having to be online or buy items without the seller hving to be online with chest shops. Create a chest shop by shift-clicking a chest with the item you'd like to sell and shift-click a chest shop to interact and buy from it. Join a town and nation with many allies for easier trading and larger trading hubs.

### Trade
You can safely trade items, money, and experience points with another player by requesting a trade with /trade. The player you would like to trade with must be within 10 blocks of you.
