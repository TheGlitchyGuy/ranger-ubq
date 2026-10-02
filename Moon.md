:::tracker{species="Popplio" baseStats="\[\[50,54,54,66,56,40], \[60,69,69,91,81,50], \[80,74,74,126,116,60]]" hiddenPower="true" generation="7"}
5:
6 -> 0, 0, 0, 0, 0, 1
7 -> 0, 1, 0, 0, 0, 2
8 -> 0, 1, 0, 0, 0, 4
9 -> 0, 1, 2, 0, 0, 4
10 -> 0, 1, 3, 0, 0, 4
11 -> 1, 2, 3, 0, 0, 4
12 -> 1, 2, 3, 1, 0, 6
13 -> 1, 3, 3, 1, 0, 7
14 -> 1, 3, 3, 1, 1, 10
15 -> 1, 3, 3, 1, 2, 12
16 -> 1, 3, 3, 1, 2, 18
17 -> 2, 5, 3, 1, 2, 18
18 -> 2, 5, 3, 3, 2, 19
19 -> 4, 5, 3, 3, 2, 20
20 -> 8, 5, 3, 3, 2, 20
21 -> 8, 7, 3, 3, 2, 20
22 -> 8, 7, 5, 5, 3, 20
23 -> 8, 7, 5, 5, 3, 24
24 -> 8, 7, 5, 5, 5, 26
25 -> 8, 7, 5, 5, 5, 26
26 -> 8, 8, 5, 5, 5, 26
27 -> 8, 9, 5, 5, 5, 26
28 -> 8, 9, 5, 5, 5, 26
29 -> 8, 18, 5,	5, 5, 29
30 -> 8, 19, 7,	5, 5, 32
31 -> 8, 21, 7, 5, 5, 36
32 -> 8, 21, 7, 5, 5, 36
33 -> 8, 21, 7, 5, 5, 36
	34 -> 8, 24, 11, 5, 5, 36
	35 -> 8, 24, 17, 8, 5, 36
	36 -> 8, 26, 19, 10, 6, 37
	37 -> 8, 26, 19, 20, 10, 37
	38 -> 8, 26, 20, 20, 11, 41
	39 -> 9, 29, 22, 20, 11, 41
	40 -> 9, 29, 22, 20, 11, 41
	41 -> 9, 29, 22, 20, 11, 41


:::

:::tracker{species="Lunala" baseStats="\[\[137,113,89,137,107,97]]"}
55:
56 -> 0,0,0,0,0,0
:::

:::tracker{species="Pheromosa" baseStats="\[\[71,137,37,137,37,151]]"}
60:
61 -> 0,0,0,0,0,0
:::

*Enter in your Level 55 Sp.Atk and Speed Stats*

:::if{source="Lunala" condition="spa=(x/x/21+) \&\& spe=(21+/0+/0+)"}
\[Do Not Candy - Early Acerola with no Candy]
:::
:::if{source="Lunala" condition="spa=(x/x/21+) \&\& spe=(16-20/x/x)"}
\[Use a Rare Candy! - Early Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/x/16-20) \&\& spe=(21+/0+/0+)"}
\[Use a Rare Candy! - Early Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/x/16-20) \&\& spe=(16-20/x/x)"}
\[Use a Rare Candy! - Early Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/x/16+) \&\& spe=(13-15/x/x)"}
\[Use a Rare Candy! - Late Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/26+/0-15) \&\& spe=(16+/0+/0+)"}
\[Use a Rare Candy! - Late Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/26+/0-15) \&\& spe=(13-15/x/x)"}
\[Use a Rare Candy! - Late Acerola with Candy]
:::
:::if{source="Lunala" condition="spa=(x/9-13/x)"}
\[Use a Rare Candy! - For final Hau fight, if you are doing Version 1--> do Version 1.5; Old E4 Strats!]
:::
:::if{source="Lunala" condition="spa=(0+/14-25/x)|| spa=(x/0-8/x)"}
\[Do Not Candy - Old E4 Strats]
:::
:::if{source="Lunala" condition="spa=(0+/0-8/x)\&\& spe=(0-12/x/x)"}
\[Do Not Candy - Old E4 Strats]
:::
:::if{source="Lunala" condition="spa=(x/14+/0+)\&\& spe=(0-12/x/x)"}
\[Do Not Candy - Old E4 Strats]
:::





