### Roster Details<br />
Team Name: Team Genesium<br />
Roster: Kanky, Saax, Sergent_polo, Supr3me, XiMaa<br />
Global Rank: [245](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [170]( ../standings_europe.md)<br />
<br />
Final Rank Value:  681.7<br />
<br />
Final Rank Value (681.7) = Starting Rank Value (681.7) + Head To Head Adjustments (-0.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.7
- 400 + ( ( 0.141 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 681.7


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
|            8 |     2221 | 2024-12-04 | GardenGarage           | L   | 0.612      | -            | -                | -                | -         |    -8.43 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            7 |     2337 | 2024-12-02 | Reveal (German team)   | W   | 0.599      | 0.333        | 0.001 (0.000)    | 0.187 (0.037)    | 0 (0.000) |     8.41 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            6 |     2428 | 2024-12-01 | Ex-DOSKI               | W   | 0.592      | 0.333        | 0.000 (0.000)    | 0.019 (0.004)    | 0 (0.000) |     3.08 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            5 |     2628 | 2024-11-28 | WOPA Esport            | L   | 0.572      | -            | -                | -                | -         |    -5.40 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            4 |     2725 | 2024-11-26 | Team M33               | W   | 0.559      | 0.333        | 0.000 (0.000)    | 0.028 (0.005)    | 0 (0.000) |     2.91 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            3 |     3651 | 2024-11-10 | GODZILLA (French team) | L   | 0.452      | -            | -                | -                | -         |    -7.02 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            2 |     3664 | 2024-11-10 | Dr. Kawashima          | W   | 0.452      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.452) |     3.98 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |
|            1 |     3676 | 2024-11-10 | GenOne Academy         | W   | 0.451      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.451) |     2.42 | Kanky, Saax, Sergent_polo, Supr3me, XiMaa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($727.58)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.452 | $1,608.40      | $727.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
