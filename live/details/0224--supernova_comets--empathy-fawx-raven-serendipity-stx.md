### Roster Details<br />
Team Name: Supernova Comets<br />
Roster: empathy, Fawx, raven, Serendipity, Stx<br />
Global Rank: [224](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [41]( ../standings_americas.md)<br />
<br />
Final Rank Value:  693.3<br />
<br />
Final Rank Value (693.3) = Starting Rank Value (677.9) + Head To Head Adjustments (15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.9
- 400 + ( ( 0.139 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 677.9


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
|           26 |      222 | 2025-02-20 | Wanted Goons       | L   | 1.000      | -            | -                | -                | -         |   -23.24 | empathy, Fawx, raven, Serendipity, Stx |
|           25 |      824 | 2025-02-06 | Blahaj             | L   | 1.000      | -            | -                | -                | -         |   -23.16 | empathy, Fawx, raven, Serendipity, Stx |
|           24 |     1272 | 2024-12-28 | Lumen              | W   | 0.782      | -            | -                | -                | 0 (0.000) |     3.21 | empathy, Fawx, milo, raven, Stx        |
|           23 |     1604 | 2024-12-15 | Lotus              | W   | 0.695      | 0.250        | 0.002 (0.000)    | 0.111 (0.019)    | 0 (0.000) |     7.61 | empathy, milo, raven, Serendipity, Stx |
|           22 |     1656 | 2024-12-14 | CrchWrapSupreme    | W   | 0.688      | -            | -                | -                | 0 (0.000) |     2.94 | empathy, milo, raven, Serendipity, Stx |
|           21 |     1969 | 2024-12-08 | GIRLYPOPS          | W   | 0.648      | 0.250        | 0.000 (0.000)    | 0.030 (0.005)    | 0 (0.000) |     6.56 | empathy, Fawx, phoebe, raven, Stx      |
|           20 |     2053 | 2024-12-07 | CrchWrapSupreme    | W   | 0.641      | -            | -                | -                | 0 (0.000) |     2.91 | empathy, Fawx, phoebe, raven, Stx      |
|           19 |     2390 | 2024-12-01 | Lotus              | W   | 0.601      | 0.250        | 0.002 (0.000)    | 0.111 (0.017)    | 0 (0.000) |     7.08 | empathy, Fawx, phoebe, raven, Stx      |
|           18 |     2457 | 2024-11-30 | GIRLYPOPS          | W   | 0.595      | 0.250        | 0.000 (0.000)    | 0.030 (0.004)    | 0 (0.000) |     6.39 | empathy, Fawx, phoebe, raven, Stx      |
|           17 |     3221 | 2024-11-17 | Lotus              | W   | 0.508      | 0.250        | 0.002 (0.000)    | 0.111 (0.014)    | 0 (0.000) |     6.27 | empathy, Fawx, phoebe, raven, Stx      |
|           16 |     3302 | 2024-11-16 | GIRLYPOPS          | W   | 0.501      | 0.250        | 0.000 (0.000)    | 0.030 (0.004)    | 0 (0.000) |     5.76 | empathy, Fawx, phoebe, raven, Stx      |
|           15 |     4027 | 2024-11-03 | Lotus              | W   | 0.415      | 0.250        | 0.002 (0.000)    | 0.111 (0.012)    | 0 (0.000) |     5.36 | Celia, empathy, phoebe, raven, Stx     |
|           14 |     4100 | 2024-11-02 | Kitsune            | W   | 0.408      | -            | -                | -                | -         |     2.15 | Celia, empathy, phoebe, raven, Stx     |
|           13 |     4446 | 2024-10-27 | Unjustified Impact | W   | 0.368      | 0.250        | -                | 0.064 (0.006)    | -         |     3.24 | Celi, empathy, phoebe, raven, Stx      |
|           12 |     4495 | 2024-10-26 | Kitsune            | W   | 0.361      | -            | -                | -                | -         |     1.97 | Celi, empathy, phoebe, raven, Stx      |
|           11 |     4867 | 2024-10-18 | Lotus              | W   | 0.308      | 0.333        | 0.001 (0.000)    | -                | -         |     3.77 | gadfly, gone, raven, Serendipity, Stx  |
|           10 |     5176 | 2024-10-12 | Team Aether        | L   | 0.267      | -            | -                | -                | -         |    -6.07 | Celi, empathy, phoebe, raven, Stx      |
|            9 |     5182 | 2024-10-12 | Fisher College     | L   | 0.267      | -            | -                | -                | -         |    -3.24 | Celi, empathy, phoebe, raven, Stx      |
|            8 |     5501 | 2024-10-06 | Imp Pact           | W   | 0.228      | -            | -                | -                | -         |     2.71 | Celi, empathy, phoebe, raven, Stx      |
|            7 |     5552 | 2024-10-05 | Aware Impact       | W   | 0.221      | -            | -                | -                | -         |     2.75 | Celi, empathy, phoebe, raven, Stx      |
|            6 |     5744 | 2024-10-02 | TSM Impact         | W   | 0.201      | 0.333        | 0.001 (0.000)    | 0.022 (0.001)    | -         |     2.66 | gadfly, gone, raven, Serendipity, Stx  |
|            5 |     6249 | 2024-09-25 | Nouns.fe           | W   | 0.155      | 0.333        | 0.001 (0.000)    | 0.071 (0.004)    | -         |     2.02 | gadfly, gone, raven, Serendipity, Stx  |
|            4 |     6664 | 2024-09-19 | FlyQuest RED       | L   | 0.115      | -            | -                | -                | -         |    -1.90 | gadfly, gone, raven, Serendipity, Stx  |
|            3 |     6959 | 2024-09-14 | FlyQuest RED       | L   | 0.082      | -            | -                | -                | -         |    -1.36 | gadfly, gone, Raven, Serendipity, Stx  |
|            2 |     7114 | 2024-09-12 | FLUFFY MAFIA       | L   | 0.068      | -            | -                | -                | -         |    -1.22 | gadfly, gone, raven, Serendipity, Stx  |
|            1 |     7550 | 2024-09-05 | Aware Impact       | W   | 0.021      | -            | -                | -                | -         |     0.27 | gadfly, gone, raven, Serendipity, Stx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,707.19)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.782 | $750.00        | $586.55         |
| 2024-12-15 |      0.695 | $750.00        | $521.35         |
| 2024-12-08 |      0.648 | $750.00        | $486.04         |
| 2024-12-01 |      0.601 | $750.00        | $450.83         |
| 2024-11-17 |      0.508 | $750.00        | $381.04         |
| 2024-11-03 |      0.415 | $750.00        | $311.04         |
| 2024-10-27 |      0.368 | $750.00        | $276.04         |
| 2024-10-18 |      0.308 | $1,700.00      | $523.46         |
| 2024-10-06 |      0.228 | $750.00        | $170.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
