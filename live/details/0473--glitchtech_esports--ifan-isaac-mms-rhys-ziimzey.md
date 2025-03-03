### Roster Details<br />
Team Name: Glitchtech Esports<br />
Roster: ifan, isaac, MMS, Rhys, Ziimzey<br />
Global Rank: [473](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [293]( ../standings_europe.md)<br />
<br />
Final Rank Value:  537.9<br />
<br />
Final Rank Value (537.9) = Starting Rank Value (534.9) + Head To Head Adjustments (3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.152[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 534.9
- 400 + ( ( 0.067 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 534.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |      180 | 2025-02-22 | Viperio Academy         | L   | 1.000      | -            | -                | -                | -         |   -13.96 | ifan, isaac, MMS, Rhys, Ziimzey     |
|            6 |      202 | 2025-02-21 | Submissive and Readable | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     9.42 | ifan, isaac, MMS, Rhys, Ziimzey     |
|            5 |     3835 | 2024-11-07 | ROYALS                  | L   | 0.432      | -            | -                | -                | -         |    -4.21 | ifan, maddeN, Rhys, Yoshwa, Ziimzey |
|            4 |     3842 | 2024-11-07 | ALASKA                  | L   | 0.432      | -            | -                | -                | -         |    -0.75 | ifan, maddeN, Rhys, Yoshwa, Ziimzey |
|            3 |     3880 | 2024-11-06 | Annex Esports           | W   | 0.425      | 0.143        | 0.000 (0.000)    | 0.058 (0.004)    | 0 (0.000) |     7.83 | ifan, maddeN, Rhys, Yoshwa, Ziimzey |
|            2 |     3932 | 2024-11-05 | Dreams To Legends       | W   | 0.419      | 0.143        | 0.000 (0.000)    | 0.081 (0.005)    | 0 (0.000) |     8.07 | ifan, maddeN, Rhys, Yoshwa, Ziimzey |
|            1 |     3983 | 2024-11-04 | Belfast Storm           | L   | 0.412      | -            | -                | -                | -         |    -3.35 | ifan, maddeN, Rhys, Yoshwa, Ziimzey |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
