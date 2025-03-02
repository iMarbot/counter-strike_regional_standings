### Roster Details<br />
Team Name: Insilio Female<br />
Roster: c0ldhurt, g1tsune, icytears, Juntella, metori<br />
Global Rank: [429](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [267]( ../standings_europe.md)<br />
<br />
Final Rank Value:  574.5<br />
<br />
Final Rank Value (574.5) = Starting Rank Value (585.5) + Head To Head Adjustments (-11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.147[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.093<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 585.5
- 400 + ( ( 0.093 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 585.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     4516 | 2024-10-26 | Also                     | L   | 0.359      | -            | -                | -                | -         |    -4.82 | c0ldhurt, g1tsune, icytears, Juntella, metori |
|            7 |     5537 | 2024-10-06 | XRayG                    | L   | 0.224      | -            | -                | -                | -         |    -3.28 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            6 |     5606 | 2024-10-05 | Nomercy (Female team)    | L   | 0.218      | -            | -                | -                | -         |    -2.60 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            5 |     6993 | 2024-09-14 | Take Flyte Female        | L   | 0.079      | -            | -                | -                | -         |    -0.97 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            4 |     7037 | 2024-09-14 | NIP Impact               | L   | 0.078      | -            | -                | -                | -         |    -0.80 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            3 |     7084 | 2024-09-13 | Needachance              | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     0.59 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            2 |     7428 | 2024-09-07 | Let Her Cook             | W   | 0.032      | 0.294        | 0.002 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     0.57 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            1 |     7460 | 2024-09-07 | SoulEaters (Female team) | W   | 0.031      | 0.294        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.26 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($117.81)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.225 | $522.98        | $117.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
