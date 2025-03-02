### Roster Details<br />
Team Name: Fisher College<br />
Roster: AlekS, corn, CrePoW, ReFuZR, tatm<br />
Global Rank: [156](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
<br />
Final Rank Value:  757.2<br />
<br />
Final Rank Value (757.2) = Starting Rank Value (765.9) + Head To Head Adjustments (-8.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.323[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.186[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 765.9
- 400 + ( ( 0.183 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 765.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      171 | 2025-02-21 | Wanted Goons            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |     7.59 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           16 |      173 | 2025-02-21 | Seoul                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     4.18 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           15 |      223 | 2025-02-20 | ShanghaiSharks          | W   | 1.000      | 0.143        | -                | 0.032 (0.005)    | 0 (0.000) |     4.14 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           14 |      731 | 2025-02-07 | Getting Info            | L   | 1.000      | -            | -                | -                | -         |   -24.81 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           13 |     1820 | 2024-12-12 | Homyno                  | L   | 0.675      | -            | -                | -                | -         |   -12.65 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           12 |     1853 | 2024-12-11 | Small rejuice           | W   | 0.669      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     4.05 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           11 |     1903 | 2024-12-10 | Habibi                  | W   | 0.662      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     4.04 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           10 |     2048 | 2024-12-07 | Undone                  | L   | 0.642      | -            | -                | -                | -         |   -10.61 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            9 |     2073 | 2024-12-07 | Take Flyte              | W   | 0.640      | 0.384        | -                | 0.142 (0.035)    | 1 (0.640) |     3.31 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            8 |     2112 | 2024-12-06 | Nouns Esports           | L   | 0.635      | -            | -                | -                | -         |    -7.91 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            7 |     4758 | 2024-10-20 | Timbermen               | W   | 0.321      | 0.333        | 0.002 (0.000)    | 0.030 (0.003)    | 1 (0.321) |     3.68 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            6 |     4760 | 2024-10-20 | Slugy's Shekel Squad    | W   | 0.320      | 0.333        | 0.001 (0.000)    | 0.015 (0.002)    | 1 (0.320) |     2.13 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            5 |     4826 | 2024-10-19 | Penance (American Team) | W   | 0.315      | -            | -                | -                | 1 (0.315) |     1.05 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            4 |     5120 | 2024-10-13 | FLUFFY AIMERS           | W   | 0.274      | 0.262        | 0.005 (0.000)    | 0.228 (0.016)    | 0 (0.000) |     4.69 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            3 |     5170 | 2024-10-12 | InControl               | W   | 0.268      | 0.262        | 0.001 (0.000)    | 0.086 (0.006)    | -         |     2.67 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            2 |     5175 | 2024-10-12 | Final Form              | W   | 0.267      | 0.262        | 0.001 (0.000)    | 0.076 (0.005)    | -         |     2.50 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            1 |     5182 | 2024-10-12 | Supernova Comets        | W   | 0.267      | 0.262        | 0.011 (0.001)    | 0.220 (0.015)    | -         |     3.24 | AlekS, corn, CrePoW, ReFuZR, tatm |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,667.97)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.696 | $1,000.00      | $695.69         |
| 2024-10-20 |      0.321 | $5,500.00      | $1,766.49       |
| 2024-10-13 |      0.274 | $750.00        | $205.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
