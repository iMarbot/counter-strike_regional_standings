### Roster Details<br />
Team Name: Adventurers<br />
Roster: hAdji, k1to, meztal, OWNER, Woro2k<br />
Global Rank: [154](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
<br />
Final Rank Value:  757.5<br />
<br />
Final Rank Value (757.5) = Starting Rank Value (781.7) + Head To Head Adjustments (-24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.054[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 781.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      231 | 2025-02-20 | VOLT (European team)  | L   | 1.000      | -            | -                | -                | -         |   -25.25 | hAdji, maxster, OWNER, Svedjehed, Woro2k  |
|           29 |      911 | 2025-02-05 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -10.94 | hAdji, k1to, meztal, OWNER, Woro2k        |
|           28 |      951 | 2025-02-04 | KONO.ECF              | L   | 1.000      | -            | -                | -                | -         |   -21.44 | hAdji, k1to, meztal, OWNER, Woro2k        |
|           27 |     1123 | 2025-01-27 | Zero Tenacity         | L   | 0.979      | -            | -                | -                | -         |   -12.81 | adamS, hAdji, juanflatroo, meztal, Woro2k |
|           26 |     3528 | 2024-11-12 | FlyQuest              | L   | 0.476      | -            | -                | -                | -         |    -2.70 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           25 |     3571 | 2024-11-12 | The MongolZ           | L   | 0.471      | -            | -                | -                | -         |    -0.03 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           24 |     3627 | 2024-11-11 | Lynn Vision Gaming    | W   | 0.464      | -            | -                | -                | 1 (0.464) |     8.01 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           23 |     3946 | 2024-11-05 | Monte                 | L   | 0.426      | -            | -                | -                | -         |    -5.16 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           22 |     4003 | 2024-11-04 | Preasy Esport         | W   | 0.419      | 0.333        | -                | 0.710 (0.099)    | 0 (0.000) |     5.96 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           21 |     4053 | 2024-11-03 | GODSENT               | W   | 0.413      | -            | -                | -                | 0 (0.000) |     4.17 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           20 |     4530 | 2024-10-26 | Leo Team              | W   | 0.358      | 0.333        | 0.026 (0.003)    | 0.758 (0.091)    | 0 (0.000) |     6.01 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           19 |     4607 | 2024-10-25 | Natus Vincere Junior  | L   | 0.351      | -            | -                | -                | -         |    -3.13 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           18 |     4747 | 2024-10-21 | Leo Team              | W   | 0.325      | 0.333        | 0.026 (0.003)    | 0.758 (0.082)    | 0 (0.000) |     5.47 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           17 |     4895 | 2024-10-18 | Monte                 | W   | 0.306      | 0.333        | 0.045 (0.005)    | 0.704 (0.072)    | 0 (0.000) |     6.28 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           16 |     4947 | 2024-10-17 | TEAM NEXT LEVEL       | W   | 0.298      | 0.333        | 0.039 (0.004)    | 0.508 (0.050)    | 0 (0.000) |     5.38 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           15 |     4956 | 2024-10-17 | Ex-9INE Academy       | W   | 0.297      | -            | -                | -                | 0 (0.000) |     2.30 | hAdji, Kvem, meztal, SENER1, Woro2k       |
|           14 |     5424 | 2024-10-08 | Monte                 | W   | 0.239      | 0.354        | 0.045 (0.004)    | 0.704 (0.060)    | 0 (0.000) |     4.99 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           13 |     5474 | 2024-10-07 | FAVBET Team           | W   | 0.233      | 0.354        | 0.032 (0.003)    | 0.814 (0.067)    | 0 (0.000) |     4.18 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           12 |     5508 | 2024-10-06 | GamerLegion Academy   | W   | 0.227      | -            | -                | -                | -         |     1.46 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           11 |     5521 | 2024-10-06 | GODSENT               | W   | 0.226      | -            | -                | -                | -         |     2.48 | hAdji, Kvem, meztal, nifee, Woro2k        |
|           10 |     5534 | 2024-10-06 | FAVBET Team           | L   | 0.225      | -            | -                | -                | -         |    -3.09 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            9 |     5611 | 2024-10-05 | Monte                 | L   | 0.218      | -            | -                | -                | -         |    -2.78 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            8 |     5657 | 2024-10-04 | GamerLegion           | L   | 0.213      | -            | -                | -                | -         |    -0.08 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            7 |     5803 | 2024-10-02 | Los kogutos           | W   | 0.197      | 0.435        | 0.032 (0.003)    | 0.527 (0.045)    | -         |     4.74 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            6 |     5914 | 2024-09-30 | ALTERNATE aTTaX       | W   | 0.186      | 0.435        | 0.021 (0.002)    | 0.564 (0.046)    | -         |     4.06 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            5 |     5928 | 2024-09-30 | TSM                   | L   | 0.185      | -            | -                | -                | -         |    -3.12 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            4 |     6041 | 2024-09-28 | Team Spirit Academy   | L   | 0.172      | -            | -                | -                | -         |    -1.68 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            3 |     6217 | 2024-09-26 | FAVBET Team           | W   | 0.158      | 0.435        | 0.032 (0.002)    | 0.814 (0.056)    | -         |     2.89 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            2 |     6274 | 2024-09-25 | RUSTEC                | L   | 0.154      | -            | -                | -                | -         |    -4.05 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |
|            1 |     6388 | 2024-09-24 | Passion UA            | W   | 0.146      | 0.435        | 0.044 (0.003)    | -                | -         |     3.68 | AMSALEM, hAdji, Kvem, meztal, Woro2k      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,553.33)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.426 | $3,000.00      | $1,278.33       |
| 2024-10-26 |      0.358 | $3,000.00      | $1,075.00       |
| 2024-10-18 |      0.306 | $5,000.00      | $1,527.78       |
| 2024-10-08 |      0.239 | $7,000.00      | $1,672.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
