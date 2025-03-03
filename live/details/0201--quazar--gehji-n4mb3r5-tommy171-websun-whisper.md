### Roster Details<br />
Team Name: QUAZAR<br />
Roster: gehji, N4mb3r5, tommy171, WebSun, whisper<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [144]( ../standings_europe.md)<br />
<br />
Final Rank Value:  711.4<br />
<br />
Final Rank Value (711.4) = Starting Rank Value (705.3) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.3
- 400 + ( ( 0.153 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 705.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      339 | 2025-02-16 | OG                    | L   | 1.000      | -            | -                | -                | -         |    -7.43 | gehji, N4mb3r5, tommy171, WebSun, whisper   |
|           36 |      477 | 2025-02-14 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |    -6.36 | gehji, N4mb3r5, tommy171, WebSun, whisper   |
|           35 |     1641 | 2024-12-15 | Premdesant            | L   | 0.684      | -            | -                | -                | -         |   -12.17 | desl3bio, gehji, N4mb3r5, tommy171, whisper |
|           34 |     1717 | 2024-12-14 | Playfire              | W   | 0.677      | -            | -                | -                | 0 (0.000) |     5.00 | desl3bio, gehji, N4mb3r5, tommy171, whisper |
|           33 |     2977 | 2024-11-22 | Partizan Esports      | L   | 0.531      | -            | -                | -                | -         |    -2.20 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           32 |     3096 | 2024-11-20 | Lazer Cats            | L   | 0.519      | -            | -                | -                | -         |    -7.48 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           31 |     3122 | 2024-11-20 | MOUZ NXT              | W   | 0.518      | 0.372        | -                | 0.183 (0.035)    | 0 (0.000) |     5.34 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           30 |     3137 | 2024-11-20 | Team Spirit Academy   | L   | 0.518      | -            | -                | -                | -         |    -3.83 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           29 |     3340 | 2024-11-16 | FLuffy Gangsters      | W   | 0.491      | 0.143        | 0.014 (0.001)    | 0.909 (0.064)    | 0 (0.000) |     9.64 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           28 |     3354 | 2024-11-16 | Premdesant            | L   | 0.490      | -            | -                | -                | -         |    -9.32 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           27 |     3363 | 2024-11-16 | Nuclear TigeRES       | W   | 0.489      | 0.143        | 0.004 (0.000)    | 0.580 (0.041)    | 0 (0.000) |    10.00 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           26 |     3446 | 2024-11-14 | Underrated            | W   | 0.478      | 0.372        | 0.002 (0.000)    | 0.268 (0.048)    | 0 (0.000) |     6.47 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           25 |     3630 | 2024-11-11 | BC.Game Esports       | L   | 0.457      | -            | -                | -                | -         |    -5.13 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           24 |     3854 | 2024-11-07 | Poslednii3ae3d        | W   | 0.431      | 0.372        | -                | 0.101 (0.016)    | 0 (0.000) |     4.68 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           23 |     3895 | 2024-11-06 | KONO.ECF              | L   | 0.425      | -            | -                | -                | -         |    -3.67 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           22 |     3952 | 2024-11-05 | TEAM NEXT LEVEL       | W   | 0.418      | 0.372        | 0.040 (0.006)    | 0.500 (0.078)    | 0 (0.000) |     8.78 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           21 |     4263 | 2024-10-31 | 1win                  | L   | 0.384      | -            | -                | -                | -         |    -5.54 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           20 |     4389 | 2024-10-29 | UNiTY esports         | L   | 0.371      | -            | -                | -                | -         |    -4.15 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           19 |     4662 | 2024-10-23 | LEON Esports          | W   | 0.332      | 0.143        | 0.010 (0.000)    | -                | 0 (0.000) |     5.82 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           18 |     4734 | 2024-10-21 | CYBERSHOKE Esports    | W   | 0.318      | 0.143        | 0.011 (0.001)    | 1.000 (0.045)    | 0 (0.000) |     6.71 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           17 |     4935 | 2024-10-17 | Permitta Esports      | W   | 0.291      | 0.372        | 0.013 (0.001)    | 0.487 (0.053)    | 0 (0.000) |     5.62 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           16 |     5083 | 2024-10-15 | ALTERNATE aTTaX       | W   | 0.277      | 0.372        | 0.021 (0.002)    | 0.552 (0.057)    | -         |     6.67 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           15 |     5117 | 2024-10-14 | THE SPELLS            | L   | 0.271      | -            | -                | -                | -         |    -6.18 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           14 |     5160 | 2024-10-13 | Nuclear TigeRES       | W   | 0.263      | 0.143        | 0.004 (0.000)    | 0.580 (0.022)    | -         |     5.47 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           13 |     5169 | 2024-10-13 | XP Ansuz              | W   | 0.263      | -            | -                | -                | -         |     1.28 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           12 |     6610 | 2024-09-21 | Rhyno Esports         | L   | 0.116      | -            | -                | -                | -         |    -1.98 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           11 |     6696 | 2024-09-19 | THE GENTLEMEN ESPORTS | L   | 0.105      | -            | -                | -                | -         |    -1.72 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|           10 |     6758 | 2024-09-18 | Lazer Cats            | L   | 0.098      | -            | -                | -                | -         |    -1.49 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            9 |     6777 | 2024-09-18 | Team Space            | L   | 0.097      | -            | -                | -                | -         |    -2.37 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            8 |     6867 | 2024-09-17 | ENCE Academy          | W   | 0.089      | -            | -                | -                | -         |     1.81 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            7 |     6885 | 2024-09-16 | Flame Sharks          | W   | 0.085      | -            | -                | -                | -         |     1.12 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            6 |     6996 | 2024-09-14 | Nexus Gaming          | L   | 0.071      | -            | -                | -                | -         |    -0.14 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            5 |     7106 | 2024-09-13 | Kubix Esports         | W   | 0.063      | 0.333        | 0.045 (0.001)    | -                | -         |     1.56 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            4 |     7263 | 2024-09-10 | TALON                 | W   | 0.044      | -            | -                | -                | -         |     0.42 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            3 |     7289 | 2024-09-09 | Rejected by all       | W   | 0.038      | -            | -                | -                | -         |     0.25 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            2 |     7324 | 2024-09-09 | Rhyno Esports         | W   | 0.036      | -            | -                | -                | -         |     0.52 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |
|            1 |     7592 | 2024-09-05 | Kronjyllands Esport   | W   | 0.012      | -            | -                | -                | -         |     0.06 | gehji, Muk0s, N4mb3r5, tommy171, whisper    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,791.03)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $1,452.65      | $993.65         |
| 2024-11-03 |      0.405 | $1,532.61      | $620.92         |
| 2024-09-21 |      0.118 | $1,500.00      | $176.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
