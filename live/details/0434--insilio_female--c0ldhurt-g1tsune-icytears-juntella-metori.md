### Roster Details<br />
Team Name: Insilio Female<br />
Roster: c0ldhurt, g1tsune, icytears, Juntella, metori<br />
Global Rank: [434](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [268]( ../standings_europe.md)<br />
<br />
Final Rank Value:  573.4<br />
<br />
Final Rank Value (573.4) = Starting Rank Value (584.2) + Head To Head Adjustments (-10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.144[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.092<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 584.2
- 400 + ( ( 0.092 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 584.2


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
|            8 |     4528 | 2024-10-26 | Also                     | L   | 0.351      | -            | -                | -                | -         |    -4.68 | c0ldhurt, g1tsune, icytears, Juntella, metori |
|            7 |     5549 | 2024-10-06 | XRayG                    | L   | 0.216      | -            | -                | -                | -         |    -3.16 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            6 |     5618 | 2024-10-05 | Nomercy (Female team)    | L   | 0.210      | -            | -                | -                | -         |    -2.49 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            5 |     7005 | 2024-09-14 | Take Flyte Female        | L   | 0.071      | -            | -                | -                | -         |    -0.86 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            4 |     7049 | 2024-09-14 | NIP Impact               | L   | 0.070      | -            | -                | -                | -         |    -0.71 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            3 |     7096 | 2024-09-13 | Needachance              | W   | 0.064      | 0.143        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     0.53 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            2 |     7440 | 2024-09-07 | Let Her Cook             | W   | 0.024      | 0.294        | 0.002 (0.000)    | 0.030 (0.000)    | 0 (0.000) |     0.43 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |
|            1 |     7472 | 2024-09-07 | SoulEaters (Female team) | W   | 0.023      | 0.294        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.19 | c0ldhurt, g1tsune, icytears, Juntella, m0rena |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($113.53)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.217 | $522.98        | $113.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
