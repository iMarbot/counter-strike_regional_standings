### Roster Details<br />
Team Name: TGD Pro<br />
Roster: FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x<br />
Global Rank: [595](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [360]( ../standings_europe.md)<br />
<br />
Final Rank Value:  406.2<br />
<br />
Final Rank Value (406.2) = Starting Rank Value (400.1) + Head To Head Adjustments (6.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.1
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3453 | 2024-11-14 | Ex-ESC Gaming           | L   | 0.478      | -            | -                | -                | -         |    -3.06 | FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x  |
|            9 |     3498 | 2024-11-13 | Onyx Ravens             | L   | 0.472      | -            | -                | -                | -         |    -2.59 | FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x  |
|            8 |     4445 | 2024-10-28 | GOOFYBOYZ               | L   | 0.365      | -            | -                | -                | -         |    -1.50 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            7 |     4625 | 2024-10-24 | RogerBall               | W   | 0.339      | 0.143        | 0.000 (0.000)    | 0.030 (0.001)    | 0 (0.000) |     6.64 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            6 |     4659 | 2024-10-23 | Talaintanse             | W   | 0.332      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     6.43 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            5 |     4705 | 2024-10-22 | The Agency Clan         | L   | 0.325      | -            | -                | -                | -         |    -0.81 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            4 |     4853 | 2024-10-19 | The Agency Clan         | W   | 0.304      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.82 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            3 |     6122 | 2024-09-27 | Mixzada                 | L   | 0.158      | -            | -                | -                | -         |    -1.22 | Fointte, NaOw, taero, xJiNCh0, xNanoEL6x |
|            2 |     6753 | 2024-09-18 | Turritos                | L   | 0.098      | -            | -                | -                | -         |    -1.54 | FlipiN, Fointte, NaOw, taero, xJiNCh0    |
|            1 |     6883 | 2024-09-16 | SQUAD (Portuguese team) | L   | 0.085      | -            | -                | -                | -         |    -1.04 | FlipiN, Fointte, NaOw, taero, xJiNCh0    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
