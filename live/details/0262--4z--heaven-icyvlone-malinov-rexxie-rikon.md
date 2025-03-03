### Roster Details<br />
Team Name: 4z<br />
Roster: HeaveN, icyvlone, malinov, rexxie, rikon<br />
Global Rank: [262](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [180]( ../standings_europe.md)<br />
<br />
Final Rank Value:  673.0<br />
<br />
Final Rank Value (673.0) = Starting Rank Value (659.5) + Head To Head Adjustments (13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.5
- 400 + ( ( 0.130 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 659.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1624 | 2024-12-15 | KZ Esports      | W   | 0.686      | 0.310        | 0.009 (0.002)    | 0.112 (0.024)    | 0 (0.000) |    12.00 | HeaveN, icyvlone, malinov, rexxie, rikon |
|            9 |     1843 | 2024-12-12 | ZOTIX           | W   | 0.665      | 0.310        | 0.001 (0.000)    | 0.147 (0.030)    | 0 (0.000) |    10.61 | HeaveN, icyvlone, malinov, rexxie, rikon |
|            8 |     2169 | 2024-12-05 | KZ Esports      | L   | 0.618      | -            | -                | -                | -         |    -8.46 | HeaveN, icyvlone, malinov, rexxie, rikon |
|            7 |     2279 | 2024-12-03 | QMISTRY         | W   | 0.605      | 0.310        | 0.001 (0.000)    | 0.027 (0.005)    | 0 (0.000) |     8.88 | HeaveN, icyvlone, malinov, rexxie, rikon |
|            6 |     2444 | 2024-12-01 | YoCrew          | W   | 0.591      | 0.310        | 0.001 (0.000)    | 0.029 (0.005)    | 0 (0.000) |     6.15 | HeaveN, icyvlone, malinov, rexxie, rikon |
|            5 |     2852 | 2024-11-23 | Flame Sharks    | L   | 0.539      | -            | -                | -                | -         |    -8.42 | fate, icyvlone, malinov, rexxie, rikon   |
|            4 |     3688 | 2024-11-10 | Nuclear TigeRES | L   | 0.450      | -            | -                | -                | -         |    -3.68 | fate, HeaveN, icyvlone, rexxie, rikon    |
|            3 |     3691 | 2024-11-10 | Aviators        | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.75 | fate, HeaveN, icyvlone, rexxie, rikon    |
|            2 |     3756 | 2024-11-09 | Nuclear TigeRES | L   | 0.443      | -            | -                | -                | -         |    -3.64 | fate, HeaveN, icyvlone, rexxie, rikon    |
|            1 |     4031 | 2024-11-04 | K27             | L   | 0.410      | -            | -                | -                | -         |    -2.71 | fate, HeaveN, icyvlone, rexxie, rikon    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,371.11)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.686 | $2,000.00      | $1,371.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
