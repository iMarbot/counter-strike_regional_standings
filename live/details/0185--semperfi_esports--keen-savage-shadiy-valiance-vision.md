### Roster Details<br />
Team Name: SemperFi Esports<br />
Roster: keen, SaVage, shadiy, Valiance, vision<br />
Global Rank: [185](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [19]( ../standings_asia.md)<br />
<br />
Final Rank Value:  722.9<br />
<br />
Final Rank Value (722.9) = Starting Rank Value (548.2) + Head To Head Adjustments (174.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.074<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 548.2
- 400 + ( ( 0.074 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 548.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       61 | 2025-02-25 | KZG                                       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.164 (0.023)    | 0 (0.000) |    11.40 | keen, SaVage, shadiy, Valiance, vision        |
|           23 |       83 | 2025-02-24 | Only One Word                             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.190 (0.027)    | 0 (0.000) |    11.55 | keen, SaVage, shadiy, Valiance, vision        |
|           22 |      448 | 2025-02-14 | Justice For Tomorrow                      | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.425 (0.061)    | 0 (0.000) |    15.46 | keen, SaVage, shadiy, Valiance, vision        |
|           21 |      459 | 2025-02-14 | DXA Esports                               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.02 | keen, SaVage, shadiy, Valiance, vision        |
|           20 |      508 | 2025-02-14 | Vantage Esports                           | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.336 (0.048)    | 0 (0.000) |    15.51 | keen, SaVage, shadiy, Valiance, vision        |
|           19 |      513 | 2025-02-13 | Underground Esports Club                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.240 (0.034)    | 0 (0.000) |    12.90 | keen, SaVage, shadiy, Valiance, vision        |
|           18 |      613 | 2025-02-10 | Rooster                                   | L   | 1.000      | -            | -                | -                | -         |   -13.42 | keen, SaVage, shadiy, Valiance, vision        |
|           17 |      655 | 2025-02-08 | Just Swing (Chinese team)                 | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    17.96 | keen, SaVage, shadiy, Valiance, vision        |
|           16 |      730 | 2025-02-08 | Rooster                                   | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.220 (0.031)    | 0 (0.000) |    18.17 | keen, SaVage, shadiy, Valiance, vision        |
|           15 |      870 | 2025-02-06 | Victores Sumus                            | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.173 (0.025)    | 0 (0.000) |    19.28 | Gratisfaction, keen, shadiy, Valiance, vision |
|           14 |     1054 | 2025-02-01 | Justice For Tomorrow                      | L   | 1.000      | -            | -                | -                | -         |   -12.86 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|           13 |     1055 | 2025-02-01 | BBBCBMBS                                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.13 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|           12 |     1056 | 2025-02-01 | Blazing Beavers                           | W   | 1.000      | -            | -                | -                | -         |     8.57 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|           11 |     1059 | 2025-02-01 | Underground Esports Club                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.240 (0.034)    | -         |    16.18 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|           10 |     1081 | 2025-01-31 | PrevailANZ                                | W   | 1.000      | -            | -                | -                | -         |    10.53 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|            9 |     1084 | 2025-01-31 | LITE Esports                              | W   | 1.000      | -            | -                | -                | -         |     8.19 | keen, KraxyT, shadiy, Valiance, w0mbat        |
|            8 |     1248 | 2024-12-30 | Preasy Esport                             | L   | 0.785      | -            | -                | -                | -         |    -6.52 | keen, SaVage, shadiy, Valiance, vision        |
|            7 |     1250 | 2024-12-30 | Copenhagen Wolves (American organization) | W   | 0.785      | 0.284        | 0.016 (0.004)    | 1.000 (0.223)    | -         |    21.37 | keen, SaVage, shadiy, Valiance, vision        |
|            6 |     1648 | 2024-12-15 | ESC Gaming                                | L   | 0.683      | -            | -                | -                | -         |   -10.92 | keen, SaVage, shadiy, Valiance, vision        |
|            5 |     1900 | 2024-12-11 | Astralis Talent                           | L   | 0.657      | -            | -                | -                | -         |    -4.58 | keen, SaVage, shadiy, Valiance, vision        |
|            4 |     5561 | 2024-10-05 | Only One Word                             | W   | 0.215      | -            | -                | -                | -         |     4.15 | keen, SaVage, shadiy, Valiance, vision        |
|            3 |     5645 | 2024-10-04 | Mindfreak (Australian team)               | W   | 0.208      | -            | -                | -                | -         |     4.63 | keen, SaVage, shadiy, Valiance, vision        |
|            2 |     5649 | 2024-10-04 | Vantage Esports                           | W   | 0.208      | -            | -                | -                | -         |     4.18 | keen, SaVage, shadiy, Valiance, vision        |
|            1 |     5655 | 2024-10-04 | Rebound                                   | W   | 0.207      | -            | -                | -                | -         |     2.88 | keen, SaVage, shadiy, Valiance, vision        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
