### Roster Details<br />
Team Name: MCS Gaming<br />
Roster: Goodbye, Oczarka, ogura, Scorchyy, snufaffu<br />
Global Rank: [282](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
<br />
Final Rank Value:  661.1<br />
<br />
Final Rank Value (661.1) = Starting Rank Value (654.6) + Head To Head Adjustments (6.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 654.6
- 400 + ( ( 0.127 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 654.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      386 | 2025-02-15 | Regain                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.157 (0.022)    | 0 (0.000) |    10.29 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           24 |      387 | 2025-02-15 | MarcaRegistrada           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.125 (0.018)    | 0 (0.000) |    13.56 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           23 |      438 | 2025-02-14 | MIGHT                     | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.444 (0.063)    | 0 (0.000) |    19.02 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           22 |      575 | 2025-02-10 | Marsborne                 | L   | 1.000      | -            | -                | -                | -         |   -16.59 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           21 |      617 | 2025-02-09 | Bad News Capybaras        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.115 (0.016)    | 0 (0.000) |    15.74 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           20 |      666 | 2025-02-08 | Marsborne                 | L   | 1.000      | -            | -                | -                | -         |   -19.01 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           19 |      733 | 2025-02-07 | BACKWHENEVER              | L   | 1.000      | -            | -                | -                | -         |   -21.78 | Goodbye, Oczarka, ogura, Scorchyy, snuffafu        |
|           18 |      818 | 2025-02-06 | MIGHT                     | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.444 (0.063)    | 0 (0.000) |    18.28 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           17 |      827 | 2025-02-06 | Straight2Killin           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |     9.46 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           16 |     1751 | 2024-12-13 | Akimbo Esports            | L   | 0.682      | -            | -                | -                | -         |    -9.90 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           15 |     2153 | 2024-12-05 | Bad Boys                  | L   | 0.629      | -            | -                | -                | -         |    -9.31 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           14 |     2308 | 2024-12-02 | Chicken Coop Esports      | L   | 0.609      | -            | -                | -                | -         |    -8.48 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           13 |     2378 | 2024-12-01 | StandOnBusiness           | W   | 0.602      | 0.372        | 0.000 (0.000)    | 0.054 (0.012)    | 0 (0.000) |     3.93 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           12 |     2566 | 2024-11-29 | Final Form                | W   | 0.589      | 0.372        | -                | 0.057 (0.012)    | 0 (0.000) |     3.55 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           11 |     2688 | 2024-11-26 | Immigrants Peek           | W   | 0.569      | 0.372        | 0.001 (0.000)    | 0.366 (0.078)    | 0 (0.000) |     8.69 | Goodbye, Oczarka, ogura, Scorchyy, snufaffu        |
|           10 |     2764 | 2024-11-24 | Make Your Mind            | L   | 0.556      | -            | -                | -                | -         |    -7.34 | jBREEEZY, Oczarka, ogura, Scorchyy, snufaffu       |
|            9 |     2769 | 2024-11-24 | HRT N ADDERALL            | W   | 0.554      | 0.233        | 0.000 (0.000)    | -                | 0 (0.000) |     5.26 | jBREEEZY, Oczarka, ogura, Scorchyy, snufaffu       |
|            8 |     4824 | 2024-10-19 | Timbermen                 | L   | 0.316      | -            | -                | -                | -         |    -4.64 | GibbyATL, Goodbye, ogura, Scorchyy, snufaffu       |
|            7 |     5172 | 2024-10-12 | FLUFFY AIMERS             | L   | 0.268      | -            | -                | -                | -         |    -2.58 | jBREEEZY, Oczarka, Scorchyy, snufaffu, Stay_Classy |
|            6 |     5181 | 2024-10-12 | InControl                 | L   | 0.267      | -            | -                | -                | -         |    -4.51 | jBREEEZY, Oczarka, Scorchyy, snufaffu, Stay_Classy |
|            5 |     5184 | 2024-10-12 | Bad News Capybaras        | W   | 0.267      | 0.262        | 0.001 (0.000)    | 0.115 (0.008)    | -         |     4.18 | jBREEEZY, Oczarka, Scorchyy, snufaffu, Stay_Classy |
|            4 |     7219 | 2024-09-10 | Take Flyte FRAUDS         | L   | 0.055      | -            | -                | -                | -         |    -1.26 | Goodbye, Oczarka, Scorchyy, snufaffu, Stay_Classy  |
|            3 |     7326 | 2024-09-08 | LazerrFreeks8             | W   | 0.042      | -            | -                | -                | -         |     0.25 | Goodbye, Oczarka, Scorchyy, snufaffu, Stay_Classy  |
|            2 |     7547 | 2024-09-05 | Undefined (American team) | L   | 0.022      | -            | -                | -                | -         |    -0.37 | Goodbye, Oczarka, Scorchyy, snufaffu, Stay_Classy  |
|            1 |     7691 | 2024-09-03 | Orbital vsat online       | W   | 0.008      | -            | -                | -                | -         |     0.05 | Goodbye, Oczarka, Scorchyy, snufaffu, Stay_Classy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($894.65)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.649 | $1,250.00      | $811.28         |
| 2024-11-24 |      0.556 | $150.00        | $83.37          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
