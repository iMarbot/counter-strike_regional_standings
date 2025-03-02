### Roster Details<br />
Team Name: ROYALS<br />
Roster: Lake, oskvr, shateri, Swaggy, waZz<br />
Global Rank: [277](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [190]( ../standings_europe.md)<br />
<br />
Final Rank Value:  663.0<br />
<br />
Final Rank Value (663.0) = Starting Rank Value (683.4) + Head To Head Adjustments (-20.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.4
- 400 + ( ( 0.142 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 683.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |     1372 | 2024-12-23 | NEVERMORE (Ukrainian team) | L   | 0.746      | -            | -                | -                | -         |    -8.28 | Lake, oskvr, shateri, Swaggy, waZz  |
|           32 |     1417 | 2024-12-22 | SkyFury                    | L   | 0.738      | -            | -                | -                | -         |   -11.64 | jeyN, oskvr, shateri, Swaggy, waZz  |
|           31 |     1526 | 2024-12-19 | VOLT (European team)       | L   | 0.721      | -            | -                | -                | -         |   -11.02 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           30 |     1778 | 2024-12-13 | P0RTUGAL                   | L   | 0.680      | -            | -                | -                | -         |    -7.24 | d1maje, jeyN, shateri, Swaggy, waZz |
|           29 |     1781 | 2024-12-13 | PULSE Esports              | W   | 0.680      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     6.30 | d1maje, jeyN, shateri, Swaggy, waZz |
|           28 |     2350 | 2024-12-02 | NEVERMORE (Ukrainian team) | L   | 0.605      | -            | -                | -                | -         |    -7.72 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           27 |     2442 | 2024-12-01 | SkyFury                    | W   | 0.598      | 0.303        | 0.004 (0.001)    | 0.342 (0.062)    | 0 (0.000) |     9.17 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           26 |     2542 | 2024-11-30 | Fragmatic                  | W   | 0.591      | 0.303        | -                | 0.069 (0.012)    | 0 (0.000) |     6.13 | ERSIN, jeyN, shateri, Swaggy, waZz  |
|           25 |     3540 | 2024-11-12 | ALASKA                     | L   | 0.473      | -            | -                | -                | -         |    -1.81 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           24 |     3662 | 2024-11-10 | Endpoint                   | L   | 0.460      | -            | -                | -                | -         |    -5.50 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           23 |     3823 | 2024-11-07 | Glitchtech Esports         | W   | 0.441      | -            | -                | -                | 0 (0.000) |     4.26 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           22 |     3917 | 2024-11-05 | Dreams To Legends          | L   | 0.427      | -            | -                | -                | -         |    -8.33 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           21 |     3921 | 2024-11-05 | 8Sins                      | L   | 0.427      | -            | -                | -                | -         |    -3.18 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           20 |     4243 | 2024-10-31 | ALASKA                     | L   | 0.393      | -            | -                | -                | -         |    -1.41 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           19 |     4298 | 2024-10-30 | TRAXXXMANIA                | L   | 0.387      | -            | -                | -                | -         |    -6.53 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           18 |     4354 | 2024-10-29 | Annex Esports              | W   | 0.381      | -            | -                | -                | 0 (0.000) |     4.64 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           17 |     4739 | 2024-10-21 | The Last Resort            | W   | 0.326      | 0.143        | 0.001 (0.000)    | 0.161 (0.007)    | 0 (0.000) |     5.46 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           16 |     4935 | 2024-10-17 | Monte                      | L   | 0.299      | -            | -                | -                | -         |    -2.19 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           15 |     4980 | 2024-10-16 | MOUZ NXT                   | W   | 0.293      | 0.333        | -                | 0.186 (0.018)    | 0 (0.000) |     3.10 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           14 |     5407 | 2024-10-08 | Belfast Storm              | W   | 0.240      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     3.92 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           13 |     5801 | 2024-10-02 | Monte                      | L   | 0.197      | -            | -                | -                | -         |    -1.45 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           12 |     6025 | 2024-09-28 | Astralis Talent            | W   | 0.173      | 0.354        | 0.002 (0.000)    | 0.733 (0.045)    | 0 (0.000) |     3.33 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           11 |     6148 | 2024-09-27 | GenOne                     | W   | 0.165      | 0.333        | 0.012 (0.001)    | 0.848 (0.047)    | 0 (0.000) |     3.61 | ERSIN, oskvr, shateri, Swaggy, waZz |
|           10 |     6234 | 2024-09-26 | GenOne                     | W   | 0.157      | 0.333        | 0.012 (0.001)    | 0.848 (0.044)    | -         |     3.46 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            9 |     6278 | 2024-09-25 | EYEBALLERS                 | L   | 0.153      | -            | -                | -                | -         |    -1.67 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            8 |     6310 | 2024-09-25 | PCIFIC Espor               | W   | 0.151      | 0.354        | 0.004 (0.000)    | 0.254 (0.014)    | -         |     2.95 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            7 |     6514 | 2024-09-22 | Astralis Talent            | L   | 0.132      | -            | -                | -                | -         |    -1.55 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            6 |     6536 | 2024-09-22 | Partizan Esports           | W   | 0.130      | 0.333        | 0.082 (0.004)    | 0.768 (0.033)    | -         |     3.74 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            5 |     6635 | 2024-09-20 | Natus Vincere Youth        | W   | 0.119      | -            | -                | -                | -         |     0.94 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            4 |     6743 | 2024-09-18 | LOADING (French team)      | L   | 0.107      | -            | -                | -                | -         |    -2.42 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            3 |     6857 | 2024-09-17 | Preasy Esport              | W   | 0.097      | 0.333        | 0.012 (0.000)    | 0.710 (0.023)    | -         |     2.05 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            2 |     6900 | 2024-09-16 | GenOne                     | L   | 0.091      | -            | -                | -                | -         |    -0.87 | ERSIN, oskvr, shateri, Swaggy, waZz |
|            1 |     7026 | 2024-09-14 | FORZE Reload               | L   | 0.078      | -            | -                | -                | -         |    -0.70 | ERSIN, oskvr, shateri, Swaggy, waZz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,435.07)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-03 |      0.613 | $500.00        | $306.60         |
| 2024-10-18 |      0.306 | $1,000.00      | $305.56         |
| 2024-09-27 |      0.165 | $5,000.00      | $822.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
