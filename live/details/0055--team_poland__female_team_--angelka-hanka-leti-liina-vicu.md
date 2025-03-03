### Roster Details<br />
Team Name: Team Poland (Female team)<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.6<br />
<br />
Final Rank Value (946.6) = Starting Rank Value (931.1) + Head To Head Adjustments (15.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.502[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.274[<sup>2</sup>](#table1)

The average of these factors is 0.266<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.1
- 400 + ( ( 0.266 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 931.1


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
|            6 |     3449 | 2024-11-14 | Prototype Blaze           | W   | 0.478      | 0.557        | 0.058 (0.015)    | 0.228 (0.061)    | 1 (0.478) |     6.24 | Angelka, Hanka, LETi, Liina, vicu   |
|            5 |     3486 | 2024-11-14 | Team USA (Female team)    | W   | 0.476      | 0.557        | 0.015 (0.004)    | 0.022 (0.006)    | 1 (0.476) |     2.30 | Angelka, Hanka, LETi, Liina, vicu   |
|            4 |     3523 | 2024-11-13 | Team Sweden (Female team) | W   | 0.470      | 0.557        | 0.007 (0.002)    | 0.038 (0.010)    | 1 (0.470) |     2.28 | Angelka, Hanka, LETi, Liina, vicu   |
|            3 |     3623 | 2024-11-11 | Ex-Astralis Women         | W   | 0.458      | 0.557        | 0.010 (0.003)    | 0.083 (0.021)    | 1 (0.458) |     3.72 | Angelka, Hanka, LETi, Liina, vicu   |
|            2 |     3635 | 2024-11-11 | Team Canada (Female team) | W   | 0.457      | 0.557        | 0.000 (0.000)    | 0.022 (0.006)    | 1 (0.457) |     0.81 | Angelka, Hanka, LETi, Liina, vicu   |
|            1 |     6887 | 2024-09-16 | NeedONE Agency            | W   | 0.085      | 0.310        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.13 | AlcesT, Angelka, ASTRA, Hanka, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,519.89)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-14 |      0.478 | $70,000.00     | $33,478.47      |
| 2024-09-21 |      0.118 | $350.00        | $41.42          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
