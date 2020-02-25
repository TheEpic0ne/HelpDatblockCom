# Datearth

Datearth is a geopolitical Minecraft server with a 1:1000 earth map where towns and nations strive for power with war and diplomacy. The server is on 1.13.2 but compatible upwards to the latest Minecraft version. 

![image](_images/gladia.png)

Live map of Gladia at [gladia.datearth.com](https://gladia.datearth.com) and Nova at [nova.datearth.com](https://nova.datearth.com).


## Towns

You can create a new town with `/t new` for $2000. A town can claim territory with `/t claim` for $200 per chunk. Residents are protected from outsiders in the town's territory unless their nation is at war. You can view all town commands with `/t ?`.

## Nations

A nation is a collection of united towns. A nation has a capital town whose mayor is the leader of the nation. You can create a nation with `/n new` for $20000. Being in a nation comes with benefits such as being able to teleport to each town in the nation, making trade and travel easier. You can view all nation commands with `/n ?`.

## War

### Sieging

As a king or general, place a coloured banner in the wilderness close to a town to initiate a siege. Starting a siege will cost the attacking nation $50 per town plot the defending town has. This money will be recovered by the siege winner. 

New towns are immune from sieging for 7 days. A town recently sieged is immune from sieging for the length of the previous siege times 3.

A nation can have a maximum of 3 active sieges at once.

#### Score

The town under siege has a score shown in `/t` that will determine the siege winner. The attacking nation requires a positive score to win and the defending town requires a negative score to win. A siege lasts 3 days and a timer is shown in `/t` for the town under siege.

#### Occupying
As an attacker or a defender with a military rank, occupy the wilderness area within 16 blocks of the siege banner to increase or decrease the score by 5 points every 20 seconds occupied. Up to 3 players per side can score timed siege points at once. After 10 minutes while remaining in the siege zone, to resume scoring points, the player will need to exit then re-enter the siege zone. All residents in the nation and allies with a military rank can contribute to the score. 

#### Killing
As an attacker or a defender with a military rank, kill enemy players within a 150 block radius of the siege banner to increase or decrease the score by 200 points. Allies with a military rank can contribute. All residents in the nation and allies with a military rank can contribute to the score.

#### Military ranks

The military ranks for towns are guard, sheriff, and mayor. The military ranks for nations are soldier, general, and king.

*Notice!* Changing ranks or ally relations while residents in your town, nation, or allied nation are in the siege zone, will penalize your town or nation in points in the siege.

#### Abandon attack
As a king or general, place an all-white banner near the siege-attack-banner to abandon the attack. The attacker can abandon the attack 12 hours after the siege started.

#### Surrender town
As a mayor, place an all-white banner anywhere in the town to surrender. The defender can surrender 12 hours after the siege started.

#### Plunder town
As a king or general, after the siege is won, place a chest in the wilderness close to the town. This will rob the town $50 per plot the sieged town has, transferring it to the plundering nation. If the town does not have enough money it will fall.

#### Capturing town
As a king or general, after the siege is won, place a coloured banner in the wilderness close to the town. This action will forcibly add the town to the nation, and will put the town into an 'occupied' state, in which its residents cannot affect siege points in other wars. 

When the capital town of a nation is captured, the most populated town in that nation becomes the new capital.

*Notice!* Towns in a nation must have enough money in their town bank to pay nation taxes, else their town will fall to ruins. You can view your nation's tax rate with `/n`.

### Commands

View detailed information on any siege affecting the town, using `/t`.

View a list of any sieges the nation is involved in, using `/n`.

#### Ruined Towns
When a town is deleted or falls, the town enters a ruined state for 48 hours, whereafter the town is deleted. Any player can place and break blocks in a ruined town while the town claims remain. After 12 hours of the town being in a ruined state, any player can reclaim the town with `/t reclaim`. If no one reclaims the town after 48 hours the town and its claims will be deleted.

*Notice!* Remember to follow the rules written below regarding the looting of towns in a ruined state.

#### Town neutrality
As a mayor, declare your town to be neutral using `/t toggle neutral`. A neutral town cannot voluntarily join any nation and is immune to forced PvP, plunder and occupation taxes. Attackers can still invade if they manage to defeat the town, but the occupation is in-name-only, with no material benefits provided except to increase nation town count.

It takes 4 days to confirm a town neutrality status change after the mayor toggles neutrality.

#### Town revolt
As a mayor, when a 7 days has passed after an invasion, the town can revolt and be free of the occupying nation. This is done using `/n leave`.

#### Nation deletion
As a king, if your nation gets deleted for any reason, including capture of your last town, you will be refunded 50% of the initial cost of creating the nation. This can be triggered voluntarily using `/n delete`.

### Rules

#### Neutral is neutral
Neutral towns may not participate in any wars such as helping a nation with a siege. Residents in a neutral town participating in a war will be punished and the town may lose its right to neutrality. This also applies to residents that are not an official ally with the nations at war. If you are not related to a war, you should not approach the siege zone.

#### Looting towns
If a town enters a ruined state, the town may be looted of containers and valuable blocks. Valuable blocks are ore and mineral blocks, enchanting tables, bookshelves, beacons, conduits, ender chests, anvils, and brewing stands. Blocks can be destroyed in ruined towns, but blocks may only be broken to get through barriers such as doors or walls to valuables. Any excessive or unnecessary breaking will be punished. The ruined state lasts 24 hours whereafter the town is fully deleted. The first to claim the town again is the rightful owner of the town.

#### Defences in wilderness
The attacking nation is allowed to construct small walls at the siege zone to protect themselves from ranged attacks. It is not allowed to build any construction that hinders reaching the siege zone or players in the zone.

#### Fair wars
Any use of bugs or unintended behavior to gain an advantage in a siege will be punished. Use common sense or ask staff if unsure.

### Tips

#### Fortify towns
Walls are important. During sieges they help stop enemies from infiltrating towns and killing residents.

#### Fortify or abandon outposts
Outposts are important. Towns can be besieged anywhere they have claimed territory.  Make provisions to defend valuable outposts, and abandon the rest.

#### Assign military ranks
Find residents who can be trusted to fight for your town or nation, and assign them the ranks of guard or sheriff in the town or soldier or general in the nation.

#### Watch your town bank balance
As a mayor, keep enough money in the bank for sieges and nation taxes. If a town is plundered of all its money by a siege attacker or can't afford nation taxes, the town will be destroyed, entering a ruined state for some time. During this time the town blocks cannot be reclaimed, after which the town will be deleted. 

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

## Warfare

### Ancient
The world, Gladia, uses ancient warfare. With ancient warfare, the vanilla combat system has been modified to replicate the 1.8 combat mechanics, before the 1.9 combat update. This means that there is 1.8 attack cooldown, no sword sweep, knockback for fishing rods and projectiles such as snowballs, 1.8 health regeneration, 1.8 armor durability. Shields have been kept, creating a unique combination of the old and new Minecraft combat systems. Note that the damage values of weapons displayed on your client are inaccurate, as they have been changed server-side to the 1.8 damage values, meaning that the sword deals the most amount of damage. Invisibility potion has been disabled and strength potion has been nerfed.

### Modern
The world, Nova, uses modern warfare. With modern warfare, the vanilla combat system is unchanged except enchantments, using post-1.9 combat, but features non-vanilla additions to combat and transportation.

*Notice!* You must have the modern warfare resource pack to view the custom firearm and vehicle models. The resource pack is lightweight and compatible with other resource packs. Upon enabling the resource pack, it may warn that the resource pack is outdated, however, it will still function with no issues.

[Click here to download the resource pack.](https://datearth.com/resourcepack)

[Click here to learn how to install the resource pack.](https://minecraft.gamepedia.com/Tutorials/Loading_a_resource_pack)

#### Firearms
Pistols, rifles, rocket launchers, and more can be bought from the weapon shop with `/weapons`. Right click to shoot, press Q to reload, shift for less recoil, and left click for a special mechanic that some weapons have such as aiming with a scope. Weapons have attributes such as damage, weight, speed, and spread that make them unique. Headshots and shots from behind deal more damage. Some firearms can not be purchased from the weapon shop and can only be found in chests and supply crates.

Protection and thorns enchantment has been disabled and sharpness enchantment is limited to level 3. This is to account for firearms in combat and keep the damage caused by firearms realistic and similar to any other shooter game.

#### Vehicles
Jeeps, boats, planes, and helicopters that can be bought from the vehicle shop with `/vehicles`. To control a vehicle, use WASD and space. Once you buy a vehicle, you will keep it forever. You can summon your vehicles from your garage with `/garage`. Shift while in the vehicle to un-summon the vehicle.

#### Nuclear
Make nuclear weapons and reactors with uranium from the moon. Obtain uranium ore by mining endstone on the moon. Smelt uranium ore in a furnace to turn it into enriched uranium. Enriched uranium is used to make fuel rods for reactors and nuclear weapons.

[Click here to view the recipes for nuclear.](https://imgur.com/a/RTx5FcL)

##### Nuclear Reactors
You can create a nuclear reactor to fuel a furnace. To create a nuclear reactor, you need to place 1 reactor core, 3 cauldrons, 1 hopper, and then as last block 1 furnace. You much place the furnace as last block. To use the nuclear reactor, simply place fuel rods in the hopper. One fuel rod will keep the reactor running for 30 minutes. Radioactive nuclear waste will be produced while the reactor is running and will be deposited into the hopper or dropped on the ground if the hopper is full. Nuclear waste will radiate players if they hold it in their inventory or stand near it when its on the ground. Wear hazmat gear to reduce its effect! While the reactor is running it will use up the water in the cauldrons. The reactor will use one cauldron level of water every 60 seconds. If the reactor runs out of water it will meltdown, causing an explosion and radiation.

[Click here to view the blueprint for a nuclear reactor.](https://imgur.com/a/VcN67W9)

##### Nuclear Weapons
There are two nuclear weapons, atomic bomb and hydrogen bomb. Both weapons cause a large explosion on impact and radiate the surrounding area but the hydrogen bomb is more powerful. The atomic bomb has an explosion strength of 30 and causes radiation within a 25 block radius for 2 minutes and the hydrogen bomb has an explosion strength of 75 and causes radiation within a 50 block radius for 5 minutes. For scale, TNT has an explosion strength of 4. The explosions do not cause damage to blocks. To launch a nuclear weapon, click the item while looking in the direction you want the missile to fire and it will explode on impact.

##### Radiation
Your radiation level is displayed in a bar on top of your screen. Radiation causes weakness, nausea and ultimately death at 100 rads. Sources of radiation include: holding nuclear waste, standing near nuclear waste, reactor meltdowns, and nuclear weapons. Your radiation level will slowly decrease as time passes or you can use radiation pills to significantly reduce your radiation level. The amount of radiation a player receives from a radiation source can be reduced by wearing hazmat gear. For each piece of hazmat gear the player is wearing, the amount of rads received is reduced by 25% so if the player is wearing a full hazmat suit they are fully protected from all radiation.

#### Space Travel

##### Mars
It is possible to space warp to the planet, Mars, by entering a nether portal. Mars is in the nether dimension where nether related supplies can be gathered and martians roam here and have a low chance of dropping a nether star or their head which carries special powers.

##### The Moon
It is possible to travel to the Moon by a rocket that you can purchase with `/rocket`. The Moon is in the end dimension where end related supplies can be gathered and alien roam here and have a low chance of dropping end rods or their head which carries special powers. Uranium ore for nuclear can also be mined on the Moon.
