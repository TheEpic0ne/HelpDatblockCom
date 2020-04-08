# Datearth

Geopolitcs on a world map with nations, diplomacy, and war! There are three worlds: [Gladia](https://gladia.datearth.com), the ancient warfare world, [Nova](https://nova.datearth.com), the modern warfare world, and [Elysia](https://elysia.datearth.com), the peaceful world without war.

![image](_images/gladia.png)

## Towns

Create a town with `/t new` for $2000. A town can claim territory with `/t claim` for $200 per chunk. Residents are protected from outsiders in the town's territory unless they are at war. You can view all town commands with `/t ?`.

## Nations

A nation is a collection of united towns. A nation has a capital town whose mayor is the leader of the nation. Create a nation with `/n new` for $20000. Being in a nation comes with benefits such as being able to teleport to each town in the nation, making trade and travel easier. You can view all nation commands with `/n ?`.

## War

### Sieging

As a king or general, place a coloured banner in the wilderness close to a town to initiate a siege. Starting a siege will cost the attacking nation $50 per town plot the defending town has. This money will be recovered by the siege winner. While under siege, the town cannot recruit new residents or claim new land.

New towns are immune from sieging for 7 days. A town recently sieged is immune from sieging for the length of the previous siege times 3.

A nation can have a maximum of 3 active sieges at once.

#### Score

The town under siege has a score shown in `/t` that will determine the siege winner. The attacking nation requires a positive score to win and the defending town requires a negative score to win. A siege lasts 3 days and a timer is shown in `/t` for the town under siege.

#### Banner control
As an military-ranked attacked or defender, gain banner control for your side, by remaining alive and close to the the siege banner for 10 minutes. Once your side has banner control, siege points will be awarded automatically every 20 seconds

#### Killing
As an attacker or a defender with a military rank, kill enemy players within a 150 block radius of the siege banner to increase or decrease the score by 500 points. Allies with a military rank can contribute. All residents in the nation and allies with a military rank can contribute to the score.

#### Tactical Visibility

Kings and Generals are always visible on the dynmap. Any player pillaging at the banner is always visible on the map. Other military-ranked players can simply equip a compass or shield in their off-hand, to disappear from the map. Other players remain visible on the map.

#### Military ranks

The military ranks for towns are guard, sheriff, and mayor. The military ranks for nations are soldier, captain, general, and king. 

Military ranked nation players of captain rank and above gain a leadership aura. If a military leader dies in a siege, then points loss in increased by 50%. If a friendly military leader is nearby when a soldier dies in a siege, then points loss is reduced by 20%. If an enemy military leader is nearby when a soldier dies in a siege, then points loss is increased by 20%.

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

#### Make friends & allies
Diplomacy is critical.  As a mayor, diplomacy can be the difference between your town remaining independant, within a friendly nation, or occupied by an expansionistic empire. As a king, diplomacy can be the difference between your nation succeeding, and its annihilation.

#### Do not remove guards while the town is under siege
As a mayor, while your town is under siege, do not remove guards by any means. If this occurs, a siege-point penalty will be applied. 

As a king, while you OR your allies have in-progress sieges, do not remove soldiers by any means. If this occurs, a siege-point penalty will be applied at each of the sieges.  

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

## Miscellaneous

### Commands

#### General
- /vote - Vote to receive rewards.
- /gold - Open the gold shop.
- /balance - Check your money balance.
- /baltop - View the top balances.
- /trade - Request to trade with a player.
- /weapons - Opens the weapon shop (Nova only).
- /vehicles - Opens the vehicle shop (Nova only).
- /garage - Opens your vehicle garage. (Nova only).
- /rocket - Purchase a space rocket (Nova only).
- /pvp - Toggle personal PvP status (Elysia only).

#### Chat
- /channel - View channel commands.
- /join [channel] - Join a chat channel.
- /leave [channel] - Leave a chat channel. 
- /g [message] - Join or send a message in global channel.
- /l [message] - Join or send a message in local channel.
- /tc [message] - Join or send a message in town channel.
- /nc [message] - Join or send a message in nation channel.
- /ac [message] - Join or send a message in ally channel.
- /tr [message] - Join or send a message in trade channel.
- /msg - Send a private message to a player.
- /ignore - Block messages from a player.

## Ranks
Support the development of Datearth and earn some neat perks at [shop.datblock.com](https://shop.datblock.com). We strive to keep the perks fair while giving those that support the server something nice in return. The perks are meant to be bonuses for our supporters as a thank you for making Datearth possible for everyone.

| Perks | VIP | VIP+ | VIP++ | MVP | MVP+ | MVP++ | ROYAL |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | 
| Get more money when voting. | $75 | $100 | $125 | $150 | $175 | $200 | $250 |
| Get more gold when voting. | 2G | 3G | 4G | 6G | 8G | 10G | 15G |
| Be able to create more shops. | 15 | 20 | 25 | 30 | 40 | 50 | 100 |
| Join when the server is full. | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Get access to the gold shop. | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Toggle night vision with /nv. |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Sort your inventory with /invsort. |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Express yourself with /emotes. |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Sort your chests with /chestsort. |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Color sign text with color codes. |  |  | ✔️ | ✔️ | ✔️ | ✔️ | ✔️ |
| Send mail with /mail send. |  |  |  | ✔️ | ✔️ | ✔️ | ✔️ |
| Sort inv. into chests with /unload. |  |  |  | ✔️ | ✔️ | ✔️ | ✔️ |
| Open a crafting table with /craft. |  |  |  | ✔️ | ✔️ | ✔️ | ✔️ |
| Keep your experience on death. |  |  |  |  | ✔️ | ✔️ | ✔️ |
| Put inv. into chest with /dump. |  |  |  |  | ✔️ | ✔️ | ✔️ |
| Repair an item with /fix once a day. |  |  |  |  | ✔️ | ✔️ | ✔️ |
| Non-combat fly in your town with /tfly. |  |  |  |  |  | ✔️ | ✔️ |
| Play music within an area with /music. |  |  |  |  |  | ✔️ | ✔️ |
| Change color of firearm with /skins. |  |  |  |  |  | ✔️ | ✔️ |
| Change your display name with /nick. |  |  |  |  |  | ✔️ | ✔️ |
| Replenish your hunger with /feed. |  |  |  |  |  |  | ✔️ |
| Equip an item as a hat with /hat. |  |  |  |  |  |  | ✔️ |
| Open your ender chest with /echest. |  |  |  |  |  |  | ✔️ |

## Rules

### Cheating

Players are normally banned 7 to 30 days for their first offense of breaking a cheating rule and on the second offense banned for 30 days or permanently. A player may be banned up to 30 days or permanently on their first offense if severe damage is caused to the server or another player.

1.1 No client modifications that give an advantage. Modifications for pure aesthetics, armor and effects HUD, maps that don't display more than live map, or reducing client lag are allowed, like Optifine.
- Xray and hack client cheats, like increased speed, fly, kill aura is punished by 30 days to permanent ban on first offense.

1.2 No abusing bugs that give an advantage. Bugs must be reported to staff privately.

1.3 No non-human activity, like auto clicking for fishing. You must be able to respond to a staff member.

1.4 A player may only have one minecraft account on the server.

### Gameplay Behavior

Players are normally warned for their first offense of breaking a gameplay behavior rule and on the second offense banned 1 to 7 days. A player may be banned up to 30 days or permanently on their first offense if severe damage is caused to the server or another player.

2.1 No bypassing AFK kick, like using an AFK pool.

2.2 No targeting or jailing players that joined less than 2 days ago. Use /resident to check their join date. If a new player is targeting you, you may defend yourself. Being kind to new players is a good courtesy and encouraged.

2.3 No nonreciprocal killing of the same player more than twice within 24 hours if not at war with them, unless they are going near you, going near your claims, or attacking an ally. This rule only applies to the overworld.

2.4 No killing sprees, where you kill more than 5 players within an hour, unless the player is at war with you. This rule only applies to the overworld.

2.5 No camping, where you camp a town for longer than 15 minutes.

2.6 Stealing, like taking a player's items, animals in a town, or from containers is allowed. It is the responsibility of the player to protect their items.

2.7 Scamming, like not trading fairly is allowed. It is the responsibility of the player to build trust and be careful of others.

2.8 Do not settle within 10 chunks of another town's border without their permission. Your town may be removed.

2.9 If a mayor of a town is inactive for more than 2 weeks, players may request by a ticket to be granted mayorship of the town. Residents of the town have first priority and residents within the same nation have second priority to be granted mayorship of the town. A town is automatically deleted after 30 days if no residents are active in the town and any player may reclaim the town after deletion.

2.10 No nether portal trapping, do not block up portals in a way where a player can't access commands by being stuck in the nether portal animation.

2.11 No heavy redstone use and slime block planes.

2.12 No building or claiming within the spawning zone in Africa.

### Player Behavior

Players are normally warned for their first offense of breaking a player behavior rule and on the second offense muted if chat related or banned 1 to 7 days if non-chat related. A player may be banned up to 30 days or permanently on their first offense if severe damage is caused to the server or another player.

3.1 English only in the global channel.

3.2 No spamming, like repeatedly advertising trades or flooding the chat.

3.3 No cursing or bypassing the chat filter. Keep it appropriate for everyone.

3.4 No harmful, abusive, or inappropriate expressions in chat, signs, skins, or buildings. This includes name-calling, insulting, bullying, harrashment, hate speech, discrimination, obscene content, talking or threatening about self-harm, encouraging violence or hatred towards others.

3.6 No references to Nazi Germany, the Soviet Union, and the Islamic State, like Swastikas, Soviet Sickles.

3.7 No sharing others' personal information, like IP, name, email, phone number.

3.8 No misleading and baiting a player to type a command, like /suicide.

3.9 Do not accuse rule-breakers publicly, report with /report or make a ticket at disc.datblock.com.

3.10 Do not discuss, disagree or appeal a staff action publicly, make a ticket a disc.datblock.com. You may only appeal bans and not warns or mutes.

### Griefing

Players are normally banned 1 to 7 days for their first offense of breaking a griefing rule if it has caused great damage and on the second offense banned 7 to 30 days. If the grief has caused minor damage, the player may be warned for their first offense and on the second offense banned 1 to 7 days. A player may be banned up to 30 days or permanently on their first offense if severe damage is caused to the server or another player.

4.1 No griefing, like destroying buildings or placing blocks in a mess. You may only break valuable blocks, crops, and containers from unclaimed towns. Valuable blocks are ore and mineral blocks, enchanting tables, bookshelves, beacons, conduits, enderchests, anvils and brewing stands. A fallen town may be freely broken down, be taken, or be requested to be removed by staff. Be sure it is a fallen town and not a town being settled. Buildings in the nether and the end may be broken down at any time and are not proteced from griefing.

4.2 No building outside of claims, except minor building outside of your own town or when settling a new town where the settlers have 7 days to claim the land. Make a ticket at disc.datblock.com if you want an unlawful building in unclaimed land to be removed.

4.3 No Modifying terrain nearby other claims (10 chunks), except your own claims on a minor scale that does not look unnatural.

4.4 No claiming or making outposts nearby or around other claims (10 chunks) without permission, or claiming in an obnoxious manner like a straight line.

4.5 Players must conserve the world map terrain. No major harvesting and terraforming like taking down mountains, draining, flooding with lava or water, placing random blocks, deforestation, digging holes, and flattening large areas without intent to build.

4.6 No cobble monsters, faction-like bases, pixel art or any form of building that stands out from the towns and nation building lore.

4.7 No building on the water with exceptions like Venice, canals, and minor builds in bays and rivers. Make a ticket at disc.datblock.com to request permission to build on water.

4.8 Mass spawning entities like boats is not allowed.

### Naming

Players are normally not punished for breaking a naming rule but may be depending on the severity. Staff may at any given time change a town or nation name for any reason staff deems reasonable. Make a ticket at disc.datblock.com for rule exceptions and if you're unsure whether a name is allowed.

5.1 Nation Naming
- Nation name has to be the same as current or past nations that correspond with where the capital is located on the world map.
- Nations can't be named identically to already existing nations on the server.
- Nations can't be named after unions, alliances, regions, oceans, or after a continent.

5.2 Town Naming
- Town names may be fictional but must have a connection to where the town is located and must sound like a realistic town name.
- Towns can't be named identically to already existing towns on the server.

5.3 Any inappropriate, offensive, explicit or racist naming is not allowed anywhere.

### War

Players are normally warned for their first offense of breaking a war rule and on the second offense banned 1 to 7 days. A player may be banned up to 30 days or permanently on their first offense if severe damage is caused to the server or another player.


6.1 Neutral is neutral. Neutral towns may not participate in any wars such as helping a nation with a siege. Residents in a neutral town participating in a war will be punished and the town may lose its right to neutrality. This also applies to residents that are not an official ally with the nations at war. If you are not related to a war, you should not approach the siege zone.

6.2 Looting towns. If a town enters a ruined state, the town may be looted of containers and valuable blocks. Valuable blocks are ore and mineral blocks, enchanting tables, bookshelves, beacons, conduits, ender chests, anvils, and brewing stands. Blocks can be destroyed in ruined towns, but blocks may only be broken to get through barriers such as doors or walls to valuables. Any excessive or unnecessary breaking will be punished. The ruined state lasts 24 hours whereafter the town is fully deleted. The first to claim the town again is the rightful owner of the town.

6.3. Defences in wilderness. The attacking nation is allowed to construct small walls at the siege zone to protect themselves from ranged attacks. It is not allowed to build any construction that hinders reaching the siege zone or players in the zone.

6.4 Fair wars. Any use of bugs or unintended behavior to gain an advantage in a siege will be punished. Use common sense or ask staff if unsure.

### Miscellaneous

7.1 Intentionally crashing the server or producing lag will result in a permanent ban.

7.2 Advertising other servers or products is not allowed.
- Advertisers deemed as only being on the server to advertise will be permanently banned.

7.3 Real world traders for services and items will be permanently banned.

### Staff

8.1 If a player makes a ticket to appeal their ban, the staff that banned the player may not make any final judgments for the appeal but only provide arguments and evidence for the reasoning of giving the ban.

8.2 If a player makes a ticket to report staff abuse, the staff member that is accussed of staff abuse may not make any judgments for the report but only provide arguments and evidence. The report must be seen by a minimun of two admins before a judgement is made. If you have suspicion of staff abuse but do not have any evidence, you may privately message @Lambsauce#0001 at disc.datblock.com.
