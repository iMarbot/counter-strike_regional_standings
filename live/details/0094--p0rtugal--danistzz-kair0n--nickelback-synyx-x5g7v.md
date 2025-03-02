### Roster Details<br />
Team Name: P0RTUGAL<br />
Roster: danistzz, KaiR0N-, NickelBack, synyx, X5G7V<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  863.2<br />
<br />
Final Rank Value (863.2) = Starting Rank Value (777.3) + Head To Head Adjustments (85.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.189<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.3
- 400 + ( ( 0.189 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 777.3


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
|           12 |     1382 | 2024-12-22 | Metizport                                 | W   | 0.741      | 0.143        | 0.074 (0.008)    | 0.513 (0.054)    | 0 (0.000) |    17.59 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           11 |     1401 | 2024-12-22 | RUSH B (Russian team)                     | W   | 0.739      | 0.143        | 0.028 (0.003)    | 0.921 (0.097)    | 0 (0.000) |    14.51 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|           10 |     1459 | 2024-12-21 | Nexus Gaming                              | W   | 0.732      | 0.143        | 0.186 (0.019)    | 0.808 (0.085)    | 0 (0.000) |    17.88 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            9 |     1771 | 2024-12-13 | NEVERMORE (Ukrainian team)                | L   | 0.680      | -            | -                | -                | -         |   -10.21 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            8 |     1778 | 2024-12-13 | ROYALS                                    | W   | 0.680      | 0.143        | 0.004 (0.000)    | 0.205 (0.020)    | 0 (0.000) |     7.24 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            7 |     1785 | 2024-12-13 | VOLT (European team)                      | W   | 0.680      | 0.143        | 0.003 (0.000)    | 0.163 (0.016)    | 0 (0.000) |     7.52 | danistzz, glowiing, KaiR0N-, synyx, X5G7V   |
|            6 |     1974 | 2024-12-08 | VOLT (European team)                      | W   | 0.647      | 0.143        | 0.003 (0.000)    | 0.163 (0.015)    | 0 (0.000) |     7.57 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            5 |     1981 | 2024-12-08 | AMKAL ESPORTS                             | W   | 0.647      | 0.143        | 0.017 (0.002)    | 0.383 (0.035)    | 0 (0.000) |    10.55 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            4 |     1995 | 2024-12-08 | Kubix Esports                             | W   | 0.647      | 0.143        | 0.045 (0.004)    | 0.496 (0.046)    | 0 (0.000) |    13.30 | danistzz, KaiR0N-, NickelBack, synyx, X5G7V |
|            3 |     4043 | 2024-11-03 | Fire Flux Esports                         | L   | 0.413      | -            | -                | -                | -         |    -4.56 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            2 |     4149 | 2024-11-02 | Dynamo Eclot                              | L   | 0.405      | -            | -                | -                | -         |    -2.20 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |
|            1 |     4605 | 2024-10-25 | Copenhagen Wolves (American organization) | W   | 0.351      | 0.384        | 0.016 (0.002)    | 1.000 (0.135)    | 0 (0.000) |     6.76 | danistzz, KaiR0N-, rexxie, TruNiQ, X5G7V    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,551.79)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.741 | $16,949.15     | $12,551.79      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
