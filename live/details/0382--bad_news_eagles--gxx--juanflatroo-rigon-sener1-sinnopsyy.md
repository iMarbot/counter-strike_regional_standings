### Roster Details<br />
Team Name: Bad News Eagles<br />
Roster: gxx-, juanflatroo, rigoN, SENER1, sinnopsyy<br />
Global Rank: [382](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [239]( ../standings_europe.md)<br />
<br />
Final Rank Value:  608.2<br />
<br />
Final Rank Value (608.2) = Starting Rank Value (541.7) + Head To Head Adjustments (66.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.071<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 541.7
- 400 + ( ( 0.071 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 541.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      310 | 2025-02-17 | GenOne                                    | L   | 1.000      | -            | -                | -                | -         |    -6.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            6 |      345 | 2025-02-16 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.143        | 0.016 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    25.36 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            5 |      760 | 2025-02-07 | Mission Possible                          | L   | 1.000      | -            | -                | -                | -         |   -16.61 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            4 |      972 | 2025-02-04 | PARIVISION                                | L   | 1.000      | -            | -                | -                | -         |   -12.67 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            3 |      992 | 2025-02-04 | AMKAL ESPORTS                             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.674 (0.096)    | 0 (0.000) |    24.83 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            2 |     1005 | 2025-02-04 | K27                                       | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.769 (0.110)    | 0 (0.000) |    25.50 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |
|            1 |     1017 | 2025-02-04 | CYBERSHOKE Esports                        | W   | 1.000      | 0.143        | 0.011 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    26.42 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
