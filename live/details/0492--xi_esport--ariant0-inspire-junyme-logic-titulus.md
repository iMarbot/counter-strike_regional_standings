### Roster Details<br />
Team Name: XI Esport<br />
Roster: Ariant0, Inspire, Junyme, Logic, titulus<br />
Global Rank: [492](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [306]( ../standings_europe.md)<br />
<br />
Final Rank Value:  523.8<br />
<br />
Final Rank Value (523.8) = Starting Rank Value (499.9) + Head To Head Adjustments (23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 499.9
- 400 + ( ( 0.050 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 499.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     3596 | 2024-11-11 | Denial (Danish team)      | W   | 0.467      | 0.143        | 0.001 (0.000)    | 0.106 (0.007)    | 0 (0.000) |    10.23 | Ariant0, Inspire, Junyme, Logic, titulus |
|           23 |     3599 | 2024-11-11 | XI Esport                 | L   | 0.467      | -            | -                | -                | -         |    -4.09 | Ariant0, Inspire, Junyme, Logic, titulus |
|           22 |     3614 | 2024-11-11 | KUUSAMO.gg                | L   | 0.466      | -            | -                | -                | -         |    -7.56 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           21 |     3845 | 2024-11-07 | Ins (Polish team)         | L   | 0.439      | -            | -                | -                | -         |    -4.29 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           20 |     3988 | 2024-11-04 | Astralis Talent           | L   | 0.420      | -            | -                | -                | -         |    -3.09 | Ariant0, Inspire, Junyme, Logic, titulus |
|           19 |     3996 | 2024-11-04 | WOPA Esport               | L   | 0.420      | -            | -                | -                | -         |    -1.92 | Ariant0, Inspire, Junyme, Logic, titulus |
|           18 |     4042 | 2024-11-03 | Sampi NEXT                | W   | 0.413      | 0.278        | 0.000 (0.000)    | 0.024 (0.003)    | 0 (0.000) |     5.91 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           17 |     4419 | 2024-10-28 | Preasy Esport             | L   | 0.374      | -            | -                | -                | -         |    -2.21 | Ariant0, Inspire, Junyme, Logic, titulus |
|           16 |     4426 | 2024-10-28 | Copenhagen Wolves Academy | W   | 0.373      | -            | -                | -                | 0 (0.000) |     3.75 | Ariant0, Inspire, Junyme, Logic, titulus |
|           15 |     4718 | 2024-10-21 | MASONIC                   | W   | 0.327      | 0.143        | 0.001 (0.000)    | 0.166 (0.008)    | 0 (0.000) |     7.07 | Ariant0, Inspire, Junyme, Logic, titulus |
|           14 |     4924 | 2024-10-17 | Ex-Dynamo Eclot Thunders  | L   | 0.299      | -            | -                | -                | -         |    -3.75 | Ariant0, Inspire, Junyme, Logic, titulus |
|           13 |     5008 | 2024-10-16 | Daystar                   | W   | 0.292      | 0.278        | 0.000 (0.000)    | 0.135 (0.011)    | 0 (0.000) |     6.24 | Ariant0, G0op, Inspire, Logic, titulus   |
|           12 |     5055 | 2024-10-15 | ALTERNATE aTTaX Evo       | L   | 0.286      | -            | -                | -                | -         |    -3.27 | Ariant0, Inspire, Junyme, Logic, titulus |
|           11 |     5131 | 2024-10-13 | Devils.one                | W   | 0.273      | 0.278        | 0.001 (0.000)    | 0.073 (0.006)    | 0 (0.000) |     6.02 | Ariant0, Inspire, Junyme, Logic, titulus |
|           10 |     5290 | 2024-10-10 | Metizport X               | W   | 0.252      | 0.278        | 0.001 (0.000)    | 0.221 (0.015)    | 0 (0.000) |     5.53 | Ariant0, G0op, Inspire, Logic, titulus   |
|            9 |     5468 | 2024-10-07 | Preasy Esport             | L   | 0.233      | -            | -                | -                | -         |    -1.23 | Ariant0, G0op, Inspire, Logic, titulus   |
|            8 |     5480 | 2024-10-07 | XI Esport                 | L   | 0.233      | -            | -                | -                | -         |    -2.06 | Ariant0, G0op, Inspire, Logic, titulus   |
|            7 |     5517 | 2024-10-06 | BRUTE                     | W   | 0.226      | 0.278        | 0.004 (0.000)    | 0.345 (0.022)    | 0 (0.000) |     5.44 | Ariant0, G0op, Inspire, Logic, titulus   |
|            6 |     5772 | 2024-10-02 | Metizport X               | L   | 0.199      | -            | -                | -                | -         |    -1.89 | Ariant0, G0op, Inspire, Logic, titulus   |
|            5 |     5908 | 2024-09-30 | Copenhagen Wolves Academy | W   | 0.186      | -            | -                | -                | 0 (0.000) |     2.06 | Ariant0, G0op, Inspire, Logic, titulus   |
|            4 |     6457 | 2024-09-23 | MASONIC                   | W   | 0.140      | 0.143        | 0.001 (0.000)    | 0.166 (0.003)    | 0 (0.000) |     3.11 | Ariant0, G0op, Inspire, Logic, titulus   |
|            3 |     6470 | 2024-09-23 | WOPA Esport               | L   | 0.139      | -            | -                | -                | -         |    -0.54 | Ariant0, G0op, Inspire, Logic, titulus   |
|            2 |     6870 | 2024-09-16 | Denial (Danish team)      | W   | 0.093      | 0.143        | 0.001 (0.000)    | 0.106 (0.001)    | -         |     2.02 | Ariant0, G0op, Inspire, Logic, titulus   |
|            1 |     6884 | 2024-09-16 | Astralis Talent           | W   | 0.093      | 0.143        | 0.002 (0.000)    | 0.733 (0.010)    | -         |     2.42 | Ariant0, G0op, Inspire, Logic, titulus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
