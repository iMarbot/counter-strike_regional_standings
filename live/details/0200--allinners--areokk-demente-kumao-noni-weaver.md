### Roster Details<br />
Team Name: ALLINNERS<br />
Roster: areokk, demente, kumao, noni, weaveR<br />
Global Rank: [200](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [146]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.1<br />
<br />
Final Rank Value (712.1) = Starting Rank Value (703.1) + Head To Head Adjustments (9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.1
- 400 + ( ( 0.152 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 703.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1262 | 2024-12-29 | Temp                            | L   | 0.784      | -            | -                | -                | -         |   -15.03 | areokk, demente, kumao, noni, weaveR  |
|           14 |     1728 | 2024-12-13 | Mix52                           | L   | 0.684      | -            | -                | -                | -         |   -10.11 | areokk, demente, kumao, noni, weaveR  |
|           13 |     1807 | 2024-12-13 | AimAssassins                    | L   | 0.678      | -            | -                | -                | -         |    -5.01 | areokk, demente, kumao, noni, weaveR  |
|           12 |     1814 | 2024-12-12 | Blaze (Uzbek team)              | W   | 0.677      | 0.333        | 0.005 (0.001)    | 0.070 (0.016)    | 1 (0.677) |    10.47 | areokk, demente, kumao, noni, weaveR  |
|           11 |     2405 | 2024-12-01 | Team Novaq                      | W   | 0.600      | 0.143        | 0.030 (0.003)    | 0.396 (0.034)    | 0 (0.000) |    17.10 | areokk, demente, kumao, noni, weaveR  |
|           10 |     2427 | 2024-12-01 | AK BARS                         | W   | 0.599      | 0.143        | 0.008 (0.001)    | 0.212 (0.018)    | 0 (0.000) |    12.57 | areokk, demente, kumao, noni, weaveR  |
|            9 |     2482 | 2024-11-30 | Cerberus eSports (Russian team) | L   | 0.594      | -            | -                | -                | -         |   -12.64 | Areokk, demente, kumao, Noni, weaveR  |
|            8 |     2623 | 2024-11-28 | Metizport X                     | L   | 0.580      | -            | -                | -                | -         |   -10.61 | Areokk, demente, kumao, Noni, weaveR  |
|            7 |     3262 | 2024-11-17 | DEPO                            | L   | 0.505      | -            | -                | -                | -         |    -7.16 | areokk, noni, plushax, tasman, weaveR |
|            6 |     3283 | 2024-11-17 | MYSKILL                         | L   | 0.504      | -            | -                | -                | -         |    -9.27 | areokk, noni, plushax, tasman, weaveR |
|            5 |     3338 | 2024-11-16 | Yamato Esports                  | W   | 0.498      | 0.143        | 0.000 (0.000)    | 0.020 (0.001)    | 0 (0.000) |     3.45 | areokk, noni, plushax, tasman, weaveR |
|            4 |     3717 | 2024-11-09 | AK BARS                         | W   | 0.453      | 0.143        | 0.008 (0.001)    | 0.212 (0.014)    | 0 (0.000) |     9.24 | areokk, demente, noni, rinn, weaveR   |
|            3 |     3795 | 2024-11-08 | AK BARS                         | W   | 0.446      | 0.143        | 0.008 (0.001)    | 0.212 (0.014)    | 0 (0.000) |     9.33 | areokk, demente, noni, rinn, weaveR   |
|            2 |     3886 | 2024-11-06 | DEPO                            | W   | 0.433      | 0.143        | 0.006 (0.000)    | 0.297 (0.018)    | 0 (0.000) |     7.94 | areokk, demente, noni, rinn, weaveR   |
|            1 |     4063 | 2024-11-03 | RAGE (Kazakh team)              | W   | 0.412      | 0.143        | 0.005 (0.000)    | 0.182 (0.011)    | 0 (0.000) |     8.74 | areokk, demente, noni, rinn, weaveR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($838.66)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-17 |      0.506 | $100.31        | $50.71          |
| 2024-11-09 |      0.453 | $1,740.06      | $787.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
