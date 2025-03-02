### Roster Details<br />
Team Name: INTERDIT<br />
Roster: KLR, kxr, polarzyn, respect, vzn<br />
Global Rank: [401](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [86]( ../standings_americas.md)<br />
<br />
Final Rank Value:  596.0<br />
<br />
Final Rank Value (596.0) = Starting Rank Value (613.8) + Head To Head Adjustments (-17.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.198[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.107<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 613.8
- 400 + ( ( 0.107 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 613.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     2469 | 2024-11-30 | Sharks Youngsters         | L   | 0.594      | -            | -                | -                | -         |   -10.16 | KLR, kxr, polarzyn, respect, vzn        |
|           15 |     2490 | 2024-11-30 | VELOX Argentina           | L   | 0.594      | -            | -                | -                | -         |    -9.88 | KLR, kxr, polarzyn, respect, vzn        |
|           14 |     2696 | 2024-11-26 | América eSports           | L   | 0.568      | -            | -                | -                | -         |    -9.38 | freitas, kxr, polarzyn, respect, vzn    |
|           13 |     2779 | 2024-11-24 | DB Peek Esports           | W   | 0.553      | 0.143        | 0.000 (0.000)    | 0.240 (0.019)    | 0 (0.000) |     8.71 | freitas, kxr, polarzyn, respect, vzn    |
|           12 |     2824 | 2024-11-23 | ArtGamerz                 | W   | 0.547      | 0.143        | 0.000 (0.000)    | 0.030 (0.002)    | 0 (0.000) |     5.39 | freitas, kxr, polarzyn, respect, vzn    |
|           11 |     2851 | 2024-11-23 | Guará eSports             | W   | 0.547      | 0.143        | 0.000 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     5.53 | freitas, kxr, polarzyn, respect, vzn    |
|           10 |     3645 | 2024-11-10 | Team Leveling             | L   | 0.460      | -            | -                | -                | -         |    -9.51 | freitas, kxr, polarzyn, respect, spider |
|            9 |     3696 | 2024-11-09 | Nova holanda              | W   | 0.454      | 0.143        | 0.000 (0.000)    | 0.090 (0.006)    | 0 (0.000) |     7.01 | freitas, kxr, polarzyn, respect, spider |
|            8 |     3702 | 2024-11-09 | SamuraiS (Brazilian team) | L   | 0.454      | -            | -                | -                | -         |    -9.17 | freitas, kxr, polarzyn, respect, spider |
|            7 |     3970 | 2024-11-04 | Nova holanda              | L   | 0.421      | -            | -                | -                | -         |    -6.86 | freitas, kxr, polarzyn, respect, vzn    |
|            6 |     4102 | 2024-11-02 | FURIA Esports Female      | W   | 0.408      | 0.143        | 0.064 (0.004)    | 0.223 (0.013)    | 0 (0.000) |    11.21 | freitas, kxr, polarzyn, respect, vzn    |
|            5 |     4117 | 2024-11-02 | Floripa Stars Academy     | W   | 0.407      | 0.143        | 0.000 (0.000)    | 0.051 (0.003)    | 0 (0.000) |     4.14 | freitas, kxr, polarzyn, respect, vzn    |
|            4 |     5322 | 2024-10-09 | Myth e-Sports             | L   | 0.248      | -            | -                | -                | -         |    -4.08 | freitas, KLR, kxr, polarzyn, respect    |
|            3 |     5394 | 2024-10-08 | América eSports           | W   | 0.241      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.38 | freitas, KLR, kxr, polarzyn, respect    |
|            2 |     5558 | 2024-10-05 | Team Leveling             | L   | 0.221      | -            | -                | -                | -         |    -4.67 | freitas, KLR, kxr, polarzyn, respect    |
|            1 |     5569 | 2024-10-05 | Chape E-sports            | W   | 0.220      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.60 | freitas, KLR, kxr, polarzyn, respect    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29.37)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-26 |      0.568 | $51.74         | $29.37          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
