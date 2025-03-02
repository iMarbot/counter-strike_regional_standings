### Roster Details<br />
Team Name: Team Genesium<br />
Roster: Kanky, Saax, Sergent_polo, Supr3me, XiMaa<br />
Global Rank: [239](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [168]( ../standings_europe.md)<br />
<br />
Final Rank Value:  682.1<br />
<br />
Final Rank Value (682.1) = Starting Rank Value (682.2) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.107[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.2
- 400 + ( ( 0.141 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 682.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2209 | 2024-12-04 | GardenGarage           | L   | 0.620      | -            | -                | -                | -         |    -8.56 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            7 |     2325 | 2024-12-02 | Reveal (German team)   | W   | 0.607      | 0.333        | 0.001 (0.000)    | 0.192 (0.039)    | 0 (0.000) |     8.52 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            6 |     2418 | 2024-12-01 | Ex-DOSKI               | W   | 0.600      | 0.333        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     3.12 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            5 |     2616 | 2024-11-28 | WOPA Esport            | L   | 0.580      | -            | -                | -                | -         |    -5.46 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            4 |     2713 | 2024-11-26 | Team M33               | W   | 0.567      | 0.333        | 0.000 (0.000)    | 0.028 (0.005)    | 0 (0.000) |     2.95 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            3 |     3639 | 2024-11-10 | GODZILLA (French team) | L   | 0.461      | -            | -                | -                | -         |    -7.14 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            2 |     3652 | 2024-11-10 | Dr. Kawashima          | W   | 0.460      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.460) |     4.04 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            1 |     3664 | 2024-11-10 | GenOne Academy         | W   | 0.460      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.460) |     2.46 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($740.76)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.461 | $1,608.40      | $740.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
