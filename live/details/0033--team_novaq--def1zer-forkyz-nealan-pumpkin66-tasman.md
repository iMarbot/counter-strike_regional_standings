### Roster Details<br />
Team Name: Team Novaq<br />
Roster: def1zer, forkyz, neaLaN, Pumpkin66, tasman<br />
Global Rank: [33](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1043.1<br />
<br />
Final Rank Value (1043.1) = Starting Rank Value (1121.8) + Head To Head Adjustments (-78.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.327[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.638[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1121.8
- 400 + ( ( 0.361 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 1121.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       99 | 2025-02-23 | Roler Coaster    | L   | 1.000      | -            | -                | -                | -         |   -29.61 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           25 |      132 | 2025-02-22 | Openai chatgpt   | W   | 1.000      | -            | -                | -                | -         |     0.71 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           24 |      233 | 2025-02-20 | POLET            | L   | 1.000      | -            | -                | -                | -         |   -30.17 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           23 |      683 | 2025-02-08 | Little Red Door  | L   | 1.000      | -            | -                | -                | -         |   -29.79 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           22 |      695 | 2025-02-08 | Fnatic           | W   | 1.000      | 0.143        | 0.072 (0.010)    | 0.461 (0.066)    | -         |    13.99 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           21 |      774 | 2025-02-07 | Iberian Soul     | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.553 (0.079)    | -         |     4.78 | def1zer, forkyz, neaLaN, Pumpkin66, tasman     |
|           20 |     1640 | 2024-12-15 | AK BARS          | W   | 0.691      | 0.333        | 0.008 (0.002)    | 0.212 (0.049)    | 1 (0.691) |     4.51 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           19 |     1651 | 2024-12-15 | AimAssassins     | W   | 0.691      | 0.333        | 0.004 (0.001)    | 0.240 (0.055)    | 1 (0.691) |     6.17 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           18 |     1717 | 2024-12-14 | Mix52            | W   | 0.684      | 0.333        | 0.002 (0.000)    | 0.064 (0.015)    | 1 (0.684) |     2.81 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           17 |     1729 | 2024-12-13 | DEPO             | W   | 0.684      | 0.333        | 0.006 (0.001)    | 0.297 (0.068)    | 1 (0.684) |     3.32 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           16 |     1789 | 2024-12-13 | AK BARS          | L   | 0.679      | -            | -                | -                | -         |   -17.37 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           15 |     1796 | 2024-12-13 | Mix52            | W   | 0.679      | 0.333        | 0.002 (0.000)    | 0.064 (0.014)    | 1 (0.679) |     2.45 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           14 |     2394 | 2024-12-01 | MYSKILL          | W   | 0.600      | 0.143        | 0.002 (0.000)    | -                | -         |     1.65 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           13 |     2405 | 2024-12-01 | ALLINNERS        | L   | 0.600      | -            | -                | -                | -         |   -17.10 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           12 |     2426 | 2024-12-01 | Mix52            | W   | 0.599      | -            | -                | -                | -         |     2.05 | dako, def1zer, forkyz, Pumpkin66, tasman       |
|           11 |     3316 | 2024-11-16 | GTZ.ESPORTS      | L   | 0.500      | -            | -                | -                | -         |    -7.36 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|           10 |     3385 | 2024-11-15 | KONO.ECF         | W   | 0.493      | 0.617        | 0.045 (0.014)    | 0.757 (0.230)    | 1 (0.493) |     3.25 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            9 |     3391 | 2024-11-15 | GnG x Amazigh    | W   | 0.492      | -            | -                | -                | 1 (0.492) |     0.26 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            8 |     3443 | 2024-11-14 | Team Latvia      | W   | 0.486      | 0.617        | -                | 0.046 (0.014)    | 1 (0.486) |     0.75 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            7 |     3452 | 2024-11-14 | Nexus Gaming     | W   | 0.486      | 0.617        | 0.186 (0.056)    | 0.808 (0.242)    | 1 (0.486) |     7.02 | dako, def1zer, demente, neaLaN, Pumpkin66      |
|            6 |     6822 | 2024-09-17 | Partizan Esports | L   | 0.100      | -            | -                | -                | -         |    -1.69 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            5 |     6934 | 2024-09-15 | DEPO             | W   | 0.085      | -            | -                | -                | 1 (0.085) |     0.34 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            4 |     7034 | 2024-09-14 | MYSKILL          | W   | 0.078      | -            | -                | -                | -         |     0.18 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            3 |     7053 | 2024-09-13 | LostEverySense   | W   | 0.077      | -            | -                | -                | -         |     0.04 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            2 |     7067 | 2024-09-13 | PodREDBULom      | W   | 0.073      | -            | -                | -                | -         |     0.04 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |
|            1 |     7616 | 2024-09-05 | Team Uzbekistan  | W   | 0.018      | -            | -                | -                | -         |     0.01 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,164.20)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.691 | $5,000.00      | $3,456.94       |
| 2024-11-17 |      0.506 | $12,500.00     | $6,328.13       |
| 2024-09-22 |      0.133 | $175.00        | $23.24          |
| 2024-09-15 |      0.085 | $4,166.59      | $355.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
