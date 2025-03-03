### Roster Details<br />
Team Name: Blahaj<br />
Roster: dAVE, Freaky, LUKE4k, traekS, zeep<br />
Global Rank: [459](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [102]( ../standings_americas.md)<br />
<br />
Final Rank Value:  554.1<br />
<br />
Final Rank Value (554.1) = Starting Rank Value (516.6) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 516.6
- 400 + ( ( 0.058 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 516.6


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
|            9 |        8 | 2025-03-01 | Getting Info       | L   | 1.000      | -            | -                | -                | -         |    -4.12 | dAVE, Freaky, LUKE4k, traekS, zeep     |
|            8 |      822 | 2025-02-06 | MIGHT              | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Freaky, LUKE4k, sava9e, traekS, zeep   |
|            7 |      824 | 2025-02-06 | Akimbo Esports     | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.327 (0.047)    | 0 (0.000) |    20.40 | Freaky, LUKE4k, sava9e, traekS, zeep   |
|            6 |      829 | 2025-02-06 | Immigrants Peek    | L   | 1.000      | -            | -                | -                | -         |   -11.62 | Freaky, LUKE4k, sava9e, traekS, zeep   |
|            5 |      836 | 2025-02-06 | Supernova Comets   | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.263 (0.038)    | 0 (0.000) |    24.59 | Freaky, LUKE4k, sava9e, traekS, zeep   |
|            4 |     2937 | 2024-11-22 | Chill Guys         | L   | 0.534      | -            | -                | -                | -         |    -4.98 | dAVE, LUKE4k, mason, traekS, zeep      |
|            3 |     2939 | 2024-11-22 | Make Your Mind     | W   | 0.534      | 0.143        | 0.014 (0.001)    | 0.285 (0.022)    | 0 (0.000) |    12.35 | dAVE, LUKE4k, mason, traekS, zeep      |
|            2 |     2946 | 2024-11-22 | Bad News Capybaras | W   | 0.534      | 0.143        | 0.000 (0.000)    | 0.113 (0.009)    | 0 (0.000) |    11.30 | dAVE, LUKE4k, mason, traekS, zeep      |
|            1 |     6183 | 2024-09-26 | Team Aether        | L   | 0.153      | -            | -                | -                | -         |    -2.45 | dAVE, Loagurt, traekS, WetWillie, zeep |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
