### Roster Details<br />
Team Name: NIP Impact<br />
Roster: aiM, Nayomy, Qiyarah, ramziiN, vilga<br />
Global Rank: [204](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [149]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.5<br />
<br />
Final Rank Value (709.5) = Starting Rank Value (714.9) + Head To Head Adjustments (-5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.340[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.063[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 714.9
- 400 + ( ( 0.158 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 714.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2890 | 2024-11-23 | BIG EQUIPA        | L   | 0.545      | -            | -                | -                | -         |    -7.12 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            9 |     2948 | 2024-11-22 | K27 Female        | W   | 0.540      | 0.524        | 0.008 (0.002)    | 0.058 (0.016)    | 1 (0.540) |     8.57 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            8 |     2986 | 2024-11-22 | BIG EQUIPA        | L   | 0.538      | -            | -                | -                | -         |    -7.04 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            7 |     4881 | 2024-10-18 | Let Her Cook      | L   | 0.306      | -            | -                | -                | -         |    -5.89 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            6 |     5716 | 2024-10-03 | Ex-Astralis Women | W   | 0.206      | 0.328        | 0.010 (0.001)    | 0.085 (0.006)    | 0 (0.000) |     3.61 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            5 |     6288 | 2024-09-25 | Take Flyte Female | W   | 0.153      | 0.328        | 0.006 (0.000)    | 0.272 (0.014)    | 0 (0.000) |     2.11 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            4 |     7009 | 2024-09-14 | Eco Warriors      | L   | 0.079      | -            | -                | -                | -         |    -0.97 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            3 |     7037 | 2024-09-14 | Insilio Female    | W   | 0.078      | 0.294        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     0.80 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            2 |     7429 | 2024-09-07 | Elite Klan Violet | W   | 0.032      | 0.294        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.15 | aiM, Nayomy, Qiyarah, ramziiN, vilga |
|            1 |     7583 | 2024-09-05 | Eco Warriors      | W   | 0.020      | 0.328        | 0.022 (0.000)    | 0.244 (0.002)    | 0 (0.000) |     0.38 | aiM, Nayomy, Qiyarah, ramziiN, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,868.47)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.553 | $7,000.00      | $3,868.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
