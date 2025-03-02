### Roster Details<br />
Team Name: NOTTODAY<br />
Roster: dJakONdA, eksiver, H0k17, natalia_audi, WESTGOTH<br />
Global Rank: [356](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [231]( ../standings_europe.md)<br />
<br />
Final Rank Value:  621.5<br />
<br />
Final Rank Value (621.5) = Starting Rank Value (604.0) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.203[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.102<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 604.0
- 400 + ( ( 0.102 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 604.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     5198 | 2024-10-12 | GameAgents                     | W   | 0.266      | 0.215        | 0.000 (0.000)    | 0.097 (0.006)    | 0 (0.000) |     4.27 | dJakONdA, eksiver, H0k17, natalia_audi, WESTGOTH    |
|            6 |     5199 | 2024-10-12 | LEON Esports                   | W   | 0.266      | 0.215        | 0.010 (0.001)    | 0.275 (0.016)    | 0 (0.000) |     5.98 | dJakONdA, eksiver, H0k17, natalia_audi, WESTGOTH    |
|            5 |     5206 | 2024-10-12 | Betera Esports                 | W   | 0.265      | 0.215        | 0.006 (0.000)    | 0.299 (0.017)    | 0 (0.000) |     5.66 | dJakONdA, eksiver, H0k17, natalia_audi, WESTGOTH    |
|            4 |     5218 | 2024-10-12 | ENTERPRISE Genesis             | W   | 0.265      | 0.215        | 0.001 (0.000)    | 0.178 (0.010)    | 0 (0.000) |     4.65 | dJakONdA, eksiver, H0k17, natalia_audi, WESTGOTH    |
|            3 |     5893 | 2024-09-30 | G2 Ares                        | L   | 0.187      | -            | -                | -                | -         |    -2.21 | drawreality, eksiver, H0k17, natalia_audi, WESTGOTH |
|            2 |     5902 | 2024-09-30 | TEAM ALPHA (European mix-team) | W   | 0.187      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.43 | drawreality, eksiver, H0k17, natalia_audi, WESTGOTH |
|            1 |     6574 | 2024-09-21 | CS2NEWS                        | L   | 0.126      | -            | -                | -                | -         |    -2.28 | drawreality, eksiver, H0k17, natalia_audi, WESTGOTH |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39.87)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-12 |      0.266 | $150.00        | $39.87          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
