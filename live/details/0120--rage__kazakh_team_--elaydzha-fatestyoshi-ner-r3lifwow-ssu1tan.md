### Roster Details<br />
Team Name: RAGE (Kazakh team)<br />
Roster: ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN<br />
Global Rank: [120](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
<br />
Final Rank Value:  798.0<br />
<br />
Final Rank Value (798.0) = Starting Rank Value (826.6) + Head To Head Adjustments (-28.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 826.6
- 400 + ( ( 0.214 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 826.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2392 | 2024-12-01 | AK BARS             | L   | 0.601      | -            | -                | -                | -         |    -8.78 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|           15 |     2400 | 2024-12-01 | AimAssassins        | L   | 0.600      | -            | -                | -                | -         |    -6.22 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|           14 |     2429 | 2024-12-01 | PUGSTAR5            | W   | 0.599      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.71 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|           13 |     2500 | 2024-11-30 | HellaSlayers99      | L   | 0.593      | -            | -                | -                | -         |   -14.70 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|           12 |     2780 | 2024-11-24 | Delta (Kazakh team) | W   | 0.553      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 1 (0.553) |     5.38 | Adams0n, ElayDzha, ner, R3LiFwOw, ssu1taN        |
|           11 |     2796 | 2024-11-24 | N1 (Kazakh team)    | W   | 0.552      | 0.143        | 0.001 (0.000)    | 0.026 (0.002)    | 1 (0.552) |     4.85 | Adams0n, ElayDzha, ner, R3LiFwOw, ssu1taN        |
|           10 |     2805 | 2024-11-24 | RONIN (Kazakh team) | W   | 0.551      | 0.143        | 0.000 (0.000)    | 0.051 (0.004)    | 1 (0.551) |     2.29 | Adams0n, ElayDzha, ner, R3LiFwOw, ssu1taN        |
|            9 |     2807 | 2024-11-24 | Venom cyber         | W   | 0.551      | 0.143        | 0.000 (0.000)    | 0.026 (0.002)    | 1 (0.551) |     1.91 | Adams0n, ElayDzha, ner, R3LiFwOw, ssu1taN        |
|            8 |     2858 | 2024-11-23 | N1 (Kazakh team)    | L   | 0.547      | -            | -                | -                | -         |   -12.47 | Adams0n, ElayDzha, ner, R3LiFwOw, ssu1taN        |
|            7 |     3800 | 2024-11-08 | DEPO                | L   | 0.446      | -            | -                | -                | -         |    -8.17 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|            6 |     3849 | 2024-11-07 | MYSKILL             | W   | 0.439      | 0.143        | 0.002 (0.000)    | 0.129 (0.008)    | 0 (0.000) |     4.02 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|            5 |     4004 | 2024-11-04 | Brodyagi            | W   | 0.419      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.10 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|            4 |     4063 | 2024-11-03 | ALLINNERS           | L   | 0.412      | -            | -                | -                | -         |    -8.74 | ElayDzha, fatestyoshi, ner, R3LiFwOw, ssu1taN    |
|            3 |     5536 | 2024-10-06 | AK BARS             | W   | 0.224      | 0.333        | 0.008 (0.001)    | 0.212 (0.016)    | 1 (0.224) |     3.64 | ElayDzha, fatestyoshi, for2na, R3LiFwOw, ssu1taN |
|            2 |     5617 | 2024-10-05 | MYSKILL             | W   | 0.218      | 0.333        | 0.002 (0.000)    | 0.129 (0.009)    | 1 (0.218) |     2.03 | ElayDzha, fatestyoshi, for2na, R3LiFwOw, ssu1taN |
|            1 |     5630 | 2024-10-04 | AK BARS             | W   | 0.217      | 0.333        | 0.008 (0.001)    | 0.212 (0.015)    | 1 (0.217) |     3.55 | ElayDzha, fatestyoshi, for2na, R3LiFwOw, ssu1taN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,755.21)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.553 | $1,001.64      | $554.20         |
| 2024-11-09 |      0.453 | $174.01        | $78.79          |
| 2024-10-06 |      0.224 | $5,000.00      | $1,122.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
