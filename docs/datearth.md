## War

_This page is a work in progress. What is currently written may not be the final design of the war system._

### Sieging

As a king or general, place a coloured banner in the wilderness close to a town to initiate a siege. Starting a siege will cost the attacking nation $1500. This money will be recovered by the siege winner.

#### Score

The town under siege has a score shown in `/t` that will determine the siege winner. The attacker requires a positive score to win and the defender requires a negative score to win. A siege lasts 3 days unless the attacker or defender surrenders. 

#### Occupying
As an attacker or a defender with a military rank, occupy the wilderness area within 16 blocks of the siege banner to increase or decrease the score by 10 points every 30 seconds occupied. Allies with a military rank can contribute.

#### Killing
As an attacker or a defender with a military rank, kill enemy players within a 100 block radius of the siege banner to increase or decrease the score by 200 points. Allies with a military rank can contribute.

#### Abandon attack
As a king or general, place an all-white banner near the siege-attack-banner.

#### Surrender town
As a mayor, place an all-white banner anywhere in the town.

#### Plunder town
As a king or general, after the siege is won, place a chest in the wilderness close to the town. This action will rob the town $500 per plot, transferring it to the plundering nation.

#### Capturing town
As a king or general, after the siege is won, place a coloured banner in the wilderness close to the town. This action will forcibly add the town to the nation, and will put the town into an 'occupied' state, in which its residents cannot affect siege points. 

### Commands

View detailed information on any siege affecting the town, using `/t`.

View a list of any sieges the nation is involved in, using `/n`.

#### Town neutrality
As a mayor, declare your town to be neutral using `/t toggle neutral`. A neutral town cannot voluntarily join any nation and is immune to siege-forced-pvp, plunder, and occupation taxes. Attackers can still invade if they manage to defeat the town, but the occupation is in-name-only, with no material benefits provided except to increase nation town count.

#### Town revolt
As a mayor, when a certain duration has passed after an invasion, typically many days, the town can revolt and be free of the occupying nation. This is done using `/n leave`.

#### Nation deletion
As a king, if your nation gets deleted for any reason, including capture of your last town, you will be refunded 90% of the initial setup cost. This can be triggered voluntarily using `/n delete`.

### Tips

#### Fortify towns
Walls are important. During sieges they help stop enemies from infiltrating towns and killing residents.

#### Fortify or abandon outposts
Outposts are important. Towns can be besieged anywhere they have claimed territory.  Make provisions to defend valuable outposts, and abandon the rest.

#### Assign war ranks
Find residents who can be trusted to fight for your town or nation, and assign them the ranks of guard/sheriff(town) or soldier/general(nation)

#### Watch your town bank balance
As a mayor, keep enough money in the bank for sieges. If a town is plundered of all its gold by a siege attacker, the town will be destroyed, entering a ruined state for some time. During this time the town blocks cannot be reclaimed, but all perms will be enabled.

#### Make friends & allies
Diplomacy is critical.  As a mayor, diplomacy can be the difference between your town remaining independant, within a friendly nation, or occupied by an expansionistic empire. As a king, diplomacy can be the difference between your nation succeeding, and its annihilation.

#### You are not entitled to power
As a king, your claim to power will be tested. Defend your nation's towns to prove yourself a true nation leader.

