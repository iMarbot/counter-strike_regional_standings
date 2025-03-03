### Roster Details<br />
Team Name: Team USA (Female team)<br />
Roster: EMUHLEET, emy, madss, olya, uhKelsie<br />
Global Rank: [343](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [72]( ../standings_americas.md)<br />
<br />
Final Rank Value:  628.2<br />
<br />
Final Rank Value (628.2) = Starting Rank Value (630.6) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.108[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.6
- 400 + ( ( 0.115 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 630.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3471 | 2024-11-14 | Team Portugal (Female team)    | L   | 0.477      | -            | -                | -                | -         |    -3.63 | EMUHLEET, emy, madss, olya, uhKelsie |
|            4 |     3486 | 2024-11-14 | Team Poland (Female team)      | L   | 0.476      | -            | -                | -                | -         |    -2.30 | EMUHLEET, emy, madss, olya, uhKelsie |
|            3 |     3563 | 2024-11-12 | Team Netherlands (Female team) | W   | 0.464      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.464) |     3.56 | EMUHLEET, emy, madss, olya, uhKelsie |
|            2 |     3628 | 2024-11-11 | Team Portugal (Female team)    | L   | 0.458      | -            | -                | -                | -         |    -3.54 | EMUHLEET, emy, madss, olya, uhKelsie |
|            1 |     3645 | 2024-11-11 | Team Netherlands (Female team) | W   | 0.456      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.456) |     3.46 | EMUHLEET, emy, madss, olya, uhKelsie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,782.64)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.478 | $10,000.00     | $4,782.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
