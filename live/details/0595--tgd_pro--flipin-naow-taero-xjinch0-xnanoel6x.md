### Roster Details<br />
Team Name: TGD Pro<br />
Roster: FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x<br />
Global Rank: [595](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [361]( ../standings_europe.md)<br />
<br />
Final Rank Value:  406.3<br />
<br />
Final Rank Value (406.3) = Starting Rank Value (400.1) + Head To Head Adjustments (6.1)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.1


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
|           10 |     3441 | 2024-11-14 | Ex-ESC Gaming           | L   | 0.486      | -            | -                | -                | -         |    -3.12 | FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x  |
|            9 |     3486 | 2024-11-13 | Onyx Ravens             | L   | 0.480      | -            | -                | -                | -         |    -2.64 | FlipiN, NaOw, taero, xJiNCh0, xNanoEL6x  |
|            8 |     4433 | 2024-10-28 | GOOFYBOYZ               | L   | 0.373      | -            | -                | -                | -         |    -1.53 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            7 |     4613 | 2024-10-24 | RogerBall               | W   | 0.347      | 0.143        | 0.000 (0.000)    | 0.030 (0.002)    | 0 (0.000) |     6.80 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            6 |     4647 | 2024-10-23 | Talaintanse             | W   | 0.340      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     6.59 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            5 |     4693 | 2024-10-22 | The Agency Clan         | L   | 0.333      | -            | -                | -                | -         |    -0.83 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            4 |     4841 | 2024-10-19 | The Agency Clan         | W   | 0.313      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.96 | NaOw, taero, xJiNCh0, xNanoEL6x, YuRk0   |
|            3 |     6110 | 2024-09-27 | Mixzada                 | L   | 0.167      | -            | -                | -                | -         |    -1.29 | Fointte, NaOw, taero, xJiNCh0, xNanoEL6x |
|            2 |     6741 | 2024-09-18 | Turritos                | L   | 0.107      | -            | -                | -                | -         |    -1.67 | FlipiN, Fointte, NaOw, taero, xJiNCh0    |
|            1 |     6871 | 2024-09-16 | SQUAD (Portuguese team) | L   | 0.093      | -            | -                | -                | -         |    -1.13 | FlipiN, Fointte, NaOw, taero, xJiNCh0    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
