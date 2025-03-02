### Roster Details<br />
Team Name: Victores Sumus<br />
Roster: arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster<br />
Global Rank: [249](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [31]( ../standings_asia.md)<br />
<br />
Final Rank Value:  679.3<br />
<br />
Final Rank Value (679.3) = Starting Rank Value (778.4) + Head To Head Adjustments (-99.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.233[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.4
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 778.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |        3 | 2025-03-01 | Gods Reign              | L   | 1.000      | -            | -                | -                | -         |    -8.59 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           20 |        5 | 2025-02-28 | Flashback Gaming        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.141 (0.020)    | 1 (1.000) |    19.10 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           19 |        9 | 2025-02-28 | Big W                   | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.072 (0.010)    | 1 (1.000) |    16.36 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           18 |       15 | 2025-02-27 | Gods Reign              | L   | 1.000      | -            | -                | -                | -         |    -8.38 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           17 |      374 | 2025-02-16 | Nomads (Mongolian team) | L   | 1.000      | -            | -                | -                | -         |   -20.13 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           16 |      858 | 2025-02-06 | SemperFi Esports        | L   | 1.000      | -            | -                | -                | -         |   -19.16 | arakyN, Benzene, ChAmP, p7, Recoilmaster     |
|           15 |     1248 | 2024-12-29 | Red Viperz              | W   | 0.786      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.87 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           14 |     1252 | 2024-12-29 | Flashback Gaming        | L   | 0.786      | -            | -                | -                | -         |    -9.08 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           13 |     1734 | 2024-12-13 | Gods Reign              | L   | 0.683      | -            | -                | -                | -         |    -6.82 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           12 |     2274 | 2024-12-03 | THE (Russian team)      | L   | 0.612      | -            | -                | -                | -         |   -11.35 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           11 |     2293 | 2024-12-03 | Harizma                 | L   | 0.611      | -            | -                | -                | -         |    -9.68 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           10 |     2297 | 2024-12-02 | SUBUTAI                 | W   | 0.610      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.35 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            9 |     2305 | 2024-12-02 | DEWA United             | L   | 0.610      | -            | -                | -                | -         |   -13.47 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            8 |     2900 | 2024-11-23 | Ego accendent           | L   | 0.545      | -            | -                | -                | -         |   -11.23 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            7 |     3333 | 2024-11-16 | Flashback Gaming        | L   | 0.499      | -            | -                | -                | -         |    -7.12 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            6 |     4160 | 2024-11-01 | DEWA United             | L   | 0.403      | -            | -                | -                | -         |    -9.93 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            5 |     6045 | 2024-09-28 | Carnival Gaming         | L   | 0.172      | -            | -                | -                | -         |    -4.51 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            4 |     6064 | 2024-09-28 | Project Lethals         | W   | 0.171      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     0.59 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            3 |     6135 | 2024-09-27 | Gods Reign              | L   | 0.165      | -            | -                | -                | -         |    -1.67 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            2 |     6212 | 2024-09-26 | Firedup Gaming          | W   | 0.159      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     0.54 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            1 |     6540 | 2024-09-21 | St4rboys                | L   | 0.130      | -            | -                | -                | -         |    -2.77 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,099.40)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-01 |      1.000 | $1,717.92      | $1,717.92       |
| 2024-12-29 |      0.786 | $108.90        | $85.64          |
| 2024-11-30 |      0.592 | $500.00        | $295.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
