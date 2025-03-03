### Roster Details<br />
Team Name: Victores Sumus<br />
Roster: arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster<br />
Global Rank: [246](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [30]( ../standings_asia.md)<br />
<br />
Final Rank Value:  681.2<br />
<br />
Final Rank Value (681.2) = Starting Rank Value (779.8) + Head To Head Adjustments (-98.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.234[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 779.8
- 400 + ( ( 0.190 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 779.8


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
|           21 |       18 | 2025-03-01 | Gods Reign              | L   | 1.000      | -            | -                | -                | -         |    -8.61 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           20 |       20 | 2025-02-28 | Flashback Gaming        | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.140 (0.020)    | 1 (1.000) |    19.02 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           19 |       24 | 2025-02-28 | Big W                   | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.071 (0.010)    | 1 (1.000) |    16.27 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           18 |       30 | 2025-02-27 | Gods Reign              | L   | 1.000      | -            | -                | -                | -         |    -8.40 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           17 |      386 | 2025-02-16 | Nomads (Mongolian team) | L   | 1.000      | -            | -                | -                | -         |   -20.22 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           16 |      870 | 2025-02-06 | SemperFi Esports        | L   | 1.000      | -            | -                | -                | -         |   -19.28 | arakyN, Benzene, ChAmP, p7, Recoilmaster     |
|           15 |     1260 | 2024-12-29 | Red Viperz              | W   | 0.778      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.79 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           14 |     1264 | 2024-12-29 | Flashback Gaming        | L   | 0.778      | -            | -                | -                | -         |    -9.06 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           13 |     1746 | 2024-12-13 | Gods Reign              | L   | 0.675      | -            | -                | -                | -         |    -6.74 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           12 |     2286 | 2024-12-03 | THE (Russian team)      | L   | 0.604      | -            | -                | -                | -         |   -11.25 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           11 |     2305 | 2024-12-03 | Harizma                 | L   | 0.602      | -            | -                | -                | -         |    -9.65 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|           10 |     2309 | 2024-12-02 | SUBUTAI                 | W   | 0.602      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.26 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            9 |     2317 | 2024-12-02 | DEWA United             | L   | 0.602      | -            | -                | -                | -         |   -13.38 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            8 |     2912 | 2024-11-23 | Ego accendent           | L   | 0.537      | -            | -                | -                | -         |   -11.10 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            7 |     3345 | 2024-11-16 | Flashback Gaming        | L   | 0.490      | -            | -                | -                | -         |    -7.05 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            6 |     4172 | 2024-11-01 | DEWA United             | L   | 0.395      | -            | -                | -                | -         |    -9.77 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            5 |     6057 | 2024-09-28 | Carnival Gaming         | L   | 0.164      | -            | -                | -                | -         |    -4.31 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            4 |     6076 | 2024-09-28 | Project Lethals         | W   | 0.163      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.56 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            3 |     6147 | 2024-09-27 | Gods Reign              | L   | 0.157      | -            | -                | -                | -         |    -1.59 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            2 |     6224 | 2024-09-26 | Firedup Gaming          | W   | 0.150      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.51 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |
|            1 |     6552 | 2024-09-21 | St4rboys                | L   | 0.121      | -            | -                | -                | -         |    -2.60 | arakyN, Benzene, ChAmP, RaYzeR, Recoilmaster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,094.41)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-01 |      1.000 | $1,717.92      | $1,717.92       |
| 2024-12-29 |      0.778 | $108.90        | $84.75          |
| 2024-11-30 |      0.583 | $500.00        | $291.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
