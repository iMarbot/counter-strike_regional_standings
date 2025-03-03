### Roster Details<br />
Team Name: P0RTUGAL<br />
Roster: danistzz, KaiR0N-, NickelBack, synyx, X5G7V<br />
Global Rank: [97](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  862.1<br />
<br />
Final Rank Value (862.1) = Starting Rank Value (777.4) + Head To Head Adjustments (84.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.4
- 400 + ( ( 0.189 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 777.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1394 | 2024-12-22 | Metizport                                 | W   | 0.732      | 0.143        | 0.074 (0.008)    | 0.507 (0.053)    | 0 (0.000) |    17.36 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           11 |     1413 | 2024-12-22 | RUSH B (Russian team)                     | W   | 0.731      | 0.143        | 0.028 (0.003)    | 0.915 (0.095)    | 0 (0.000) |    14.35 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           10 |     1471 | 2024-12-21 | Nexus Gaming                              | W   | 0.724      | 0.143        | 0.187 (0.019)    | 0.795 (0.082)    | 0 (0.000) |    17.70 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            9 |     1783 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.672      | -            | -                | -                | -         |   -10.11 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            8 |     1790 | 2024-12-13 | ROYALS                                    | W   | 0.672      | 0.143        | 0.004 (0.000)    | 0.200 (0.019)    | 0 (0.000) |     7.13 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            7 |     1797 | 2024-12-13 | VOLT (European team)                      | W   | 0.671      | 0.143        | 0.003 (0.000)    | 0.162 (0.016)    | 0 (0.000) |     7.43 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            6 |     1986 | 2024-12-08 | VOLT (European team)                      | W   | 0.639      | 0.143        | 0.003 (0.000)    | 0.162 (0.015)    | 0 (0.000) |     7.47 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            5 |     1993 | 2024-12-08 | AMKAL ESPORTS                             | W   | 0.639      | 0.143        | 0.017 (0.002)    | 0.379 (0.035)    | 0 (0.000) |    10.38 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            4 |     2007 | 2024-12-08 | Kubix Esports                             | W   | 0.638      | 0.143        | 0.045 (0.004)    | 0.487 (0.044)    | 0 (0.000) |    13.09 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            3 |     4055 | 2024-11-03 | Fire Flux Esports                         | L   | 0.405      | -            | -                | -                | -         |    -4.51 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            2 |     4161 | 2024-11-02 | Dynamo Eclot                              | L   | 0.397      | -            | -                | -                | -         |    -2.17 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            1 |     4617 | 2024-10-25 | Copenhagen Wolves (American organization) | W   | 0.343      | 0.384        | 0.016 (0.002)    | 1.000 (0.132)    | 0 (0.000) |     6.58 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,412.90)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $16,949.15     | $12,412.90      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
