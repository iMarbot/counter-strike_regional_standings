### Roster Details<br />
Team Name: GamePoint (Uzbek team)<br />
Roster: Ainz, bugs-bunny, cactuss, JIaska, ossic0r<br />
Global Rank: [366](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [58]( ../standings_asia.md)<br />
<br />
Final Rank Value:  615.4<br />
<br />
Final Rank Value (615.4) = Starting Rank Value (629.0) + Head To Head Adjustments (-13.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.198[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.096[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.0
- 400 + ( ( 0.114 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 629.0


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
|            6 |     1802 | 2024-12-13 | Mix52              | L   | 0.671      | -            | -                | -                | -         |    -6.96 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            5 |     1809 | 2024-12-13 | AK BARS            | L   | 0.670      | -            | -                | -                | -         |    -4.96 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            4 |     2032 | 2024-12-08 | OCTAZONE           | W   | 0.636      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.636) |     7.13 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            3 |     2045 | 2024-12-07 | Mix52              | L   | 0.635      | -            | -                | -                | -         |    -6.83 | Ainz, bugs-bunny, cactuss, JIaska, ossic0r  |
|            2 |     5873 | 2024-10-01 | 5x5                | W   | 0.183      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.183) |     1.27 | Ainz, bugs-bunny, Ingenium, JIoelL, ossic0r |
|            1 |     5887 | 2024-10-01 | Blaze (Uzbek team) | L   | 0.183      | -            | -                | -                | -         |    -3.28 | Ainz, bugs-bunny, Ingenium, JIoelL, ossic0r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28.79)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-01 |      0.183 | $157.02        | $28.79          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
