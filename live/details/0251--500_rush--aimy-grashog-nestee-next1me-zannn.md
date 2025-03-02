### Roster Details<br />
Team Name: 500 Rush<br />
Roster: aimy, Grashog, nestee, next1me, zaNNN<br />
Global Rank: [251](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [175]( ../standings_europe.md)<br />
<br />
Final Rank Value:  677.5<br />
<br />
Final Rank Value (677.5) = Starting Rank Value (645.1) + Head To Head Adjustments (32.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.1
- 400 + ( ( 0.123 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 645.1


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
|           21 |     2441 | 2024-12-01 | DEPO                  | L   | 0.598      | -            | -                | -                | -         |    -6.71 | aimy, Grashog, nestee, next1me, zaNNN |
|           20 |     2548 | 2024-11-30 | Ins (Polish team)     | W   | 0.591      | 0.284        | 0.004 (0.001)    | 0.280 (0.047)    | 0 (0.000) |     9.81 | aimy, Grashog, nestee, next1me, zaNNN |
|           19 |     2656 | 2024-11-27 | Hypewrld              | W   | 0.574      | 0.284        | 0.002 (0.000)    | 0.187 (0.030)    | 0 (0.000) |    10.80 | aimy, Grashog, nestee, next1me, zaNNN |
|           18 |     3372 | 2024-11-15 | EC BANGA              | W   | 0.494      | 0.284        | 0.001 (0.000)    | 0.097 (0.014)    | 0 (0.000) |     4.94 | aimy, Grashog, nestee, next1me, zaNNN |
|           17 |     3381 | 2024-11-15 | Viperio               | W   | 0.493      | 0.284        | 0.002 (0.000)    | 0.411 (0.057)    | 0 (0.000) |     9.65 | aimy, Grashog, nestee, next1me, zaNNN |
|           16 |     5227 | 2024-10-12 | Nuclear TigeRES       | L   | 0.265      | -            | -                | -                | -         |    -2.29 | aimy, Grashog, nestee, next1me, zaNNN |
|           15 |     5249 | 2024-10-11 | Ins (Polish team)     | L   | 0.260      | -            | -                | -                | -         |    -3.84 | aimy, Grashog, nestee, next1me, zaNNN |
|           14 |     5275 | 2024-10-10 | Los kogutos           | L   | 0.253      | -            | -                | -                | -         |    -1.11 | aimy, Grashog, nestee, next1me, zaNNN |
|           13 |     5286 | 2024-10-10 | GameAgents            | W   | 0.252      | 0.143        | 0.003 (0.000)    | 0.119 (0.004)    | 0 (0.000) |     4.62 | aimy, Grashog, nestee, next1me, zaNNN |
|           12 |     6565 | 2024-09-21 | FORTIS (Russian team) | W   | 0.127      | 0.310        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.74 | aimy, Grashog, nestee, next1me, zaNNN |
|           11 |     6622 | 2024-09-20 | NoLightGaming         | W   | 0.120      | 0.310        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.65 | aimy, Grashog, nestee, next1me, zaNNN |
|           10 |     6685 | 2024-09-19 | DEPO                  | W   | 0.113      | 0.310        | 0.006 (0.000)    | 0.297 (0.010)    | 0 (0.000) |     2.42 | aimy, Grashog, nestee, next1me, zaNNN |
|            9 |     6748 | 2024-09-18 | QuitGoats             | W   | 0.107      | 0.310        | 0.000 (0.000)    | -                | 0 (0.000) |     1.04 | aimy, Grashog, nestee, next1me, zaNNN |
|            8 |     6821 | 2024-09-17 | FORZE Youngsters      | W   | 0.100      | -            | -                | -                | 0 (0.000) |     0.98 | aimy, Grashog, nestee, next1me, zaNNN |
|            7 |     6887 | 2024-09-16 | Modern Players        | W   | 0.093      | -            | -                | -                | -         |     0.60 | aimy, Grashog, nestee, next1me, zaNNN |
|            6 |     7019 | 2024-09-14 | NewBALLS              | L   | 0.078      | -            | -                | -                | -         |    -1.18 | aimy, Grashog, nestee, next1me, zaNNN |
|            5 |     7176 | 2024-09-11 | DEPO                  | L   | 0.060      | -            | -                | -                | -         |    -0.61 | aimy, Grashog, nestee, next1me, zaNNN |
|            4 |     7232 | 2024-09-10 | Devils.one            | L   | 0.053      | -            | -                | -                | -         |    -0.83 | aimy, Grashog, nestee, next1me, zaNNN |
|            3 |     7446 | 2024-09-07 | Soul's Heart Esport   | W   | 0.032      | 0.143        | -                | 0.114 (0.001)    | -         |     0.35 | aimy, Grashog, nestee, next1me, zaNNN |
|            2 |     7457 | 2024-09-07 | Illuminar Gaming      | L   | 0.031      | -            | -                | -                | -         |    -0.22 | aimy, Grashog, nestee, next1me, zaNNN |
|            1 |     7481 | 2024-09-07 | Lazer Cats            | W   | 0.030      | 0.143        | 0.005 (0.000)    | 0.387 (0.002)    | -         |     0.58 | aimy, Grashog, nestee, next1me, zaNNN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($552.03)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-01 |      0.598 | $500.00        | $298.97         |
| 2024-09-21 |      0.127 | $2,000.00      | $253.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
