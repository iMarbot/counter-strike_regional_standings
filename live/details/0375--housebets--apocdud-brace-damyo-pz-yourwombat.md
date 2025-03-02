### Roster Details<br />
Team Name: Housebets<br />
Roster: apocdud, BRACE, damyo, pz, yourwombat<br />
Global Rank: [375](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [61]( ../standings_asia.md)<br />
<br />
Final Rank Value:  610.0<br />
<br />
Final Rank Value (610.0) = Starting Rank Value (625.8) + Head To Head Adjustments (-15.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.8
- 400 + ( ( 0.113 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 625.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      383 | 2025-02-15 | KZG                         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.165 (0.024)    | 0 (0.000) |    15.49 | apocdud, BRACE, damyo, pz, yourwombat        |
|           19 |      446 | 2025-02-14 | Vantage Esports             | L   | 1.000      | -            | -                | -                | -         |   -12.69 | apocdud, BRACE, damyo, pz, yourwombat        |
|           18 |      451 | 2025-02-14 | BBBCBMBS                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |     8.12 | apocdud, BRACE, damyo, pz, yourwombat        |
|           17 |      649 | 2025-02-08 | DogEvil                     | L   | 1.000      | -            | -                | -                | -         |    -6.34 | apocdud, BRACE, damyo, pz, yourwombat        |
|           16 |      726 | 2025-02-07 | JiJieHao                    | L   | 1.000      | -            | -                | -                | -         |   -13.36 | apocdud, BRACE, damyo, pz, yourwombat        |
|           15 |     2918 | 2024-11-22 | Mindfreak (Australian team) | L   | 0.543      | -            | -                | -                | -         |    -6.49 | apocdud, BRACE, damyo, pz, yourwombat        |
|           14 |     4864 | 2024-10-19 | Mindfreak (Australian team) | L   | 0.310      | -            | -                | -                | -         |    -3.64 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           13 |     4908 | 2024-10-18 | Only One Word               | W   | 0.304      | 0.333        | 0.001 (0.000)    | 0.191 (0.019)    | 0 (0.000) |     5.02 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           12 |     4960 | 2024-10-17 | KZG                         | W   | 0.297      | 0.333        | 0.001 (0.000)    | 0.165 (0.016)    | 0 (0.000) |     4.68 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           11 |     5632 | 2024-10-04 | Only One Word               | L   | 0.217      | -            | -                | -                | -         |    -3.30 | apocdud, BRACE, damyo, Omichella, yourwombat |
|           10 |     5635 | 2024-10-04 | Mindfreak (Australian team) | L   | 0.216      | -            | -                | -                | -         |    -2.59 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            9 |     5640 | 2024-10-04 | MANTRA                      | W   | 0.215      | 0.143        | 0.000 (0.000)    | 0.175 (0.005)    | 0 (0.000) |     3.32 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            8 |     5867 | 2024-10-01 | KZG                         | L   | 0.191      | -            | -                | -                | -         |    -3.03 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            7 |     5874 | 2024-10-01 | KZG                         | W   | 0.191      | 0.333        | 0.001 (0.000)    | 0.165 (0.010)    | 0 (0.000) |     3.03 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            6 |     6226 | 2024-09-26 | FlyQuest                    | L   | 0.158      | -            | -                | -                | -         |    -0.32 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            5 |     6231 | 2024-09-26 | FlyQuest                    | L   | 0.157      | -            | -                | -                | -         |    -0.32 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            4 |     6317 | 2024-09-25 | Rooster                     | L   | 0.151      | -            | -                | -                | -         |    -2.04 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            3 |     6326 | 2024-09-25 | Rooster                     | L   | 0.151      | -            | -                | -                | -         |    -2.07 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            2 |     6776 | 2024-09-18 | Mindfreak (Australian team) | L   | 0.104      | -            | -                | -                | -         |    -1.29 | apocdud, BRACE, damyo, Omichella, yourwombat |
|            1 |     6777 | 2024-09-18 | Mindfreak (Australian team) | W   | 0.104      | 0.333        | 0.002 (0.000)    | 0.093 (0.003)    | 0 (0.000) |     2.00 | apocdud, BRACE, damyo, Omichella, yourwombat |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($442.94)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.316 | $1,400.00      | $442.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
