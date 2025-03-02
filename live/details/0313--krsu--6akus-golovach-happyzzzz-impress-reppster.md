### Roster Details<br />
Team Name: KRSU<br />
Roster: 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster<br />
Global Rank: [313](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [47]( ../standings_asia.md)<br />
<br />
Final Rank Value:  641.5<br />
<br />
Final Rank Value (641.5) = Starting Rank Value (618.7) + Head To Head Adjustments (22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 618.7
- 400 + ( ( 0.109 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 618.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1629 | 2024-12-15 | KNU      | L   | 0.692      | -            | -                | -                | -         |   -10.81 | 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster |
|            4 |     1639 | 2024-12-15 | IUK      | W   | 0.692      | 0.143        | 0.001 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     9.42 | 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster |
|            3 |     1647 | 2024-12-15 | KSTU     | W   | 0.691      | 0.143        | 0.000 (0.000)    | 0.032 (0.003)    | 0 (0.000) |     9.55 | 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster |
|            2 |     1720 | 2024-12-14 | Ala-Too  | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.19 | 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster |
|            1 |     1887 | 2024-12-11 | KSMA 1   | W   | 0.665      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.40 | 6akus, GOLOVACH, HappyZzzz, ImpreSs, Reppster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($477.63)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.692 | $689.99        | $477.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
