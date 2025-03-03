### Roster Details<br />
Team Name: Dmoai<br />
Roster: adyoka, danikowka, dekayun, kurt, raiNyyy<br />
Global Rank: [498](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [309]( ../standings_europe.md)<br />
<br />
Final Rank Value:  518.6<br />
<br />
Final Rank Value (518.6) = Starting Rank Value (512.2) + Head To Head Adjustments (6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 512.2
- 400 + ( ( 0.056 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 512.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2018 | 2024-12-08 | Asdmix         | L   | 0.637      | -            | -                | -                | -         |    -7.30 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            5 |     2021 | 2024-12-08 | PH SunShine    | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.060 (0.005)    | 1 (0.637) |    11.31 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            4 |     2024 | 2024-12-08 | AimAssassins   | L   | 0.637      | -            | -                | -                | -         |    -1.65 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            3 |     2029 | 2024-12-08 | INVI           | W   | 0.636      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 1 (0.636) |     7.92 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            2 |     2039 | 2024-12-08 | WAKANDA        | W   | 0.636      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.636) |     6.91 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            1 |     2048 | 2024-12-07 | Yamato Esports | L   | 0.635      | -            | -                | -                | -         |   -10.85 | adyoka, danikowka, dekayun, kurt, raiNyyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
