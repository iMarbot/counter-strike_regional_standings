### Roster Details<br />
Team Name: 500 Rush<br />
Roster: aimy, Grashog, nestee, next1me, zaNNN<br />
Global Rank: [256](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [176]( ../standings_europe.md)<br />
<br />
Final Rank Value:  676.1<br />
<br />
Final Rank Value (676.1) = Starting Rank Value (644.6) + Head To Head Adjustments (31.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 644.6
- 400 + ( ( 0.122 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 644.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2453 | 2024-12-01 | DEPO                  | L   | 0.590      | -            | -                | -                | -         |    -6.66 | aimy, Grashog, nestee, next1me, zaNNN |
|           20 |     2560 | 2024-11-30 | Ins (Polish team)     | W   | 0.583      | 0.284        | 0.004 (0.001)    | 0.274 (0.045)    | 0 (0.000) |     9.70 | aimy, Grashog, nestee, next1me, zaNNN |
|           19 |     2668 | 2024-11-27 | Hypewrld              | W   | 0.566      | 0.284        | 0.002 (0.000)    | 0.185 (0.030)    | 0 (0.000) |    10.67 | aimy, Grashog, nestee, next1me, zaNNN |
|           18 |     3384 | 2024-11-15 | EC BANGA              | W   | 0.485      | 0.284        | 0.001 (0.000)    | 0.096 (0.013)    | 0 (0.000) |     4.88 | aimy, Grashog, nestee, next1me, zaNNN |
|           17 |     3393 | 2024-11-15 | Viperio               | W   | 0.485      | 0.284        | 0.002 (0.000)    | 0.404 (0.056)    | 0 (0.000) |     9.45 | aimy, Grashog, nestee, next1me, zaNNN |
|           16 |     5239 | 2024-10-12 | Nuclear TigeRES       | L   | 0.257      | -            | -                | -                | -         |    -2.20 | aimy, Grashog, nestee, next1me, zaNNN |
|           15 |     5261 | 2024-10-11 | Ins (Polish team)     | L   | 0.252      | -            | -                | -                | -         |    -3.71 | aimy, Grashog, nestee, next1me, zaNNN |
|           14 |     5287 | 2024-10-10 | Los kogutos           | L   | 0.245      | -            | -                | -                | -         |    -1.09 | aimy, Grashog, nestee, next1me, zaNNN |
|           13 |     5298 | 2024-10-10 | GameAgents            | W   | 0.244      | 0.143        | 0.003 (0.000)    | 0.111 (0.004)    | 0 (0.000) |     4.44 | aimy, Grashog, nestee, next1me, zaNNN |
|           12 |     6577 | 2024-09-21 | FORTIS (Russian team) | W   | 0.118      | 0.310        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.63 | aimy, Grashog, nestee, next1me, zaNNN |
|           11 |     6634 | 2024-09-20 | NoLightGaming         | W   | 0.112      | 0.310        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.53 | aimy, Grashog, nestee, next1me, zaNNN |
|           10 |     6697 | 2024-09-19 | DEPO                  | W   | 0.105      | 0.310        | 0.006 (0.000)    | 0.291 (0.009)    | 0 (0.000) |     2.23 | aimy, Grashog, nestee, next1me, zaNNN |
|            9 |     6760 | 2024-09-18 | QuitGoats             | W   | 0.098      | 0.310        | 0.000 (0.000)    | -                | 0 (0.000) |     0.96 | aimy, Grashog, nestee, next1me, zaNNN |
|            8 |     6833 | 2024-09-17 | FORZE Youngsters      | W   | 0.092      | -            | -                | -                | 0 (0.000) |     0.90 | aimy, Grashog, nestee, next1me, zaNNN |
|            7 |     6899 | 2024-09-16 | Modern Players        | W   | 0.085      | -            | -                | -                | -         |     0.55 | aimy, Grashog, nestee, next1me, zaNNN |
|            6 |     7031 | 2024-09-14 | NewBALLS              | L   | 0.070      | -            | -                | -                | -         |    -1.05 | aimy, Grashog, nestee, next1me, zaNNN |
|            5 |     7188 | 2024-09-11 | DEPO                  | L   | 0.052      | -            | -                | -                | -         |    -0.53 | aimy, Grashog, nestee, next1me, zaNNN |
|            4 |     7244 | 2024-09-10 | Devils.one            | L   | 0.045      | -            | -                | -                | -         |    -0.70 | aimy, Grashog, nestee, next1me, zaNNN |
|            3 |     7458 | 2024-09-07 | Soul's Heart Esport   | W   | 0.023      | 0.143        | -                | 0.112 (0.000)    | -         |     0.26 | aimy, Grashog, nestee, next1me, zaNNN |
|            2 |     7469 | 2024-09-07 | Illuminar Gaming      | L   | 0.023      | -            | -                | -                | -         |    -0.17 | aimy, Grashog, nestee, next1me, zaNNN |
|            1 |     7493 | 2024-09-07 | Lazer Cats            | W   | 0.022      | 0.143        | 0.005 (0.000)    | 0.378 (0.001)    | -         |     0.42 | aimy, Grashog, nestee, next1me, zaNNN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($531.54)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-01 |      0.590 | $500.00        | $294.87         |
| 2024-09-21 |      0.118 | $2,000.00      | $236.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
