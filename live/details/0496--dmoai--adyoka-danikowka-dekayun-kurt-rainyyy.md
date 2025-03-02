### Roster Details<br />
Team Name: Dmoai<br />
Roster: adyoka, danikowka, dekayun, kurt, raiNyyy<br />
Global Rank: [496](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [308]( ../standings_europe.md)<br />
<br />
Final Rank Value:  519.5<br />
<br />
Final Rank Value (519.5) = Starting Rank Value (513.1) + Head To Head Adjustments (6.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.226[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.1
- 400 + ( ( 0.057 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 513.1


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
|            6 |     2006 | 2024-12-08 | Asdmix         | L   | 0.646      | -            | -                | -                | -         |    -7.39 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            5 |     2009 | 2024-12-08 | PH SunShine    | W   | 0.645      | 0.143        | 0.000 (0.000)    | 0.060 (0.006)    | 1 (0.645) |    11.45 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            4 |     2012 | 2024-12-08 | AimAssassins   | L   | 0.645      | -            | -                | -                | -         |    -1.66 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            3 |     2017 | 2024-12-08 | INVI           | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.030 (0.003)    | 1 (0.644) |     8.00 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            2 |     2027 | 2024-12-08 | WAKANDA        | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.644) |     6.97 | adyoka, danikowka, dekayun, kurt, raiNyyy |
|            1 |     2036 | 2024-12-07 | Yamato Esports | L   | 0.643      | -            | -                | -                | -         |   -10.99 | adyoka, danikowka, dekayun, kurt, raiNyyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
