### Roster Details<br />
Team Name: ADEPTS<br />
Roster: cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky<br />
Global Rank: [352](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [225]( ../standings_europe.md)<br />
<br />
Final Rank Value:  624.7<br />
<br />
Final Rank Value (624.7) = Starting Rank Value (590.5) + Head To Head Adjustments (34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 590.5
- 400 + ( ( 0.095 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 590.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |     1410 | 2024-12-22 | WOPA Esport         | L   | 0.731      | -            | -                | -                | -         |    -4.95 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           57 |     1478 | 2024-12-21 | KONO.ECF            | L   | 0.724      | -            | -                | -                | -         |    -4.72 | cHeuuuuk, Chuckyy, SBT, Tarkky, xReal    |
|           56 |     1553 | 2024-12-19 | Preasy Esport       | W   | 0.710      | 0.333        | 0.012 (0.003)    | 0.701 (0.166)    | 0 (0.000) |    14.89 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           55 |     1604 | 2024-12-16 | Heimo Esports       | W   | 0.690      | 0.333        | 0.004 (0.001)    | 0.651 (0.150)    | 0 (0.000) |    14.30 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           54 |     1823 | 2024-12-13 | ENCE Academy        | L   | 0.669      | -            | -                | -                | -         |    -5.64 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           53 |     1836 | 2024-12-12 | Dark Cloud Esports  | L   | 0.666      | -            | -                | -                | -         |    -4.99 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           52 |     1851 | 2024-12-12 | GODSENT             | L   | 0.664      | -            | -                | -                | -         |    -8.94 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           51 |     1892 | 2024-12-11 | Illuminar Gaming    | L   | 0.658      | -            | -                | -                | -         |    -5.26 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           50 |     1970 | 2024-12-09 | Heimo Esports       | W   | 0.644      | 0.333        | 0.004 (0.001)    | 0.651 (0.140)    | 0 (0.000) |    12.50 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           49 |     1997 | 2024-12-08 | Astralis Talent     | L   | 0.638      | -            | -                | -                | -         |    -5.83 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           48 |     2430 | 2024-12-01 | Kubix Esports       | L   | 0.592      | -            | -                | -                | -         |    -3.15 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           47 |     2587 | 2024-11-29 | FLuffy Gangsters    | L   | 0.579      | -            | -                | -                | -         |    -4.06 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           46 |     2680 | 2024-11-27 | Preasy Esport       | L   | 0.565      | -            | -                | -                | -         |    -5.93 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           45 |     2712 | 2024-11-26 | JANO Esports        | W   | 0.559      | 0.333        | 0.022 (0.004)    | 0.440 (0.082)    | 0 (0.000) |    14.40 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           44 |     2906 | 2024-11-23 | 777 Esports         | W   | 0.537      | 0.333        | -                | 0.235 (0.042)    | 0 (0.000) |     9.52 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           43 |     3019 | 2024-11-21 | Monte               | L   | 0.526      | -            | -                | -                | -         |    -2.46 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           42 |     3058 | 2024-11-21 | Nexus Gaming        | L   | 0.524      | -            | -                | -                | -         |    -0.93 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           41 |     3098 | 2024-11-20 | Lilmix              | W   | 0.519      | -            | -                | -                | 0 (0.000) |     8.18 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           40 |     3179 | 2024-11-19 | Preasy Esport       | L   | 0.509      | -            | -                | -                | -         |    -5.22 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           39 |     3198 | 2024-11-18 | XP Academy          | L   | 0.505      | -            | -                | -                | -         |    -8.42 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           38 |     3451 | 2024-11-14 | Infinite Gaming     | W   | 0.478      | -            | -                | -                | 0 (0.000) |     5.38 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           37 |     3495 | 2024-11-13 | GODSENT             | L   | 0.472      | -            | -                | -                | -         |    -6.25 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           36 |     3506 | 2024-11-13 | ROUNDS              | W   | 0.472      | -            | -                | -                | 0 (0.000) |     5.30 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           35 |     3663 | 2024-11-10 | Permitta Esports    | W   | 0.452      | 0.372        | 0.013 (0.002)    | 0.487 (0.082)    | 0 (0.000) |    10.64 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           34 |     3939 | 2024-11-05 | GTZ.ESPORTS         | W   | 0.419      | 0.372        | 0.080 (0.012)    | 0.557 (0.087)    | 0 (0.000) |    12.68 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           33 |     3966 | 2024-11-05 | Astralis Talent     | L   | 0.417      | -            | -                | -                | -         |    -3.87 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           32 |     4226 | 2024-11-01 | Heimo Esports       | L   | 0.389      | -            | -                | -                | -         |    -3.54 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           31 |     4324 | 2024-10-30 | ALTERNATE aTTaX     | W   | 0.378      | 0.372        | 0.021 (0.003)    | 0.552 (0.078)    | -         |    10.17 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           30 |     4382 | 2024-10-29 | THE SPELLS          | L   | 0.371      | -            | -                | -                | -         |    -6.47 | cHeuuuuk, Chuckyy, HippoV, SBT, Tarkky   |
|           29 |     4872 | 2024-10-19 | Viperio             | L   | 0.303      | -            | -                | -                | -         |    -2.99 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           28 |     5002 | 2024-10-16 | Partizan Esports    | L   | 0.285      | -            | -                | -                | -         |    -0.60 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           27 |     5074 | 2024-10-15 | HyperSpirit         | W   | 0.278      | -            | -                | -                | -         |     5.22 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           26 |     5168 | 2024-10-13 | KONO.ECF            | W   | 0.263      | 0.333        | 0.046 (0.004)    | 0.747 (0.065)    | -         |     7.12 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           25 |     5296 | 2024-10-10 | Viperio             | L   | 0.244      | -            | -                | -                | -         |    -2.20 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           24 |     5374 | 2024-10-09 | Ex-9INE Academy     | W   | 0.236      | -            | -                | -                | -         |     3.76 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           23 |     5866 | 2024-10-01 | Underrated          | L   | 0.184      | -            | -                | -                | -         |    -2.09 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           22 |     5915 | 2024-09-30 | Ex-9INE Academy     | W   | 0.178      | -            | -                | -                | -         |     2.87 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           21 |     6144 | 2024-09-27 | Underrated          | L   | 0.157      | -            | -                | -                | -         |    -1.75 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           20 |     6241 | 2024-09-26 | ALASKA              | L   | 0.149      | -            | -                | -                | -         |    -0.20 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           19 |     6285 | 2024-09-25 | GameAgents          | L   | 0.145      | -            | -                | -                | -         |    -1.68 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           18 |     6326 | 2024-09-25 | WOPA Esport         | L   | 0.143      | -            | -                | -                | -         |    -0.85 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           17 |     6334 | 2024-09-25 | Alliance            | L   | 0.142      | -            | -                | -                | -         |    -0.69 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           16 |     6412 | 2024-09-24 | RUBY                | L   | 0.137      | -            | -                | -                | -         |    -1.56 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           15 |     6430 | 2024-09-24 | Partizan Esports    | L   | 0.135      | -            | -                | -                | -         |    -0.25 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           14 |     6493 | 2024-09-23 | FLuffy Gangsters    | L   | 0.130      | -            | -                | -                | -         |    -1.03 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           13 |     6503 | 2024-09-23 | Preasy Esport       | W   | 0.129      | 0.333        | 0.012 (0.001)    | -                | -         |     3.12 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           12 |     6535 | 2024-09-22 | Partizan Esports    | W   | 0.123      | 0.333        | 0.083 (0.003)    | 0.757 (0.031)    | -         |     3.67 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           11 |     6591 | 2024-09-21 | Viperio             | L   | 0.117      | -            | -                | -                | -         |    -1.03 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|           10 |     6611 | 2024-09-21 | Viperio             | L   | 0.115      | -            | -                | -                | -         |    -1.02 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            9 |     6633 | 2024-09-20 | Preasy Esport       | L   | 0.112      | -            | -                | -                | -         |    -0.81 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            8 |     6727 | 2024-09-19 | Partizan Esports    | L   | 0.102      | -            | -                | -                | -         |    -0.18 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            7 |     6782 | 2024-09-18 | Ex-9INE Academy     | W   | 0.096      | -            | -                | -                | -         |     1.56 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            6 |     6849 | 2024-09-17 | GODSENT             | L   | 0.091      | -            | -                | -                | -         |    -1.13 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            5 |     6884 | 2024-09-16 | Leo Team            | L   | 0.085      | -            | -                | -                | -         |    -0.55 | cHeuuuuk, Chuckyy, Oxbrandd, SBT, Tarkky |
|            4 |     7044 | 2024-09-14 | Astralis Talent     | L   | 0.070      | -            | -                | -                | -         |    -0.56 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            3 |     7118 | 2024-09-13 | Team Spirit Academy | L   | 0.062      | -            | -                | -                | -         |    -0.27 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            2 |     7272 | 2024-09-10 | Ex-9INE Academy     | W   | 0.043      | -            | -                | -                | -         |     0.70 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            1 |     7636 | 2024-09-05 | Dark Cloud Esports  | W   | 0.009      | -            | -                | -                | -         |     0.24 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
