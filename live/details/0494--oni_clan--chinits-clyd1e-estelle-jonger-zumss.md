### Roster Details<br />
Team Name: Oni CLAN<br />
Roster: Chinits, clyd1e, Estelle, Jonger, Zumss<br />
Global Rank: [494](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [80]( ../standings_asia.md)<br />
<br />
Final Rank Value:  522.3<br />
<br />
Final Rank Value (522.3) = Starting Rank Value (523.7) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.184[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 523.7
- 400 + ( ( 0.062 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 523.7


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
|            6 |     2916 | 2024-11-22 | Kadiliman Esports         | W   | 0.543      | 0.143        | 0.000 (0.000)    | 0.029 (0.002)    | 1 (0.543) |     5.79 | Chinits, clyd1e, Estelle, Jonger, Zumss |
|            5 |     3281 | 2024-11-17 | DEWA United               | L   | 0.504      | -            | -                | -                | -         |    -7.02 | Chinits, clyd1e, JMX, Jonger, Zumss     |
|            4 |     6843 | 2024-09-17 | Just Swing (Chinese team) | L   | 0.098      | -            | -                | -                | -         |    -0.84 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |
|            3 |     6943 | 2024-09-15 | SUBUTAI                   | W   | 0.085      | 0.250        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.90 | clyd1e, Estelle, Jaytzy, Whis, Zumss    |
|            2 |     7310 | 2024-09-09 | Alter Ego                 | L   | 0.045      | -            | -                | -                | -         |    -0.62 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |
|            1 |     7449 | 2024-09-07 | SEVER14 TEAM              | W   | 0.032      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.33 | clyd1e, Jaytzy, Jonger, Whis, Zumss     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12.49)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.125 | $100.00        | $12.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
