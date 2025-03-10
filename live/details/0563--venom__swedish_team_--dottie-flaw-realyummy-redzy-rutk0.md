### Roster Details<br />
Team Name: Venom (Swedish team)<br />
Roster: dottie, flaw, RealYummy, redzy, Rutk0<br />
Global Rank: [563](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [346]( ../standings_europe.md)<br />
<br />
Final Rank Value:  469.6<br />
<br />
Final Rank Value (469.6) = Starting Rank Value (502.7) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.7
- 400 + ( ( 0.051 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 502.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1383 | 2024-12-23 | Soul's Heart Esport   | L   | 0.739      | -            | -                | -                | -         |   -14.17 | dottie, flaw, RealYummy, redzy, Rutk0 |
|           10 |     1416 | 2024-12-22 | BMTH (Ukrainian team) | L   | 0.730      | -            | -                | -                | -         |   -10.78 | dottie, flaw, RealYummy, redzy, Rutk0 |
|            9 |     1572 | 2024-12-18 | SkyFury               | L   | 0.703      | -            | -                | -                | -         |    -6.63 | dottie, flaw, RealYummy, redzy, Rutk0 |
|            8 |     1607 | 2024-12-16 | XI Esport             | L   | 0.690      | -            | -                | -                | -         |    -5.87 | dottie, flaw, RealYummy, redzy, Rutk0 |
|            7 |     1656 | 2024-12-15 | SkyFury               | W   | 0.683      | 0.303        | 0.004 (0.001)    | 0.338 (0.070)    | 0 (0.000) |    15.21 | dottie, flaw, RealYummy, redzy, Rutk0 |
|            6 |     3499 | 2024-11-13 | NIP Svea              | L   | 0.472      | -            | -                | -                | -         |    -9.31 | dottie, flaw, Mazzo, MistFire, redzy  |
|            5 |     4254 | 2024-10-31 | Privateshow           | L   | 0.385      | -            | -                | -                | -         |    -5.76 | dottie, flaw, Mazzo, MistFire, redzy  |
|            4 |     4629 | 2024-10-24 | KILLBOX               | W   | 0.338      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     4.72 | dottie, flaw, Mazzo, MistFire, redzy  |
|            3 |     4899 | 2024-10-18 | Regeltre              | W   | 0.298      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     3.36 | dottie, flaw, Mazzo, MistFire, redzy  |
|            2 |     5431 | 2024-10-08 | Kario Mart            | L   | 0.231      | -            | -                | -                | -         |    -2.46 | dottie, flaw, Mazzo, MistFire, redzy  |
|            1 |     7033 | 2024-09-14 | Northern Lights       | L   | 0.070      | -            | -                | -                | -         |    -1.41 | dottie, flaw, Mazzo, MistFire, redzy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
