### Roster Details<br />
Team Name: OutGoing eSports<br />
Roster: Fuzenko, kilmy, Sanzh1k33, senital, slomotion<br />
Global Rank: [331](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [216]( ../standings_europe.md)<br />
<br />
Final Rank Value:  633.1<br />
<br />
Final Rank Value (633.1) = Starting Rank Value (640.7) + Head To Head Adjustments (-7.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.7
- 400 + ( ( 0.120 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 640.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1752 | 2024-12-13 | Undone          | L   | 0.682      | -            | -                | -                | -         |    -6.67 | Fuzenko, kilmy, Sanzh1k33, senital, slomotion |
|            4 |     2193 | 2024-12-04 | Bad Boys        | L   | 0.622      | -            | -                | -                | -         |    -9.41 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            3 |     2244 | 2024-12-03 | Final Form      | W   | 0.616      | 0.372        | 0.000 (0.000)    | 0.057 (0.013)    | 0 (0.000) |     4.13 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            2 |     2381 | 2024-12-01 | Undone          | L   | 0.602      | -            | -                | -                | -         |    -6.24 | Fuzenko, kilmy, malfik, senital, slomotion    |
|            1 |     2571 | 2024-11-29 | Alter Iron Club | W   | 0.588      | 0.372        | 0.009 (0.002)    | 0.356 (0.078)    | 0 (0.000) |    10.59 | Fuzenko, kilmy, malfik, senital, slomotion    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($486.77)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.649 | $750.00        | $486.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
