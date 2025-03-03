### Roster Details<br />
Team Name: XI Esport<br />
Roster: Ariant0, Inspire, Junyme, Logic, titulus<br />
Global Rank: [492](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [305]( ../standings_europe.md)<br />
<br />
Final Rank Value:  522.5<br />
<br />
Final Rank Value (522.5) = Starting Rank Value (499.5) + Head To Head Adjustments (23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.050<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 499.5
- 400 + ( ( 0.050 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 499.5


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
|           24 |     3608 | 2024-11-11 | Denial (Danish team)      | W   | 0.459      | 0.143        | 0.001 (0.000)    | 0.104 (0.007)    | 0 (0.000) |    10.06 | Ariant0, Inspire, Junyme, Logic, titulus |
|           23 |     3611 | 2024-11-11 | XI Esport                 | L   | 0.458      | -            | -                | -                | -         |    -4.01 | Ariant0, Inspire, Junyme, Logic, titulus |
|           22 |     3626 | 2024-11-11 | KUUSAMO.gg                | L   | 0.458      | -            | -                | -                | -         |    -7.40 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           21 |     3857 | 2024-11-07 | Ins (Polish team)         | L   | 0.431      | -            | -                | -                | -         |    -4.19 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           20 |     4000 | 2024-11-04 | Astralis Talent           | L   | 0.412      | -            | -                | -                | -         |    -3.01 | Ariant0, Inspire, Junyme, Logic, titulus |
|           19 |     4008 | 2024-11-04 | WOPA Esport               | L   | 0.412      | -            | -                | -                | -         |    -1.88 | Ariant0, Inspire, Junyme, Logic, titulus |
|           18 |     4054 | 2024-11-03 | Sampi NEXT                | W   | 0.405      | 0.278        | 0.000 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     5.82 | Ariant0, Junyme, Logic, Reedz, titulus   |
|           17 |     4431 | 2024-10-28 | Preasy Esport             | L   | 0.365      | -            | -                | -                | -         |    -2.16 | Ariant0, Inspire, Junyme, Logic, titulus |
|           16 |     4438 | 2024-10-28 | Copenhagen Wolves Academy | W   | 0.365      | -            | -                | -                | 0 (0.000) |     3.70 | Ariant0, Inspire, Junyme, Logic, titulus |
|           15 |     4730 | 2024-10-21 | MASONIC                   | W   | 0.318      | 0.143        | 0.001 (0.000)    | 0.164 (0.007)    | 0 (0.000) |     6.91 | Ariant0, Inspire, Junyme, Logic, titulus |
|           14 |     4936 | 2024-10-17 | Ex-Dynamo Eclot Thunders  | L   | 0.291      | -            | -                | -                | -         |    -3.63 | Ariant0, Inspire, Junyme, Logic, titulus |
|           13 |     5020 | 2024-10-16 | Daystar                   | W   | 0.284      | 0.278        | 0.000 (0.000)    | 0.131 (0.010)    | 0 (0.000) |     6.06 | Ariant0, G0op, Inspire, Logic, titulus   |
|           12 |     5067 | 2024-10-15 | ALTERNATE aTTaX Evo       | L   | 0.278      | -            | -                | -                | -         |    -3.17 | Ariant0, Inspire, Junyme, Logic, titulus |
|           11 |     5143 | 2024-10-13 | Devils.one                | W   | 0.265      | 0.278        | 0.001 (0.000)    | 0.068 (0.005)    | 0 (0.000) |     5.82 | Ariant0, Inspire, Junyme, Logic, titulus |
|           10 |     5302 | 2024-10-10 | Metizport X               | W   | 0.244      | 0.278        | 0.001 (0.000)    | 0.218 (0.015)    | 0 (0.000) |     5.36 | Ariant0, G0op, Inspire, Logic, titulus   |
|            9 |     5480 | 2024-10-07 | Preasy Esport             | L   | 0.225      | -            | -                | -                | -         |    -1.19 | Ariant0, G0op, Inspire, Logic, titulus   |
|            8 |     5492 | 2024-10-07 | XI Esport                 | L   | 0.224      | -            | -                | -                | -         |    -1.98 | Ariant0, G0op, Inspire, Logic, titulus   |
|            7 |     5529 | 2024-10-06 | BRUTE                     | W   | 0.218      | 0.278        | 0.004 (0.000)    | 0.341 (0.021)    | 0 (0.000) |     5.25 | Ariant0, G0op, Inspire, Logic, titulus   |
|            6 |     5784 | 2024-10-02 | Metizport X               | L   | 0.191      | -            | -                | -                | -         |    -1.81 | Ariant0, G0op, Inspire, Logic, titulus   |
|            5 |     5920 | 2024-09-30 | Copenhagen Wolves Academy | W   | 0.178      | -            | -                | -                | 0 (0.000) |     1.98 | Ariant0, G0op, Inspire, Logic, titulus   |
|            4 |     6469 | 2024-09-23 | MASONIC                   | W   | 0.132      | 0.143        | 0.001 (0.000)    | 0.164 (0.003)    | 0 (0.000) |     2.93 | Ariant0, G0op, Inspire, Logic, titulus   |
|            3 |     6482 | 2024-09-23 | WOPA Esport               | L   | 0.131      | -            | -                | -                | -         |    -0.51 | Ariant0, G0op, Inspire, Logic, titulus   |
|            2 |     6882 | 2024-09-16 | Denial (Danish team)      | W   | 0.085      | 0.143        | 0.001 (0.000)    | 0.104 (0.001)    | -         |     1.84 | Ariant0, G0op, Inspire, Logic, titulus   |
|            1 |     6896 | 2024-09-16 | Astralis Talent           | W   | 0.085      | 0.143        | 0.002 (0.000)    | 0.724 (0.009)    | -         |     2.21 | Ariant0, G0op, Inspire, Logic, titulus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
