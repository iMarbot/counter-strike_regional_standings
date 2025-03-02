### Roster Details<br />
Team Name: KRÜ Esports<br />
Roster: atarax1a, chshekin, deco, reversive, righi<br />
Global Rank: [300](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  648.7<br />
<br />
Final Rank Value (648.7) = Starting Rank Value (693.4) + Head To Head Adjustments (-44.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.4
- 400 + ( ( 0.147 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 693.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      391 | 2025-02-15 | Game Hunters           | L   | 1.000      | -            | -                | -                | -         |   -14.94 | atarax1a, chshekin, deco, reversive, righi |
|           23 |      474 | 2025-02-14 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -11.72 | atarax1a, chshekin, deco, reversive, righi |
|           22 |      528 | 2025-02-12 | UNO MILLE              | L   | 1.000      | -            | -                | -                | -         |   -11.98 | atarax1a, chshekin, deco, reversive, righi |
|           21 |      613 | 2025-02-09 | Atrix Esports          | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.215 (0.080)    | 0 (0.000) |    15.78 | atarax1a, chshekin, deco, reversive, righi |
|           20 |      663 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.80 | atarax1a, chshekin, deco, reversive, righi |
|           19 |      744 | 2025-02-07 | PaiN Gaming Academy    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.221 (0.032)    | 0 (0.000) |     9.50 | atarax1a, chshekin, deco, reversive, righi |
|           18 |      838 | 2025-02-06 | Fake do Biru           | L   | 1.000      | -            | -                | -                | -         |   -17.63 | atarax1a, chshekin, deco, reversive, righi |
|           17 |      894 | 2025-02-05 | AdalYamigos            | L   | 1.000      | -            | -                | -                | -         |   -14.12 | atarax1a, chshekin, deco, reversive, righi |
|           16 |     3478 | 2024-11-13 | Imperial Esports       | L   | 0.484      | -            | -                | -                | -         |    -2.47 | atarax1a, deco, laser, reversive, righi    |
|           15 |     3524 | 2024-11-12 | Nouns Esports          | W   | 0.477      | 0.143        | 0.006 (0.000)    | 0.099 (0.007)    | 1 (0.477) |     8.60 | atarax1a, deco, laser, reversive, righi    |
|           14 |     3548 | 2024-11-12 | Team Liquid            | L   | 0.472      | -            | -                | -                | -         |    -0.15 | atarax1a, deco, laser, reversive, righi    |
|           13 |     3572 | 2024-11-11 | MIBR                   | L   | 0.471      | -            | -                | -                | -         |    -0.29 | atarax1a, deco, laser, reversive, righi    |
|           12 |     5037 | 2024-10-15 | ODDIK                  | L   | 0.287      | -            | -                | -                | -         |    -2.96 | atarax1a, deco, laser, reversive, righi    |
|           11 |     5320 | 2024-10-09 | BESTIA                 | L   | 0.248      | -            | -                | -                | -         |    -1.61 | atarax1a, deco, laser, reversive, righi    |
|           10 |     5328 | 2024-10-09 | BESTIA                 | L   | 0.247      | -            | -                | -                | -         |    -1.63 | atarax1a, deco, laser, reversive, righi    |
|            9 |     5386 | 2024-10-08 | MIBR                   | L   | 0.241      | -            | -                | -                | -         |    -0.13 | atarax1a, deco, laser, reversive, righi    |
|            8 |     5397 | 2024-10-08 | MIBR                   | L   | 0.241      | -            | -                | -                | -         |    -0.13 | atarax1a, deco, laser, reversive, righi    |
|            7 |     5745 | 2024-10-02 | Dusty Roots            | W   | 0.201      | 0.450        | 0.008 (0.001)    | 0.371 (0.034)    | 0 (0.000) |     3.99 | atarax1a, deco, laser, reversive, righi    |
|            6 |     5751 | 2024-10-02 | Dusty Roots            | L   | 0.201      | -            | -                | -                | -         |    -2.37 | atarax1a, deco, laser, reversive, righi    |
|            5 |     6102 | 2024-09-27 | Patins da Ferrari      | L   | 0.167      | -            | -                | -                | -         |    -3.91 | atarax1a, deco, laser, reversive, righi    |
|            4 |     6345 | 2024-09-24 | Fluxo                  | W   | 0.148      | 0.450        | 0.056 (0.004)    | 0.430 (0.029)    | 0 (0.000) |     3.63 | atarax1a, deco, laser, reversive, righi    |
|            3 |     6351 | 2024-09-24 | Fluxo                  | W   | 0.147      | 0.450        | 0.056 (0.004)    | 0.430 (0.029)    | 0 (0.000) |     3.65 | atarax1a, deco, laser, reversive, righi    |
|            2 |     6670 | 2024-09-19 | PaiN Gaming            | L   | 0.114      | -            | -                | -                | -         |    -0.02 | atarax1a, deco, laser, reversive, righi    |
|            1 |     6673 | 2024-09-19 | PaiN Gaming            | L   | 0.114      | -            | -                | -                | -         |    -0.02 | atarax1a, deco, laser, reversive, righi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($480.21)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.320 | $1,500.00      | $480.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
