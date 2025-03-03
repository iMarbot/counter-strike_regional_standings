### Roster Details<br />
Team Name: INTERDIT<br />
Roster: KLR, kxr, polarzyn, respect, vzn<br />
Global Rank: [405](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [90]( ../standings_americas.md)<br />
<br />
Final Rank Value:  594.6<br />
<br />
Final Rank Value (594.6) = Starting Rank Value (613.9) + Head To Head Adjustments (-19.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.198[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.107<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 613.9
- 400 + ( ( 0.107 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 613.9


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
|           16 |     2481 | 2024-11-30 | Sharks Youngsters         | L   | 0.586      | -            | -                | -                | -         |    -9.97 | KLR, kxr, polarzyn, respect, vzn        |
|           15 |     2502 | 2024-11-30 | VELOX Argentina           | L   | 0.585      | -            | -                | -                | -         |   -11.15 | KLR, kxr, polarzyn, respect, vzn        |
|           14 |     2708 | 2024-11-26 | América eSports           | L   | 0.560      | -            | -                | -                | -         |    -9.23 | freitas, kxr, polarzyn, respect, vzn    |
|           13 |     2791 | 2024-11-24 | DB Peek Esports           | W   | 0.545      | 0.143        | 0.000 (0.000)    | 0.236 (0.018)    | 0 (0.000) |     8.59 | freitas, kxr, polarzyn, respect, vzn    |
|           12 |     2836 | 2024-11-23 | ArtGamerz                 | W   | 0.539      | 0.143        | 0.000 (0.000)    | 0.030 (0.002)    | 0 (0.000) |     5.32 | freitas, kxr, polarzyn, respect, vzn    |
|           11 |     2863 | 2024-11-23 | Guará eSports             | W   | 0.538      | 0.143        | 0.000 (0.000)    | 0.028 (0.002)    | 0 (0.000) |     5.46 | freitas, kxr, polarzyn, respect, vzn    |
|           10 |     3657 | 2024-11-10 | Team Leveling             | L   | 0.452      | -            | -                | -                | -         |    -9.34 | freitas, kxr, polarzyn, respect, spider |
|            9 |     3708 | 2024-11-09 | Nova holanda              | W   | 0.446      | 0.143        | 0.000 (0.000)    | 0.089 (0.006)    | 0 (0.000) |     6.89 | freitas, kxr, polarzyn, respect, spider |
|            8 |     3714 | 2024-11-09 | SamuraiS (Brazilian team) | L   | 0.445      | -            | -                | -                | -         |    -9.01 | freitas, kxr, polarzyn, respect, spider |
|            7 |     3982 | 2024-11-04 | Nova holanda              | L   | 0.412      | -            | -                | -                | -         |    -6.72 | freitas, kxr, polarzyn, respect, vzn    |
|            6 |     4114 | 2024-11-02 | FURIA Esports Female      | W   | 0.399      | 0.143        | 0.064 (0.004)    | 0.218 (0.012)    | 0 (0.000) |    10.98 | freitas, kxr, polarzyn, respect, vzn    |
|            5 |     4129 | 2024-11-02 | Floripa Stars Academy     | W   | 0.398      | 0.143        | 0.000 (0.000)    | 0.050 (0.003)    | 0 (0.000) |     4.07 | freitas, kxr, polarzyn, respect, vzn    |
|            4 |     5334 | 2024-10-09 | Myth e-Sports             | L   | 0.239      | -            | -                | -                | -         |    -3.94 | freitas, KLR, kxr, polarzyn, respect    |
|            3 |     5406 | 2024-10-08 | América eSports           | W   | 0.233      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.73 | freitas, KLR, kxr, polarzyn, respect    |
|            2 |     5570 | 2024-10-05 | Team Leveling             | L   | 0.212      | -            | -                | -                | -         |    -4.50 | freitas, KLR, kxr, polarzyn, respect    |
|            1 |     5581 | 2024-10-05 | Chape E-sports            | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.54 | freitas, KLR, kxr, polarzyn, respect    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28.95)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-26 |      0.560 | $51.74         | $28.95          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
