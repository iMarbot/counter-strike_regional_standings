### Roster Details<br />
Team Name: BASEMENT BOYS<br />
Roster: Bambosh, ERSIN, levantino, Polbandana, Tr0ublE<br />
Global Rank: [548](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [338]( ../standings_europe.md)<br />
<br />
Final Rank Value:  480.9<br />
<br />
Final Rank Value (480.9) = Starting Rank Value (404.3) + Head To Head Adjustments (76.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.002<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 404.3
- 400 + ( ( 0.002 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 404.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      190 | 2025-02-21 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |    -2.07 | Bambosh, ERSIN, levantino, Polbandana, Tr0ublE |
|            4 |      206 | 2025-02-21 | Minsk House        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.188 (0.027)    | 0 (0.000) |    17.68 | Bambosh, ERSIN, levantino, Polbandana, Tr0ublE |
|            3 |      214 | 2025-02-21 | Informmix          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |    19.37 | Bambosh, ERSIN, levantino, Polbandana, Tr0ublE |
|            2 |      225 | 2025-02-21 | Wolves eSports     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |    18.18 | Bambosh, ERSIN, levantino, Polbandana, Tr0ublE |
|            1 |      257 | 2025-02-20 | MOUZ NXT           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.183 (0.026)    | 0 (0.000) |    23.38 | Bambosh, ERSIN, levantino, Polbandana, Tr0ublE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
