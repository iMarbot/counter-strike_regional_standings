### Roster Details<br />
Team Name: XRayG<br />
Roster: a0giri, dshq, mb1w, neosoznala, riva1<br />
Global Rank: [377](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [236]( ../standings_europe.md)<br />
<br />
Final Rank Value:  609.4<br />
<br />
Final Rank Value (609.4) = Starting Rank Value (608.7) + Head To Head Adjustments (0.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.152[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.025[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 608.7
- 400 + ( ( 0.104 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 608.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     5549 | 2024-10-06 | Insilio Female  | W   | 0.216      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.216) |     3.16 | a0giri, dshq, mb1w, neosoznala, riva1   |
|            5 |     5603 | 2024-10-05 | K27 Female      | L   | 0.211      | -            | -                | -                | -         |    -2.47 | a0giri, dshq, mb1w, neosoznala, riva1   |
|            4 |     6692 | 2024-09-19 | KronBars        | W   | 0.105      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.79 | a0giri, dshq, mb1w, neosoznala, riva1   |
|            3 |     7007 | 2024-09-14 | Let Her Cook    | L   | 0.071      | -            | -                | -                | -         |    -1.03 | a0giri, dshq, neosoznala, riva1, Stormy |
|            2 |     7447 | 2024-09-07 | Imperial Female | L   | 0.024      | -            | -                | -                | -         |    -0.07 | a0giri, dshq, neosoznala, riva1, Stormy |
|            1 |     7479 | 2024-09-07 | Also            | W   | 0.023      | 0.294        | 0.002 (0.000)    | 0.195 (0.001)    | 0 (0.000) |     0.39 | a0giri, dshq, neosoznala, riva1, Stormy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($227.06)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.217 | $1,045.95      | $227.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
