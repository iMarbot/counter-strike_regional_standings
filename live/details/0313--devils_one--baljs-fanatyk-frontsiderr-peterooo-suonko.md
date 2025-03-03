### Roster Details<br />
Team Name: Devils.one<br />
Roster: baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko<br />
Global Rank: [313](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [206]( ../standings_europe.md)<br />
<br />
Final Rank Value:  642.7<br />
<br />
Final Rank Value (642.7) = Starting Rank Value (648.2) + Head To Head Adjustments (-5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.245[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 648.2
- 400 + ( ( 0.124 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 648.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     3912 | 2024-11-06 | 777 Esports                 | L   | 0.423      | -            | -                | -                | -         |    -6.23 | baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko     |
|           24 |     4168 | 2024-11-02 | Leo Team                    | L   | 0.396      | -            | -                | -                | -         |    -3.43 | baljs, fanatyk, Frontsiderr, PeTeRoOo, suonko     |
|           23 |     4362 | 2024-10-29 | Kyoto (European mix-team)   | L   | 0.373      | -            | -                | -                | -         |    -5.51 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           22 |     5005 | 2024-10-16 | Team Czech Republic         | L   | 0.285      | -            | -                | -                | -         |    -3.78 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           21 |     5079 | 2024-10-15 | ENTERPRISE Genesis          | W   | 0.278      | 0.143        | 0.001 (0.000)    | 0.175 (0.007)    | 0 (0.000) |     4.13 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           20 |     5111 | 2024-10-14 | Kyoto (European mix-team)   | L   | 0.271      | -            | -                | -                | -         |    -4.12 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           19 |     5122 | 2024-10-14 | KUUSAMO.gg                  | W   | 0.270      | 0.278        | -                | 0.162 (0.012)    | 0 (0.000) |     2.58 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           18 |     5143 | 2024-10-13 | XI Esport                   | L   | 0.265      | -            | -                | -                | -         |    -5.82 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           17 |     5439 | 2024-10-08 | 777 Esports                 | W   | 0.230      | 0.278        | 0.002 (0.000)    | 0.235 (0.015)    | 0 (0.000) |     3.56 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           16 |     5594 | 2024-10-05 | ENTERPRISE Genesis          | W   | 0.211      | 0.278        | 0.001 (0.000)    | 0.175 (0.010)    | 0 (0.000) |     3.16 | fanatyk, Frontsiderr, PeTeRoOo, suonko, ZEMO      |
|           15 |     5917 | 2024-09-30 | GardenGarage                | L   | 0.178      | -            | -                | -                | -         |    -2.13 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           14 |     5983 | 2024-09-29 | Los kogutos                 | W   | 0.170      | 0.143        | 0.032 (0.001)    | 0.515 (0.012)    | 0 (0.000) |     4.64 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           13 |     6376 | 2024-09-24 | Dynamo Eclot                | L   | 0.138      | -            | -                | -                | -         |    -0.38 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           12 |     6394 | 2024-09-24 | Error404                    | W   | 0.138      | -            | -                | -                | 0 (0.000) |     0.84 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|           11 |     6602 | 2024-09-21 | 9Pandas                     | L   | 0.117      | -            | -                | -                | -         |    -0.53 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|           10 |     6655 | 2024-09-20 | Johnny Speeds               | L   | 0.110      | -            | -                | -                | -         |    -0.71 | fanatyk, Frontsiderr, karmazynsz, Pelle, PeTeRoOo |
|            9 |     6712 | 2024-09-19 | BC.Game Esports             | W   | 0.104      | 0.443        | 0.078 (0.004)    | 0.945 (0.043)    | 0 (0.000) |     2.94 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            8 |     7023 | 2024-09-14 | 9INE                        | W   | 0.070      | 0.443        | 0.011 (0.000)    | 0.217 (0.007)    | 0 (0.000) |     1.43 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            7 |     7055 | 2024-09-14 | RUSH B (Russian team)       | W   | 0.069      | 0.443        | 0.028 (0.001)    | 0.915 (0.028)    | 0 (0.000) |     1.74 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            6 |     7240 | 2024-09-10 | Zero Tenacity               | W   | 0.045      | 0.143        | 0.028 (0.000)    | 0.684 (0.004)    | 0 (0.000) |     1.10 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|            5 |     7244 | 2024-09-10 | 500 Rush                    | W   | 0.045      | 0.143        | 0.002 (0.000)    | 0.141 (0.001)    | -         |     0.70 | baljs, fanatyk, Frontsiderr, PeTeRoOo, ZEMO       |
|            4 |     7608 | 2024-09-05 | Sleepwalkers (Russian team) | W   | 0.011      | -            | -                | -                | -         |     0.07 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            3 |     7620 | 2024-09-05 | Iuhop (Russian team)        | W   | 0.010      | -            | -                | -                | -         |     0.09 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            2 |     7659 | 2024-09-04 | LEON Esports                | W   | 0.005      | 0.221        | 0.010 (0.000)    | -                | -         |     0.11 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |
|            1 |     7663 | 2024-09-04 | 5goblinz                    | W   | 0.005      | -            | -                | -                | -         |     0.03 | fanatyk, Frontsiderr, Pelle, PeTeRoOo, ZEMO       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($275.25)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-24 |      0.137 | $2,000.00      | $273.06         |
| 2024-09-05 |      0.011 | $200.00        | $2.19           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
