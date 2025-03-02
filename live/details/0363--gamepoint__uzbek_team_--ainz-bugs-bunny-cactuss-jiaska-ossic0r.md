### Roster Details<br />
Team Name: GamePoint (Uzbek team)<br />
Roster: Ainz, bugs-bunny, cactuss, JIaska, ossic0r<br />
Global Rank: [363](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [58]( ../standings_asia.md)<br />
<br />
Final Rank Value:  615.8<br />
<br />
Final Rank Value (615.8) = Starting Rank Value (629.7) + Head To Head Adjustments (-13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.198[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.098[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.7
- 400 + ( ( 0.115 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 629.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1790 | 2024-12-13 | Mix52              | L   | 0.679      | -            | -                | -                | -         |    -7.04 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            5 |     1797 | 2024-12-13 | AK BARS            | L   | 0.679      | -            | -                | -                | -         |    -5.00 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            4 |     2020 | 2024-12-08 | OCTAZONE           | W   | 0.644      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.644) |     7.19 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            3 |     2033 | 2024-12-07 | Mix52              | L   | 0.644      | -            | -                | -                | -         |    -6.91 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            2 |     5861 | 2024-10-01 | 5x5                | W   | 0.192      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.192) |     1.32 | Ainz, bugs-bunny, Ingenium, JIoelL, ossic0r |
|            1 |     5875 | 2024-10-01 | Blaze (Uzbek team) | L   | 0.191      | -            | -                | -                | -         |    -3.42 | Ainz, bugs-bunny, Ingenium, JIoelL, ossic0r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30.07)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-01 |      0.192 | $157.02        | $30.07          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
