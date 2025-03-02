### Roster Details<br />
Team Name: GOOFYBOYZ<br />
Roster: c0mplex, Jayy2s, MattyMyimb, shaRpy, snowiee<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
<br />
Final Rank Value:  745.6<br />
<br />
Final Rank Value (745.6) = Starting Rank Value (761.6) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.230[<sup>2</sup>](#table1)

The average of these factors is 0.181<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 761.6
- 400 + ( ( 0.181 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 761.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1300 | 2024-12-28 | Rhyno Youngsters         | L   | 0.779      | -            | -                | -                | -         |   -13.29 | c0mplex, Jayy2s, MattyMyimb, shaRpy, snowiee |
|           25 |     1403 | 2024-12-22 | Rhyno Youngsters         | L   | 0.739      | -            | -                | -                | -         |   -13.23 | Jayy2s, MattyMyimb, nesto, snowiee, TMKj     |
|           24 |     1478 | 2024-12-21 | ATOMIC (Portuguese team) | W   | 0.731      | 0.143        | 0.000 (0.000)    | -                | 1 (0.731) |     4.16 | Jayy2s, MattyMyimb, nesto, snowiee, TMKj     |
|           23 |     3321 | 2024-11-16 | Iberian Soul             | L   | 0.499      | -            | -                | -                | -         |    -6.55 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           22 |     4032 | 2024-11-03 | The Agency Clan          | W   | 0.414      | 0.143        | 0.006 (0.000)    | 0.295 (0.017)    | 1 (0.414) |     7.98 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           21 |     4049 | 2024-11-03 | Rhyno Youngsters         | W   | 0.413      | 0.143        | 0.003 (0.000)    | 0.121 (0.007)    | 1 (0.413) |     6.29 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           20 |     4081 | 2024-11-03 | Nordics Esports          | W   | 0.411      | 0.143        | 0.000 (0.000)    | -                | 1 (0.411) |     1.53 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           19 |     4359 | 2024-10-29 | Impulse GW               | W   | 0.380      | 0.143        | 0.006 (0.000)    | 0.172 (0.009)    | 0 (0.000) |     5.58 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           18 |     4433 | 2024-10-28 | TGD Pro                  | W   | 0.373      | 0.143        | -                | 0.047 (0.002)    | 0 (0.000) |     1.53 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           17 |     4523 | 2024-10-26 | Rhyno Esports            | L   | 0.359      | -            | -                | -                | -         |    -4.06 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           16 |     4554 | 2024-10-26 | Mixzada                  | W   | 0.357      | 0.143        | 0.000 (0.000)    | 0.032 (0.002)    | 0 (0.000) |     3.38 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           15 |     4592 | 2024-10-25 | Energise Club            | W   | 0.352      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | 0 (0.000) |     2.25 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           14 |     4621 | 2024-10-24 | FALKE ESPORTS            | W   | 0.346      | 0.143        | -                | 0.042 (0.002)    | 0 (0.000) |     1.39 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           13 |     4669 | 2024-10-23 | Rhyno Youngsters         | W   | 0.339      | 0.143        | 0.003 (0.000)    | 0.121 (0.006)    | 0 (0.000) |     5.45 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           12 |     4704 | 2024-10-22 | Impulse GW               | L   | 0.333      | -            | -                | -                | -         |    -5.52 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           11 |     4780 | 2024-10-20 | The Agency Clan          | W   | 0.319      | 0.143        | 0.006 (0.000)    | 0.295 (0.013)    | -         |     6.41 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           10 |     4840 | 2024-10-19 | Talaintanse              | L   | 0.313      | -            | -                | -                | -         |    -8.01 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|            9 |     5257 | 2024-10-11 | Mixzada                  | L   | 0.259      | -            | -                | -                | -         |    -5.77 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|            8 |     6696 | 2024-09-19 | SQUAD (Portuguese team)  | L   | 0.113      | -            | -                | -                | -         |    -2.92 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            7 |     6763 | 2024-09-18 | EXSAD Gaming             | W   | 0.106      | -            | -                | -                | -         |     0.57 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            6 |     6881 | 2024-09-16 | Rhyno Youngsters         | L   | 0.093      | -            | -                | -                | -         |    -1.49 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            5 |     7281 | 2024-09-09 | Divergent                | L   | 0.047      | -            | -                | -                | -         |    -1.22 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            4 |     7343 | 2024-09-08 | FALKE ESPORTS            | W   | 0.039      | -            | -                | -                | -         |     0.14 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            3 |     7395 | 2024-09-07 | ALTERNATE aTTaX Evo      | W   | 0.033      | 0.333        | 0.001 (0.000)    | 0.184 (0.002)    | -         |     0.31 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            2 |     7419 | 2024-09-07 | TGD Pro                  | L   | 0.033      | -            | -                | -                | -         |    -0.85 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            1 |     7713 | 2024-09-03 | XI Esport                | L   | 0.007      | -            | -                | -                | -         |    -0.13 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($948.32)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.741 | $104.30        | $77.25          |
| 2024-11-17 |      0.506 | $1,054.46      | $533.09         |
| 2024-11-03 |      0.414 | $816.06        | $337.98         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
