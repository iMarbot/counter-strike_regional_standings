### Roster Details<br />
Team Name: GOOFYBOYZ<br />
Roster: c0mplex, Jayy2s, MattyMyimb, shaRpy, snowiee<br />
Global Rank: [162](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
<br />
Final Rank Value:  745.2<br />
<br />
Final Rank Value (745.2) = Starting Rank Value (760.4) + Head To Head Adjustments (-15.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.227[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 760.4
- 400 + ( ( 0.180 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 760.4


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
|           25 |     1312 | 2024-12-28 | Rhyno Youngsters         | L   | 0.771      | -            | -                | -                | -         |   -13.14 | c0mplex, Jayy2s, MattyMyimb, shaRpy, snowiee |
|           24 |     1415 | 2024-12-22 | Rhyno Youngsters         | L   | 0.731      | -            | -                | -                | -         |   -13.07 | Jayy2s, MattyMyimb, nesto, snowiee, TMKj     |
|           23 |     1490 | 2024-12-21 | ATOMIC (Portuguese team) | W   | 0.723      | 0.143        | 0.000 (0.000)    | -                | 1 (0.723) |     4.13 | Jayy2s, MattyMyimb, nesto, snowiee, TMKj     |
|           22 |     3333 | 2024-11-16 | Iberian Soul             | L   | 0.491      | -            | -                | -                | -         |    -6.45 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           21 |     4044 | 2024-11-03 | The Agency Clan          | W   | 0.406      | 0.143        | 0.006 (0.000)    | 0.292 (0.017)    | 1 (0.406) |     7.82 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           20 |     4061 | 2024-11-03 | Rhyno Youngsters         | W   | 0.405      | 0.143        | 0.003 (0.000)    | 0.118 (0.007)    | 1 (0.405) |     6.16 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           19 |     4093 | 2024-11-03 | Nordics Esports          | W   | 0.403      | 0.143        | 0.000 (0.000)    | -                | 1 (0.403) |     1.50 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           18 |     4371 | 2024-10-29 | Impulse GW               | W   | 0.372      | 0.143        | 0.006 (0.000)    | 0.169 (0.009)    | 0 (0.000) |     5.47 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           17 |     4445 | 2024-10-28 | TGD Pro                  | W   | 0.365      | 0.143        | -                | 0.046 (0.002)    | 0 (0.000) |     1.50 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           16 |     4535 | 2024-10-26 | Rhyno Esports            | L   | 0.350      | -            | -                | -                | -         |    -4.00 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           15 |     4566 | 2024-10-26 | Mixzada                  | W   | 0.349      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | 0 (0.000) |     3.31 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           14 |     4604 | 2024-10-25 | Energise Club            | W   | 0.344      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | 0 (0.000) |     2.20 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           13 |     4633 | 2024-10-24 | FALKE ESPORTS            | W   | 0.338      | 0.143        | -                | 0.041 (0.002)    | 0 (0.000) |     1.36 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           12 |     4681 | 2024-10-23 | Rhyno Youngsters         | W   | 0.331      | 0.143        | 0.003 (0.000)    | 0.118 (0.006)    | 0 (0.000) |     5.31 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           11 |     4716 | 2024-10-22 | Impulse GW               | L   | 0.324      | -            | -                | -                | -         |    -5.37 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|           10 |     4792 | 2024-10-20 | The Agency Clan          | W   | 0.311      | 0.143        | 0.006 (0.000)    | 0.292 (0.013)    | -         |     6.23 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|            9 |     4852 | 2024-10-19 | Talaintanse              | L   | 0.305      | -            | -                | -                | -         |    -7.80 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|            8 |     5269 | 2024-10-11 | Mixzada                  | L   | 0.251      | -            | -                | -                | -         |    -5.58 | drext, Jayy2s, MattyMyimb, nesto, snowiee    |
|            7 |     6708 | 2024-09-19 | SQUAD (Portuguese team)  | L   | 0.104      | -            | -                | -                | -         |    -2.71 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            6 |     6775 | 2024-09-18 | EXSAD Gaming             | W   | 0.098      | -            | -                | -                | -         |     0.52 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            5 |     6893 | 2024-09-16 | Rhyno Youngsters         | L   | 0.085      | -            | -                | -                | -         |    -1.36 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            4 |     7293 | 2024-09-09 | Divergent                | L   | 0.038      | -            | -                | -                | -         |    -1.00 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            3 |     7355 | 2024-09-08 | FALKE ESPORTS            | W   | 0.031      | -            | -                | -                | -         |     0.12 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            2 |     7407 | 2024-09-07 | ALTERNATE aTTaX Evo      | W   | 0.025      | 0.333        | 0.001 (0.000)    | 0.178 (0.001)    | -         |     0.24 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |
|            1 |     7431 | 2024-09-07 | TGD Pro                  | L   | 0.024      | -            | -                | -                | -         |    -0.64 | c0mplex, Jayy2s, kabul, Mané, MattyMyimb     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($932.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $104.30        | $76.39          |
| 2024-11-17 |      0.497 | $1,054.46      | $524.45         |
| 2024-11-03 |      0.406 | $816.06        | $331.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
