### Roster Details<br />
Team Name: ROUNDS<br />
Roster: foqu, Kollo, m0n0xx, p12, Villeboe<br />
Global Rank: [555](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [342]( ../standings_europe.md)<br />
<br />
Final Rank Value:  475.8<br />
<br />
Final Rank Value (475.8) = Starting Rank Value (526.0) + Head To Head Adjustments (-50.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.0
- 400 + ( ( 0.063 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 526.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1176 | 2025-01-18 | Ex-UHKA eSports                           | L   | 0.911      | -            | -                | -                | -         |   -12.16 | foqu, Kollo, m0n0xx, p12, Villeboe |
|           19 |     1184 | 2025-01-17 | Team yaNgile                              | L   | 0.905      | -            | -                | -                | -         |   -17.75 | foqu, Kollo, m0n0xx, p12, Villeboe |
|           18 |     2981 | 2024-11-22 | Los kogutos                               | W   | 0.531      | 0.372        | 0.032 (0.006)    | 0.515 (0.102)    | 0 (0.000) |    15.21 | foqu, Kollo, p12, p3kko, Villeboe  |
|           17 |     3047 | 2024-11-21 | The Suspect                               | L   | 0.524      | -            | -                | -                | -         |    -3.55 | foqu, Kollo, p12, p3kko, Villeboe  |
|           16 |     3104 | 2024-11-20 | Infinite Gaming                           | L   | 0.519      | -            | -                | -                | -         |    -8.09 | foqu, Kollo, p12, p3kko, Villeboe  |
|           15 |     3165 | 2024-11-19 | Ex-RUBY                                   | L   | 0.511      | -            | -                | -                | -         |    -7.02 | foqu, Kollo, p12, p3kko, Villeboe  |
|           14 |     3506 | 2024-11-13 | ADEPTS                                    | L   | 0.472      | -            | -                | -                | -         |    -5.30 | foqu, Kollo, p12, p3kko, Villeboe  |
|           13 |     3554 | 2024-11-12 | HyperSpirit                               | L   | 0.465      | -            | -                | -                | -         |    -4.63 | foqu, Kollo, p12, p3kko, Villeboe  |
|           12 |     3668 | 2024-11-10 | Metizport X                               | L   | 0.452      | -            | -                | -                | -         |    -4.60 | foqu, Kollo, p12, p3kko, Villeboe  |
|           11 |     3843 | 2024-11-07 | Anonymo Esports                           | W   | 0.432      | 0.372        | 0.000 (0.000)    | 0.099 (0.016)    | 0 (0.000) |     7.48 | foqu, Kollo, p12, p3kko, Villeboe  |
|           10 |     3905 | 2024-11-06 | GamerLegion Academy                       | L   | 0.424      | -            | -                | -                | -         |    -5.79 | foqu, Kollo, p12, p3kko, Villeboe  |
|            9 |     4018 | 2024-11-04 | Kubix Esports                             | L   | 0.411      | -            | -                | -                | -         |    -1.24 | foqu, Kollo, p12, p3kko, Villeboe  |
|            8 |     4369 | 2024-10-29 | FORZE Reload                              | L   | 0.372      | -            | -                | -                | -         |    -1.55 | foqu, Kollo, p12, p3kko, Villeboe  |
|            7 |     4436 | 2024-10-28 | ALTERNATE aTTaX                           | L   | 0.365      | -            | -                | -                | -         |    -1.20 | foqu, Kollo, p12, p3kko, Villeboe  |
|            6 |     4738 | 2024-10-21 | PCIFIC Espor                              | L   | 0.318      | -            | -                | -                | -         |    -2.09 | foqu, Kollo, p12, p3kko, Villeboe  |
|            5 |     4786 | 2024-10-20 | ARCRED                                    | L   | 0.311      | -            | -                | -                | -         |    -2.23 | foqu, Kollo, p12, p3kko, Villeboe  |
|            4 |     4795 | 2024-10-20 | Ins (Polish team)                         | W   | 0.311      | 0.143        | 0.004 (0.000)    | 0.274 (0.012)    | 0 (0.000) |     6.96 | foqu, Kollo, p12, p3kko, Villeboe  |
|            3 |     5012 | 2024-10-16 | Fire Flux Esports                         | L   | 0.284      | -            | -                | -                | -         |    -1.11 | foqu, Kollo, p12, p3kko, Villeboe  |
|            2 |     5084 | 2024-10-15 | Copenhagen Wolves (American organization) | L   | 0.277      | -            | -                | -                | -         |    -1.21 | foqu, Kollo, p12, p3kko, Villeboe  |
|            1 |     5356 | 2024-10-09 | ALASKA                                    | L   | 0.238      | -            | -                | -                | -         |    -0.24 | foqu, Kollo, p12, p3kko, Villeboe  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
