### Roster Details<br />
Team Name: Team Poland (Female team)<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  948.1<br />
<br />
Final Rank Value (948.1) = Starting Rank Value (932.4) + Head To Head Adjustments (15.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.501[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.278[<sup>2</sup>](#table1)

The average of these factors is 0.267<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.4
- 400 + ( ( 0.267 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 932.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     3437 | 2024-11-14 | Prototype Blaze           | W   | 0.486      | 0.557        | 0.058 (0.016)    | 0.229 (0.062)    | 1 (0.486) |     6.34 | Angelka, Hanka, LETi, Liina, vicu   |
|            5 |     3474 | 2024-11-14 | Team USA (Female team)    | W   | 0.484      | 0.557        | 0.014 (0.004)    | 0.022 (0.006)    | 1 (0.484) |     2.33 | Angelka, Hanka, LETi, Liina, vicu   |
|            4 |     3511 | 2024-11-13 | Team Sweden (Female team) | W   | 0.478      | 0.557        | 0.007 (0.002)    | 0.039 (0.010)    | 1 (0.478) |     2.32 | Angelka, Hanka, LETi, Liina, vicu   |
|            3 |     3611 | 2024-11-11 | Ex-Astralis Women         | W   | 0.466      | 0.557        | 0.010 (0.003)    | 0.085 (0.022)    | 1 (0.466) |     3.78 | Angelka, Hanka, LETi, Liina, vicu   |
|            2 |     3623 | 2024-11-11 | Team Canada (Female team) | W   | 0.465      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.465) |     0.82 | Angelka, Hanka, LETi, Liina, vicu   |
|            1 |     6875 | 2024-09-16 | NeedONE Agency            | W   | 0.093      | 0.310        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.14 | AlcesT, Angelka, ASTRA, Hanka, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,096.37)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.486 | $70,000.00     | $34,052.08      |
| 2024-09-21 |      0.127 | $350.00        | $44.28          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
