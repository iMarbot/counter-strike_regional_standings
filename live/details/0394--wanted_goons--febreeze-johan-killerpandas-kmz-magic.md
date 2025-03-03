### Roster Details<br />
Team Name: Wanted Goons<br />
Roster: febreeze, Johan, killerPandas, KmZ, Magic<br />
Global Rank: [394](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [85]( ../standings_americas.md)<br />
<br />
Final Rank Value:  602.1<br />
<br />
Final Rank Value (602.1) = Starting Rank Value (568.4) + Head To Head Adjustments (33.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.084<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 568.4
- 400 + ( ( 0.084 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 568.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |        5 | 2025-03-01 | Marsborne        | L   | 1.000      | -            | -                | -                | -         |    -5.17 | febreeze, Johan, killerPandas, KmZ, Magic |
|            4 |       14 | 2025-03-01 | Amped Esports    | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     7.48 | febreeze, Johan, killerPandas, KmZ, Magic |
|            3 |      183 | 2025-02-21 | Fisher College   | L   | 1.000      | -            | -                | -                | -         |    -8.94 | febreeze, Johan, killerPandas, KmZ, Magic |
|            2 |      186 | 2025-02-21 | Immigrants Peek  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.366 (0.052)    | 0 (0.000) |    17.70 | febreeze, Johan, killerPandas, KmZ, Magic |
|            1 |      234 | 2025-02-20 | Supernova Comets | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.263 (0.038)    | 0 (0.000) |    22.66 | febreeze, Johan, killerPandas, KmZ, Magic |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