* ::damage\[Weavile's Ice Shard at lvl 55]{source="Lunala" special=false offensive=false movePower=40 stab=true level=55 opponentLevel=52 opponentStat=178}
* ::damage\[Weavile's Ice Shard at lvl 56]{source="Lunala" special=false offensive=false movePower=40 stab=true level=56 opponentLevel=52 opponentStat=178}







* **RANGE CITY**
* Weavile :

::damage\[Moongeist Beam no MC]{source="Lunala" offensive=true special=true stab=true movePower=100 level=59 evs=4 effectiveness=0.5 combatStages=4 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}



::damage\[Moongeist Beam with MC]{source="Lunala" offensive=true special=true stab=true movePower=100 level=58 evs=1 effectiveness=0.5 combatStages=4 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}

::damage\[SB without MC]{source="Lunala" offensive=true special=true stab=true movePower=80 level=59 evs=4 effectiveness=0.5 combatStages=4 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}

::damage\[SB with MC]{source="Lunala" offensive=true special=true stab=true movePower=80 level=58 evs=1 effectiveness=0.5 combatStages=4 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}

+6 VERY LOW SPECIAL

::damage\[Moongeist Beam no MC +6]{source="Lunala" offensive=true special=true stab=true movePower=100 level=59 evs=4 effectiveness=0.5 combatStages=6 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}

::damage\[Moongeist Beam with MC +6]{source= "Lunala" offensive=true special=true stab=true movePower=100 level=58 evs=1 effectiveness=0.5 combatStages=6 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}



::damage\[SB without MC +6]{source="Lunala" offensive=true special=true stab=true movePower=80 level=59 evs=4 effectiveness=0.5 combatStages=6 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}

::damage\[SB with MC +6]{source= "Lunala" offensive=true special=true stab=true movePower=80 level=58 evs=1 effectiveness=0.5 combatStages=6 opponentLevel=61 opponentStat=117 otherPowerModifier=1.2 healthThreshold=175 theme="error"}





Salamence

::damage\[Psychic with MC]{source="Lunala" offensive=true special=true stab=true movePower=80 level=58 evs=1 combatStages=4 opponentLevel=61 opponentStat=111 healthThreshold=205 theme="error"}

::damage\[Psychic without MC]{source="Lunala" offensive=true special=true stab=true movePower=80 level=59 evs=4 combatStages=4 opponentLevel=61 opponentStat=111 healthThreshold=205 theme="error"}

::damage\[SB with MC +6]{source="Lunala" offensive=true special=true stab=true movePower=80 level=58 evs=1 effectiveness=1 combatStages=4 opponentLevel=61 opponentStat=111 otherPowerModifier=1.2 healthThreshold=205 theme="error"}



mina :

* klefki MB at +6 under light screen
* ::damage\[Moongeist Beam no MC +6]{source="Lunala" offensive=true special=true stab=true movePower=100 level=60 evs=8 effectiveness=1 combatStages=6 screen=true opponentLevel=61 opponentStat=168 otherPowerModifier=1.2  healthThreshold=159 theme="error"}
* ::damage\[Moongeist Beam MC +6]{source="Lunala" offensive=true special=true stab=true movePower=100 level=59 evs=5 effectiveness=1 combatStages=6 screen=true opponentLevel=61 opponentStat=168 otherPowerModifier=1.2  healthThreshold=159 theme="error"}

NANU (Mirror Coat only so far) ?:

Sableye aria
::damage\[Aria on Sableye at +2]{source="Popplio" evolution=2 offensive=true special=true stab=true movePower=90 level=58 evs=44 effectiveness=1 combatStages=2 opponentLevel=63 opponentStat=146 otherPowerModifier=1.2 healthThreshold=155 theme="error"}
moonblast

* If not going for the range, moonblast

:damage\[Bug Buzz]{source="Pheromosa" offensive=true special=false stab=true movePower=80 level=60 effectiveness=1 combatStages=2 opponentLevel=63 opponentStat=118 healthThreshold=155 theme="error"}

:::if{source="Popplio" condition="spatk=(#/24-/1+)"} || spatk(x/28+/x)"}

* bla bla bla
:::

