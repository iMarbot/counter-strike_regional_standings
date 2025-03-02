### Roster Details<br />
Team Name: Undone<br />
Roster: chop, cxzi, motm, Skadoodle, steel<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [24]( ../standings_americas.md)<br />
<br />
Final Rank Value:  791.2<br />
<br />
Final Rank Value (791.2) = Starting Rank Value (777.4) + Head To Head Adjustments (13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.4
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 777.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1654 | 2024-12-14 | Bad News Capybaras      | W   | 0.689      | 0.143        | 0.001 (0.000)    | 0.115 (0.011)    | 0 (0.000) |     6.94 | chop, cxzi, motm, Skadoodle, steel |
|           19 |     1737 | 2024-12-13 | Alter Iron Club         | W   | 0.683      | 0.143        | 0.009 (0.001)    | 0.356 (0.035)    | 0 (0.000) |     9.20 | chop, cxzi, motm, Skadoodle, steel |
|           18 |     1743 | 2024-12-13 | Make Your Mind          | L   | 0.682      | -            | -                | -                | -         |   -11.38 | chop, cxzi, motm, Skadoodle, steel |
|           17 |     1747 | 2024-12-13 | ShanghaiSharks          | W   | 0.682      | 0.143        | 0.000 (0.000)    | 0.032 (0.003)    | 0 (0.000) |     2.34 | chop, cxzi, motm, Skadoodle, steel |
|           16 |     1752 | 2024-12-13 | OutGoing eSports        | W   | 0.682      | 0.143        | 0.001 (0.000)    | 0.056 (0.005)    | 0 (0.000) |     6.67 | chop, cxzi, motm, Skadoodle, steel |
|           15 |     1860 | 2024-12-11 | Bad News Capybaras      | W   | 0.669      | 0.143        | 0.001 (0.000)    | 0.115 (0.011)    | 0 (0.000) |     6.73 | chop, cxzi, motm, Skadoodle, steel |
|           14 |     1905 | 2024-12-10 | InControl               | W   | 0.662      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     2.13 | chop, cxzi, motm, Skadoodle, steel |
|           13 |     1993 | 2024-12-08 | Nouns Esports           | L   | 0.647      | -            | -                | -                | -         |    -7.54 | chop, cxzi, motm, steel, taggy     |
|           12 |     2038 | 2024-12-07 | MIGHT                   | W   | 0.643      | 0.384        | 0.002 (0.000)    | 0.444 (0.110)    | 1 (0.643) |     8.68 | chop, cxzi, motm, steel, taggy     |
|           11 |     2048 | 2024-12-07 | Fisher College          | W   | 0.642      | 0.384        | 0.008 (0.002)    | 0.327 (0.081)    | 1 (0.642) |    10.61 | chop, cxzi, motm, steel, taggy     |
|           10 |     2056 | 2024-12-07 | NRG                     | L   | 0.641      | -            | -                | -                | -         |    -4.29 | chop, cxzi, motm, steel, taggy     |
|            9 |     2106 | 2024-12-06 | Anti-Eco Club           | W   | 0.636      | -            | -                | -                | 1 (0.636) |     2.35 | chop, cxzi, motm, steel, taggy     |
|            8 |     2152 | 2024-12-05 | Alter Iron Club         | L   | 0.629      | -            | -                | -                | -         |   -11.35 | chop, cxzi, motm, Skadoodle, steel |
|            7 |     2309 | 2024-12-02 | Make Your Mind          | L   | 0.609      | -            | -                | -                | -         |   -11.09 | chop, cxzi, motm, Skadoodle, steel |
|            6 |     2381 | 2024-12-01 | OutGoing eSports        | W   | 0.602      | 0.372        | 0.001 (0.000)    | 0.056 (0.013)    | 0 (0.000) |     6.24 | chop, cxzi, motm, Skadoodle, steel |
|            5 |     2570 | 2024-11-29 | Vibe (American team)    | W   | 0.589      | 0.372        | 0.000 (0.000)    | 0.071 (0.016)    | -         |     5.05 | chop, cxzi, motm, Skadoodle, steel |
|            4 |     2828 | 2024-11-23 | BOSS                    | L   | 0.547      | -            | -                | -                | -         |    -5.50 | chop, cxzi, motm, Skadoodle, steel |
|            3 |     5941 | 2024-09-29 | Party Astronauts        | L   | 0.182      | -            | -                | -                | -         |    -2.90 | BeaKie, chop, cxzi, motm, stamina  |
|            2 |     6733 | 2024-09-18 | Mythic                  | W   | 0.108      | 0.371        | -                | 0.023 (0.001)    | -         |     0.59 | BeaKie, chop, cxzi, motm, stamina  |
|            1 |     6864 | 2024-09-16 | Penance (American Team) | W   | 0.094      | -            | -                | -                | -         |     0.32 | BeaKie, chop, cxzi, motm, stamina  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($811.28)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.649 | $1,250.00      | $811.28         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
