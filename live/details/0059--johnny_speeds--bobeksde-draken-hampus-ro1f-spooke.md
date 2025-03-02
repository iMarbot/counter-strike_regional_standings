### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: bobeksde, draken, hampus, Ro1f, spooke<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
<br />
Final Rank Value:  933.5<br />
<br />
Final Rank Value (933.5) = Starting Rank Value (895.4) + Head To Head Adjustments (38.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.076[<sup>2</sup>](#table1)
- LAN Wins: 0.188[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.4
- 400 + ( ( 0.248 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 895.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |     2870 | 2024-11-23 | Alliance             | W   | 0.546      | -            | -                | -                | 1 (0.546) |     7.49 | bobeksde, draken, hampus, Ro1f, spooke |
|           45 |     2887 | 2024-11-23 | Monte                | L   | 0.546      | -            | -                | -                | -         |    -9.64 | bobeksde, draken, hampus, Ro1f, spooke |
|           44 |     3011 | 2024-11-21 | Kappa Bar            | W   | 0.533      | -            | -                | -                | 1 (0.533) |     3.98 | bobeksde, draken, hampus, Ro1f, spooke |
|           43 |     3040 | 2024-11-21 | Alliance             | W   | 0.532      | -            | -                | -                | 1 (0.532) |     7.32 | bobeksde, draken, hampus, Ro1f, spooke |
|           42 |     3647 | 2024-11-10 | OG                   | W   | 0.460      | 0.143        | 0.062 (0.004)    | 1.000 (0.066)    | 0 (0.000) |     7.27 | bobeksde, draken, hampus, Ro1f, spooke |
|           41 |     3779 | 2024-11-08 | Metizport            | L   | 0.447      | -            | -                | -                | -         |    -4.04 | bobeksde, draken, hampus, Ro1f, spooke |
|           40 |     3805 | 2024-11-08 | Zero Tenacity        | L   | 0.445      | -            | -                | -                | -         |    -8.22 | bobeksde, draken, hampus, Ro1f, spooke |
|           39 |     3903 | 2024-11-06 | Dynamo Eclot         | L   | 0.431      | -            | -                | -                | -         |    -4.36 | bobeksde, draken, hampus, Ro1f, spooke |
|           38 |     3942 | 2024-11-05 | Showmakerz           | W   | 0.426      | -            | -                | -                | 0 (0.000) |     1.86 | bobeksde, draken, hampus, Ro1f, spooke |
|           37 |     4005 | 2024-11-04 | HOTU                 | W   | 0.419      | 0.384        | -                | 0.777 (0.125)    | 0 (0.000) |     2.83 | bobeksde, draken, hampus, Ro1f, spooke |
|           36 |     4044 | 2024-11-03 | Insilio              | W   | 0.413      | -            | -                | -                | 0 (0.000) |     2.15 | bobeksde, draken, hampus, Ro1f, spooke |
|           35 |     4200 | 2024-11-01 | OG                   | W   | 0.399      | 0.384        | 0.062 (0.009)    | 1.000 (0.153)    | 0 (0.000) |     6.33 | bobeksde, draken, hampus, Ro1f, spooke |
|           34 |     4237 | 2024-10-31 | ECSTATIC             | L   | 0.394      | -            | -                | -                | -         |    -6.68 | bobeksde, draken, hampus, Ro1f, spooke |
|           33 |     4248 | 2024-10-31 | Metizport            | W   | 0.393      | 0.333        | 0.074 (0.010)    | 0.513 (0.067)    | 0 (0.000) |     8.89 | bobeksde, draken, hampus, Ro1f, spooke |
|           32 |     4325 | 2024-10-30 | 9Pandas              | L   | 0.385      | -            | -                | -                | -         |    -4.90 | bobeksde, draken, hampus, Ro1f, spooke |
|           31 |     4351 | 2024-10-29 | Endpoint             | W   | 0.381      | -            | -                | -                | 0 (0.000) |     4.08 | bobeksde, draken, hampus, Ro1f, spooke |
|           30 |     4362 | 2024-10-29 | Tricked Esport       | L   | 0.380      | -            | -                | -                | -         |    -7.04 | bobeksde, draken, hampus, Ro1f, spooke |
|           29 |     4374 | 2024-10-29 | Rare Atom            | W   | 0.379      | 0.333        | 0.063 (0.008)    | 0.581 (0.073)    | -         |     7.11 | bobeksde, draken, hampus, Ro1f, spooke |
|           28 |     4528 | 2024-10-26 | Nexus Gaming         | W   | 0.358      | 0.143        | 0.186 (0.010)    | -                | -         |     8.58 | bobeksde, draken, hampus, Ro1f, spooke |
|           27 |     4750 | 2024-10-21 | UNiTY esports        | W   | 0.325      | 0.384        | 0.025 (0.003)    | 0.412 (0.051)    | -         |     4.38 | bobeksde, draken, hampus, Ro1f, spooke |
|           26 |     4790 | 2024-10-20 | Wild Lotus           | L   | 0.319      | -            | -                | -                | -         |    -7.07 | bobeksde, draken, hampus, Ro1f, spooke |
|           25 |     5018 | 2024-10-16 | WW Team              | W   | 0.291      | -            | -                | -                | -         |     0.87 | bobeksde, draken, hampus, Ro1f, spooke |
|           24 |     5493 | 2024-10-07 | Preasy Esport        | W   | 0.231      | 0.384        | -                | 0.710 (0.063)    | -         |     2.56 | bobeksde, draken, hampus, Ro1f, spooke |
|           23 |     5518 | 2024-10-06 | EYEBALLERS           | W   | 0.226      | -            | -                | -                | -         |     2.58 | bobeksde, draken, hampus, Ro1f, spooke |
|           22 |     5530 | 2024-10-06 | Fightclub            | W   | 0.225      | -            | -                | -                | -         |     0.60 | bobeksde, draken, hampus, Ro1f, spooke |
|           21 |     5546 | 2024-10-06 | GTZ.ESPORTS          | W   | 0.224      | 0.143        | 0.080 (0.003)    | -                | -         |     6.08 | bobeksde, draken, hampus, Ro1f, spooke |
|           20 |     5600 | 2024-10-05 | Metizport X          | W   | 0.219      | -            | -                | -                | -         |     1.43 | bobeksde, draken, hampus, Ro1f, spooke |
|           19 |     5608 | 2024-10-05 | ENCE Academy         | W   | 0.218      | -            | -                | -                | -         |     2.68 | bobeksde, draken, hampus, Ro1f, spooke |
|           18 |     5671 | 2024-10-04 | Natus Vincere Junior | W   | 0.212      | 0.333        | 0.091 (0.006)    | 0.878 (0.062)    | -         |     4.02 | bobeksde, draken, hampus, Ro1f, spooke |
|           17 |     5718 | 2024-10-03 | Partizan Esports     | W   | 0.206      | 0.333        | 0.082 (0.006)    | 0.768 (0.053)    | -         |     4.87 | bobeksde, draken, hampus, Ro1f, spooke |
|           16 |     5878 | 2024-10-01 | Los kogutos          | L   | 0.190      | -            | -                | -                | -         |    -2.18 | bobeksde, draken, hampus, Ro1f, spooke |
|           15 |     5913 | 2024-09-30 | MOUZ NXT             | W   | 0.186      | -            | -                | -                | -         |     0.81 | bobeksde, draken, hampus, Ro1f, spooke |
|           14 |     5931 | 2024-09-30 | Tricked Esport       | L   | 0.184      | -            | -                | -                | -         |    -3.38 | bobeksde, draken, hampus, Ro1f, spooke |
|           13 |     6038 | 2024-09-28 | ARCRED               | W   | 0.172      | -            | -                | -                | -         |     1.75 | bobeksde, draken, hampus, Ro1f, spooke |
|           12 |     6072 | 2024-09-28 | Wild Lotus           | L   | 0.171      | -            | -                | -                | -         |    -3.70 | bobeksde, draken, hampus, Ro1f, spooke |
|           11 |     6270 | 2024-09-25 | Lazer Cats           | L   | 0.154      | -            | -                | -                | -         |    -3.50 | bobeksde, draken, hampus, Ro1f, spooke |
|           10 |     6463 | 2024-09-23 | Nemiga Gaming        | L   | 0.140      | -            | -                | -                | -         |    -1.50 | bobeksde, draken, hampus, Ro1f, spooke |
|            9 |     6477 | 2024-09-23 | 9INE                 | L   | 0.139      | -            | -                | -                | -         |    -2.98 | bobeksde, draken, hampus, Ro1f, spooke |
|            8 |     6484 | 2024-09-23 | GameAgents           | W   | 0.138      | -            | -                | -                | -         |     1.02 | bobeksde, draken, hampus, Ro1f, spooke |
|            7 |     6643 | 2024-09-20 | Devils.one           | W   | 0.118      | -            | -                | -                | -         |     0.77 | bobeksde, draken, hampus, Ro1f, spooke |
|            6 |     6682 | 2024-09-19 | CYBERSHOKE Esports   | W   | 0.113      | 0.443        | -                | 1.000 (0.050)    | -         |     1.60 | bobeksde, draken, hampus, Ro1f, spooke |
|            5 |     6709 | 2024-09-19 | Alliance             | W   | 0.111      | -            | -                | -                | -         |     1.75 | bobeksde, draken, hampus, Ro1f, spooke |
|            4 |     6941 | 2024-09-15 | 9Pandas              | W   | 0.085      | 0.443        | 0.085 (0.003)    | -                | -         |     1.65 | bobeksde, draken, hampus, Ro1f, spooke |
|            3 |     6952 | 2024-09-15 | K27                  | W   | 0.084      | -            | -                | -                | -         |     1.47 | bobeksde, draken, hampus, Ro1f, spooke |
|            2 |     7103 | 2024-09-13 | Rebels Gaming        | L   | 0.071      | -            | -                | -                | -         |    -1.60 | bobeksde, draken, hampus, Ro1f, spooke |
|            1 |     7663 | 2024-09-04 | Kappa Bar            | W   | 0.013      | -            | -                | -                | -         |     0.11 | bobeksde, draken, hampus, Ro1f, spooke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,268.47)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $1,864.89      | $1,029.83       |
| 2024-11-23 |      0.546 | $10,873.30     | $5,940.30       |
| 2024-11-09 |      0.453 | $4,623.93      | $2,093.61       |
| 2024-10-31 |      0.394 | $2,000.00      | $787.50         |
| 2024-10-06 |      0.226 | $4,821.41      | $1,089.73       |
| 2024-10-05 |      0.218 | $5,000.00      | $1,090.28       |
| 2024-09-24 |      0.145 | $8,000.00      | $1,157.78       |
| 2024-09-14 |      0.079 | $1,000.00      | $79.44          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
