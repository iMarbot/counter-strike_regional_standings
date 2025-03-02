### Roster Details<br />
Team Name: Akimbo Esports<br />
Roster: consti, kmrn, laxiee, N2o, zy<br />
Global Rank: [370](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [59]( ../standings_asia.md)<br />
<br />
Final Rank Value:  610.9<br />
<br />
Final Rank Value (610.9) = Starting Rank Value (649.1) + Head To Head Adjustments (-38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.200[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.004[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 649.1
- 400 + ( ( 0.125 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 649.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       78 | 2025-02-23 | Rolling Stone             | L   | 1.000      | -            | -                | -                | -         |   -20.24 | consti, kmrn, laxiee, N2o, zy   |
|           27 |      116 | 2025-02-22 | MILKED                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.77 | consti, kmrn, laxiee, N2o, zy   |
|           26 |      316 | 2025-02-16 | NuTorious                 | L   | 1.000      | -            | -                | -                | -         |   -21.24 | consti, kmrn, laxiee, obi, zy   |
|           25 |      651 | 2025-02-08 | Party Astronauts          | L   | 1.000      | -            | -                | -                | -         |    -8.95 | consti, kmrn, laxiee, obi, zy   |
|           24 |      656 | 2025-02-08 | BACKWHENEVER              | W   | 1.000      | 0.143        | -                | 0.047 (0.007)    | 0 (0.000) |     9.94 | consti, kmrn, laxiee, obi, zy   |
|           23 |      729 | 2025-02-07 | Aetheris                  | W   | 1.000      | 0.143        | -                | 0.140 (0.020)    | 0 (0.000) |     6.41 | consti, kmrn, laxiee, obi, zy   |
|           22 |      811 | 2025-02-06 | Exceritus                 | L   | 1.000      | -            | -                | -                | -         |   -16.99 | calamity, kmrn, laxiee, obi, zy |
|           21 |      812 | 2025-02-06 | Blahaj                    | L   | 1.000      | -            | -                | -                | -         |   -20.42 | calamity, kmrn, laxiee, obi, zy |
|           20 |      813 | 2025-02-06 | MarcaRegistrada           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.125 (0.018)    | 0 (0.000) |    13.06 | calamity, kmrn, laxiee, obi, zy |
|           19 |     1742 | 2024-12-13 | Vagrants                  | L   | 0.682      | -            | -                | -                | -         |   -10.59 | kmrn, laxiee, N2o, obi, zy      |
|           18 |     1751 | 2024-12-13 | MCS Gaming                | W   | 0.682      | 0.143        | 0.003 (0.000)    | 0.344 (0.034)    | 0 (0.000) |     9.90 | kmrn, laxiee, N2o, obi, zy      |
|           17 |     2924 | 2024-11-22 | Vagrants                  | W   | 0.542      | 0.143        | -                | 0.051 (0.004)    | 0 (0.000) |     3.49 | danss, laxiee, N2o, obi, zy     |
|           16 |     2931 | 2024-11-22 | Revel                     | W   | 0.542      | 0.143        | -                | 0.025 (0.002)    | 0 (0.000) |     3.38 | danss, laxiee, N2o, obi, zy     |
|           15 |     2937 | 2024-11-22 | Final Form                | W   | 0.542      | 0.143        | -                | 0.057 (0.004)    | 0 (0.000) |     3.31 | danss, laxiee, N2o, obi, zy     |
|           14 |     5168 | 2024-10-12 | Alter Iron Club           | L   | 0.268      | -            | -                | -                | -         |    -3.81 | danss, kmrn, N2o, obi, zy       |
|           13 |     5384 | 2024-10-08 | Redacted Society          | W   | 0.241      | 0.259        | 0.000 (0.000)    | -                | 0 (0.000) |     2.23 | danss, kmrn, N2o, obi, zy       |
|           12 |     5944 | 2024-09-29 | LAG Gaming                | L   | 0.181      | -            | -                | -                | -         |    -3.21 | kmrn, laxiee, N2o, obi, zy      |
|           11 |     6542 | 2024-09-21 | Undefined (American team) | W   | 0.128      | 0.372        | 0.002 (0.000)    | -                | -         |     1.86 | kmrn, laxiee, N2o, obi, zy      |
|           10 |     6548 | 2024-09-21 | Familia Maquininha        | W   | 0.128      | 0.371        | 0.003 (0.000)    | 0.205 (0.010)    | -         |     2.17 | kmrn, N2o, obi, taggy, zy       |
|            9 |     6802 | 2024-09-17 | Homyno                    | W   | 0.101      | 0.371        | 0.008 (0.000)    | 0.192 (0.007)    | -         |     1.85 | kmrn, laxiee, N2o, obi, zy      |
|            8 |     7158 | 2024-09-11 | Team Aether               | W   | 0.062      | -            | -                | -                | -         |     0.59 | kmrn, laxiee, N2o, obi, zy      |
|            7 |     7218 | 2024-09-10 | InControl                 | W   | 0.055      | 0.372        | 0.001 (0.000)    | -                | -         |     0.83 | kmrn, laxiee, N2o, obi, zy      |
|            6 |     7267 | 2024-09-09 | Homyno                    | W   | 0.049      | 0.372        | 0.008 (0.000)    | 0.192 (0.003)    | -         |     0.90 | kmrn, laxiee, N2o, obi, zy      |
|            5 |     7324 | 2024-09-08 | Undefined (American team) | W   | 0.042      | 0.372        | 0.002 (0.000)    | -                | -         |     0.61 | kmrn, laxiee, N2o, obi, zy      |
|            4 |     7378 | 2024-09-07 | Nouns Esports             | L   | 0.035      | -            | -                | -                | -         |    -0.43 | kmrn, laxiee, N2o, obi, zy      |
|            3 |     7383 | 2024-09-07 | Unjustified Gaming        | W   | 0.034      | -            | -                | -                | 1 (0.034) |     0.21 | kmrn, laxiee, N2o, obi, zy      |
|            2 |     7631 | 2024-09-04 | Take Flyte FRAUDS         | W   | 0.015      | -            | -                | -                | -         |     0.14 | kmrn, laxiee, N2o, obi, zy      |
|            1 |     7692 | 2024-09-03 | LOSTHILLS                 | W   | 0.008      | -            | -                | -                | -         |     0.05 | kmrn, laxiee, N2o, obi, taggy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,006.64)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-12 |      0.268 | $400.00        | $107.33         |
| 2024-09-21 |      0.128 | $7,000.00      | $899.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
