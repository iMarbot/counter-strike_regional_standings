### Roster Details<br />
Team Name: Oni CLAN<br />
Roster: Chinits, clyd1e, Estelle, Jonger, Zumss<br />
Global Rank: [493](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [80]( ../standings_asia.md)<br />
<br />
Final Rank Value:  521.8<br />
<br />
Final Rank Value (521.8) = Starting Rank Value (523.2) + Head To Head Adjustments (-1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.183[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 523.2
- 400 + ( ( 0.062 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 523.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2928 | 2024-11-22 | Kadiliman Esports         | W   | 0.535      | 0.143        | 0.000 (0.000)    | 0.028 (0.002)    | 1 (0.535) |     5.71 | Chinits, clyd1e, Estelle, Jonger, Zumss |
|            5 |     3293 | 2024-11-17 | DEWA United               | L   | 0.496      | -            | -                | -                | -         |    -6.93 | Chinits, clyd1e, JMX, Jonger, Zumss     |
|            4 |     6855 | 2024-09-17 | Just Swing (Chinese team) | L   | 0.090      | -            | -                | -                | -         |    -0.77 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |
|            3 |     6955 | 2024-09-15 | SUBUTAI                   | W   | 0.077      | 0.250        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.81 | clyd1e, Estelle, Jaytzy, Whis, Zumss    |
|            2 |     7322 | 2024-09-09 | Alter Ego                 | L   | 0.037      | -            | -                | -                | -         |    -0.51 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |
|            1 |     7461 | 2024-09-07 | SEVER14 TEAM              | W   | 0.023      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.25 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11.67)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.117 | $100.00        | $11.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
