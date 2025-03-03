### Roster Details<br />
Team Name: Fisher College<br />
Roster: AlekS, corn, CrePoW, ReFuZR, tatm<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
<br />
Final Rank Value:  774.0<br />
<br />
Final Rank Value (774.0) = Starting Rank Value (765.4) + Head To Head Adjustments (8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.183[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 765.4
- 400 + ( ( 0.183 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 765.4


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
|           17 |      183 | 2025-02-21 | Wanted Goons            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |     8.94 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           16 |      185 | 2025-02-21 | Seoul                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.88 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           15 |      235 | 2025-02-20 | ShanghaiSharks          | W   | 1.000      | 0.143        | -                | 0.032 (0.005)    | 0 (0.000) |     3.83 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           14 |      743 | 2025-02-07 | Getting Info            | L   | 1.000      | -            | -                | -                | -         |    -9.93 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           13 |     1832 | 2024-12-12 | Homyno                  | L   | 0.667      | -            | -                | -                | -         |   -12.51 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           12 |     1865 | 2024-12-11 | Small rejuice           | W   | 0.661      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     3.98 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           11 |     1915 | 2024-12-10 | Habibi                  | W   | 0.654      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     3.98 | AlekS, corn, CrePoW, ReFuZR, tatm |
|           10 |     2060 | 2024-12-07 | Undone                  | L   | 0.634      | -            | -                | -                | -         |   -10.41 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            9 |     2085 | 2024-12-07 | Take Flyte              | W   | 0.632      | 0.384        | -                | 0.189 (0.046)    | 1 (0.632) |     4.23 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            8 |     2124 | 2024-12-06 | Nouns Esports           | L   | 0.627      | -            | -                | -                | -         |    -7.52 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            7 |     4770 | 2024-10-20 | Timbermen               | W   | 0.313      | 0.333        | 0.002 (0.000)    | 0.029 (0.003)    | 1 (0.313) |     3.58 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            6 |     4772 | 2024-10-20 | Slugy's Shekel Squad    | W   | 0.312      | 0.333        | 0.001 (0.000)    | 0.014 (0.001)    | 1 (0.312) |     2.08 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            5 |     4838 | 2024-10-19 | Penance (American Team) | W   | 0.307      | -            | -                | -                | 1 (0.307) |     1.02 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            4 |     5132 | 2024-10-13 | FLUFFY AIMERS           | W   | 0.266      | 0.262        | 0.005 (0.000)    | 0.213 (0.015)    | 0 (0.000) |     4.63 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            3 |     5182 | 2024-10-12 | InControl               | W   | 0.260      | 0.262        | 0.001 (0.000)    | 0.084 (0.006)    | -         |     2.59 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            2 |     5187 | 2024-10-12 | Final Form              | W   | 0.259      | 0.262        | 0.001 (0.000)    | 0.073 (0.005)    | -         |     2.42 | AlekS, corn, CrePoW, ReFuZR, tatm |
|            1 |     5194 | 2024-10-12 | Supernova Comets        | W   | 0.258      | 0.262        | 0.011 (0.001)    | 0.263 (0.018)    | -         |     3.77 | AlekS, corn, CrePoW, ReFuZR, tatm |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,608.56)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.688 | $1,000.00      | $687.50         |
| 2024-10-20 |      0.313 | $5,500.00      | $1,721.42       |
| 2024-10-13 |      0.266 | $750.00        | $199.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
