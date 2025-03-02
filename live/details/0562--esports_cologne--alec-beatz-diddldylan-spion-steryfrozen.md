### Roster Details<br />
Team Name: ESports Cologne<br />
Roster: Alec, Beatz, Diddldylan, Spion, SteryFrozen<br />
Global Rank: [562](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [346]( ../standings_europe.md)<br />
<br />
Final Rank Value:  470.8<br />
<br />
Final Rank Value (470.8) = Starting Rank Value (472.1) + Head To Head Adjustments (-1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.144[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.036<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 472.1
- 400 + ( ( 0.036 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 472.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     4295 | 2024-10-30 | Regnum4Games      | L   | 0.387      | -            | -                | -                | -         |    -3.42 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            7 |     4408 | 2024-10-28 | Sissi State Punks | W   | 0.374      | 0.143        | 0.000 (0.000)    | 0.068 (0.004)    | 0 (0.000) |     8.00 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            6 |     4740 | 2024-10-21 | BIG               | L   | 0.326      | -            | -                | -                | -         |    -0.03 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            5 |     4984 | 2024-10-16 | MYinsanity        | L   | 0.293      | -            | -                | -                | -         |    -2.39 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            4 |     5336 | 2024-10-09 | Permitta Esports  | L   | 0.246      | -            | -                | -                | -         |    -1.05 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            3 |     5907 | 2024-09-30 | XPERION NXT       | L   | 0.186      | -            | -                | -                | -         |    -1.60 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            2 |     6751 | 2024-09-18 | ALTERNATE aTTaX   | L   | 0.106      | -            | -                | -                | -         |    -0.23 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |
|            1 |     7168 | 2024-09-11 | Wave Esports      | L   | 0.060      | -            | -                | -                | -         |    -0.56 | Alec, Beatz, Diddldylan, Spion, SteryFrozen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
