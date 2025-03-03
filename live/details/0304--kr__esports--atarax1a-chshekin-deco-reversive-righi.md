### Roster Details<br />
Team Name: KRÜ Esports<br />
Roster: atarax1a, chshekin, deco, reversive, righi<br />
Global Rank: [304](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [61]( ../standings_americas.md)<br />
<br />
Final Rank Value:  647.4<br />
<br />
Final Rank Value (647.4) = Starting Rank Value (692.4) + Head To Head Adjustments (-45.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.4
- 400 + ( ( 0.146 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 692.4


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
|           24 |      403 | 2025-02-15 | Game Hunters           | L   | 1.000      | -            | -                | -                | -         |   -14.92 | atarax1a, chshekin, deco, reversive, righi |
|           23 |      486 | 2025-02-14 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -11.69 | atarax1a, chshekin, deco, reversive, righi |
|           22 |      540 | 2025-02-12 | UNO MILLE              | L   | 1.000      | -            | -                | -                | -         |   -11.99 | atarax1a, chshekin, deco, reversive, righi |
|           21 |      625 | 2025-02-09 | Atrix Esports          | W   | 1.000      | 0.371        | 0.005 (0.002)    | 0.211 (0.078)    | 0 (0.000) |    15.84 | atarax1a, chshekin, deco, reversive, righi |
|           20 |      675 | 2025-02-08 | Imperial Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.84 | atarax1a, chshekin, deco, reversive, righi |
|           19 |      756 | 2025-02-07 | PaiN Gaming Academy    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.219 (0.031)    | 0 (0.000) |     9.38 | atarax1a, chshekin, deco, reversive, righi |
|           18 |      850 | 2025-02-06 | Fake do Biru           | L   | 1.000      | -            | -                | -                | -         |   -17.62 | atarax1a, chshekin, deco, reversive, righi |
|           17 |      906 | 2025-02-05 | AdalYamigos            | L   | 1.000      | -            | -                | -                | -         |   -14.10 | atarax1a, chshekin, deco, reversive, righi |
|           16 |     3490 | 2024-11-13 | Imperial Esports       | L   | 0.475      | -            | -                | -                | -         |    -2.45 | atarax1a, deco, laser, reversive, righi    |
|           15 |     3536 | 2024-11-12 | Nouns Esports          | W   | 0.468      | 0.143        | 0.005 (0.000)    | 0.094 (0.006)    | 1 (0.468) |     8.47 | atarax1a, deco, laser, reversive, righi    |
|           14 |     3560 | 2024-11-12 | Team Liquid            | L   | 0.464      | -            | -                | -                | -         |    -0.15 | atarax1a, deco, laser, reversive, righi    |
|           13 |     3584 | 2024-11-11 | MIBR                   | L   | 0.462      | -            | -                | -                | -         |    -0.28 | atarax1a, deco, laser, reversive, righi    |
|           12 |     5049 | 2024-10-15 | ODDIK                  | L   | 0.279      | -            | -                | -                | -         |    -2.87 | atarax1a, deco, laser, reversive, righi    |
|           11 |     5332 | 2024-10-09 | BESTIA                 | L   | 0.240      | -            | -                | -                | -         |    -1.57 | atarax1a, deco, laser, reversive, righi    |
|           10 |     5340 | 2024-10-09 | BESTIA                 | L   | 0.239      | -            | -                | -                | -         |    -1.59 | atarax1a, deco, laser, reversive, righi    |
|            9 |     5398 | 2024-10-08 | MIBR                   | L   | 0.233      | -            | -                | -                | -         |    -0.13 | atarax1a, deco, laser, reversive, righi    |
|            8 |     5409 | 2024-10-08 | MIBR                   | L   | 0.233      | -            | -                | -                | -         |    -0.13 | atarax1a, deco, laser, reversive, righi    |
|            7 |     5757 | 2024-10-02 | Dusty Roots            | W   | 0.193      | 0.450        | 0.009 (0.001)    | 0.366 (0.032)    | 0 (0.000) |     3.83 | atarax1a, deco, laser, reversive, righi    |
|            6 |     5763 | 2024-10-02 | Dusty Roots            | L   | 0.193      | -            | -                | -                | -         |    -2.27 | atarax1a, deco, laser, reversive, righi    |
|            5 |     6114 | 2024-09-27 | Patins da Ferrari      | L   | 0.159      | -            | -                | -                | -         |    -3.72 | atarax1a, deco, laser, reversive, righi    |
|            4 |     6357 | 2024-09-24 | Fluxo                  | W   | 0.140      | 0.450        | 0.056 (0.003)    | 0.423 (0.027)    | 0 (0.000) |     3.43 | atarax1a, deco, laser, reversive, righi    |
|            3 |     6363 | 2024-09-24 | Fluxo                  | W   | 0.139      | 0.450        | 0.056 (0.003)    | 0.423 (0.027)    | 0 (0.000) |     3.45 | atarax1a, deco, laser, reversive, righi    |
|            2 |     6682 | 2024-09-19 | PaiN Gaming            | L   | 0.106      | -            | -                | -                | -         |    -0.01 | atarax1a, deco, laser, reversive, righi    |
|            1 |     6685 | 2024-09-19 | PaiN Gaming            | L   | 0.106      | -            | -                | -                | -         |    -0.01 | atarax1a, deco, laser, reversive, righi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($467.92)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.312 | $1,500.00      | $467.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
