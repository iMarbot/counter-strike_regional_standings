### Roster Details<br />
Team Name: Alter Ego<br />
Roster: aidKiT, BnTeT, dobu, Freeman, XigN<br />
Global Rank: [442](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [72]( ../standings_asia.md)<br />
<br />
Final Rank Value:  564.2<br />
<br />
Final Rank Value (564.2) = Starting Rank Value (566.4) + Head To Head Adjustments (-2.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.201[<sup>1</sup>](#table2)
- Bounty Collected: 0.132[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.083<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 566.4
- 400 + ( ( 0.083 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 566.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     3593 | 2024-11-11 | Lynn Vision Gaming | L   | 0.461      | -            | -                | -                | -         |    -2.44 | aidKiT, BnTeT, dobu, Freeman, XigN        |
|            5 |     3648 | 2024-11-11 | The MongolZ        | L   | 0.456      | -            | -                | -                | -         |    -0.01 | aidKiT, BnTeT, dobu, Freeman, XigN        |
|            4 |     6600 | 2024-09-21 | Chinggis Warriors  | L   | 0.117      | -            | -                | -                | -         |    -1.50 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN |
|            3 |     7208 | 2024-09-11 | Chinggis Warriors  | W   | 0.050      | 0.250        | 0.000 (0.000)    | 0.027 (0.000)    | 0 (0.000) |     0.93 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN |
|            2 |     7322 | 2024-09-09 | Oni CLAN           | W   | 0.037      | 0.250        | 0.000 (0.000)    | 0.030 (0.000)    | 0 (0.000) |     0.51 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN |
|            1 |     7460 | 2024-09-07 | THE (Russian team) | W   | 0.023      | 0.250        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.28 | aidKiT, BnTeT, Freeman, WasteOfAmmo, XigN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.117 | $300.00        | $35.00          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
