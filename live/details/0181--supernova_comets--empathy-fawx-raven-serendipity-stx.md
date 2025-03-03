### Roster Details<br />
Team Name: Supernova Comets<br />
Roster: empathy, Fawx, raven, Serendipity, Stx<br />
Global Rank: [181](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
<br />
Final Rank Value:  725.6<br />
<br />
Final Rank Value (725.6) = Starting Rank Value (736.7) + Head To Head Adjustments (-11.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.7
- 400 + ( ( 0.168 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 736.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |        6 | 2025-03-01 | LAG Gaming         | L   | 1.000      | -            | -                | -                | -         |   -16.87 | empathy, Fawx, raven, Serendipity, Stx |
|           27 |       12 | 2025-03-01 | F5 Esports         | W   | 1.000      | 0.333        | 0.000 (0.000)    | -                | 1 (1.000) |     6.59 | empathy, Fawx, raven, Serendipity, Stx |
|           26 |      234 | 2025-02-20 | Wanted Goons       | L   | 1.000      | -            | -                | -                | -         |   -22.66 | empathy, Fawx, raven, Serendipity, Stx |
|           25 |      836 | 2025-02-06 | Blahaj             | L   | 1.000      | -            | -                | -                | -         |   -24.59 | empathy, Fawx, raven, Serendipity, Stx |
|           24 |     1284 | 2024-12-28 | Lumen              | W   | 0.774      | -            | -                | -                | 0 (0.000) |     2.56 | empathy, Fawx, milo, raven, Stx        |
|           23 |     1616 | 2024-12-15 | Lotus              | W   | 0.687      | 0.250        | 0.002 (0.000)    | 0.110 (0.019)    | 0 (0.000) |     6.43 | empathy, milo, raven, Serendipity, Stx |
|           22 |     1668 | 2024-12-14 | CrchWrapSupreme    | W   | 0.680      | -            | -                | -                | 0 (0.000) |     2.33 | empathy, milo, raven, Serendipity, Stx |
|           21 |     1981 | 2024-12-08 | GIRLYPOPS          | W   | 0.640      | 0.250        | 0.000 (0.000)    | 0.030 (0.005)    | 0 (0.000) |     5.45 | empathy, Fawx, phoebe, raven, Stx      |
|           20 |     2065 | 2024-12-07 | CrchWrapSupreme    | W   | 0.633      | -            | -                | -                | 0 (0.000) |     2.28 | empathy, Fawx, phoebe, raven, Stx      |
|           19 |     2402 | 2024-12-01 | Lotus              | W   | 0.593      | 0.250        | 0.002 (0.000)    | 0.110 (0.016)    | 0 (0.000) |     5.90 | empathy, Fawx, phoebe, raven, Stx      |
|           18 |     2469 | 2024-11-30 | GIRLYPOPS          | W   | 0.587      | 0.250        | 0.000 (0.000)    | 0.030 (0.004)    | 0 (0.000) |     5.24 | empathy, Fawx, phoebe, raven, Stx      |
|           17 |     3233 | 2024-11-17 | Lotus              | W   | 0.500      | 0.250        | 0.002 (0.000)    | 0.110 (0.014)    | 0 (0.000) |     5.17 | empathy, Fawx, phoebe, raven, Stx      |
|           16 |     3314 | 2024-11-16 | GIRLYPOPS          | W   | 0.493      | 0.250        | -                | 0.030 (0.004)    | 0 (0.000) |     4.68 | empathy, Fawx, phoebe, raven, Stx      |
|           15 |     4039 | 2024-11-03 | Lotus              | W   | 0.407      | 0.250        | 0.002 (0.000)    | 0.110 (0.011)    | -         |     4.38 | Celia, empathy, phoebe, raven, Stx     |
|           14 |     4112 | 2024-11-02 | Kitsune            | W   | 0.400      | -            | -                | -                | -         |     1.64 | Celia, empathy, phoebe, raven, Stx     |
|           13 |     4458 | 2024-10-27 | Unjustified Impact | W   | 0.360      | 0.250        | -                | 0.063 (0.006)    | -         |     2.53 | Celi, empathy, phoebe, raven, Stx      |
|           12 |     4507 | 2024-10-26 | Kitsune            | W   | 0.353      | -            | -                | -                | -         |     1.49 | Celi, empathy, phoebe, raven, Stx      |
|           11 |     4879 | 2024-10-18 | Lotus              | W   | 0.300      | 0.333        | 0.001 (0.000)    | -                | -         |     3.00 | gadfly, gone, raven, Serendipity, Stx  |
|           10 |     5188 | 2024-10-12 | Team Aether        | L   | 0.259      | -            | -                | -                | -         |    -6.35 | Celi, empathy, phoebe, raven, Stx      |
|            9 |     5194 | 2024-10-12 | Fisher College     | L   | 0.258      | -            | -                | -                | -         |    -3.77 | Celi, empathy, phoebe, raven, Stx      |
|            8 |     5513 | 2024-10-06 | Imp Pact           | W   | 0.220      | -            | -                | -                | -         |     2.11 | Celi, empathy, phoebe, raven, Stx      |
|            7 |     5564 | 2024-10-05 | Aware Impact       | W   | 0.213      | -            | -                | -                | -         |     2.15 | Celi, empathy, phoebe, raven, Stx      |
|            6 |     5756 | 2024-10-02 | TSM Impact         | W   | 0.193      | 0.333        | 0.001 (0.000)    | 0.021 (0.001)    | -         |     2.08 | gadfly, gone, raven, Serendipity, Stx  |
|            5 |     6261 | 2024-09-25 | Nouns.fe           | W   | 0.146      | 0.333        | 0.001 (0.000)    | 0.070 (0.003)    | -         |     1.56 | gadfly, gone, raven, Serendipity, Stx  |
|            4 |     6676 | 2024-09-19 | FlyQuest RED       | L   | 0.107      | -            | -                | -                | -         |    -2.03 | gadfly, gone, raven, Serendipity, Stx  |
|            3 |     6971 | 2024-09-14 | FlyQuest RED       | L   | 0.074      | -            | -                | -                | -         |    -1.41 | gadfly, gone, Raven, Serendipity, Stx  |
|            2 |     7126 | 2024-09-12 | FLUFFY MAFIA       | L   | 0.060      | -            | -                | -                | -         |    -1.22 | gadfly, gone, raven, Serendipity, Stx  |
|            1 |     7562 | 2024-09-05 | Aware Impact       | W   | 0.013      | -            | -                | -                | -         |     0.13 | gadfly, gone, raven, Serendipity, Stx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,644.09)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.774 | $750.00        | $580.40         |
| 2024-12-15 |      0.687 | $750.00        | $515.21         |
| 2024-12-08 |      0.640 | $750.00        | $479.90         |
| 2024-12-01 |      0.593 | $750.00        | $444.69         |
| 2024-11-17 |      0.500 | $750.00        | $374.90         |
| 2024-11-03 |      0.407 | $750.00        | $304.90         |
| 2024-10-27 |      0.360 | $750.00        | $269.90         |
| 2024-10-18 |      0.300 | $1,700.00      | $509.53         |
| 2024-10-06 |      0.220 | $750.00        | $164.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
