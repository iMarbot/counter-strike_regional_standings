### Roster Details<br />
Team Name: Chicken Coop Esports<br />
Roster: BAGEL, BiNoX, FRIZZY, LittleBEER, taggy<br />
Global Rank: [312](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
<br />
Final Rank Value:  642.0<br />
<br />
Final Rank Value (642.0) = Starting Rank Value (673.7) + Head To Head Adjustments (-31.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.7
- 400 + ( ( 0.137 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 673.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      578 | 2025-02-10 | MIGHT              | L   | 1.000      | -            | -                | -                | -         |   -13.09 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           12 |      618 | 2025-02-09 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |    -8.97 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           11 |      667 | 2025-02-08 | LAG Gaming         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    12.34 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           10 |      734 | 2025-02-07 | Vagrants           | L   | 1.000      | -            | -                | -                | -         |   -14.68 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|            9 |     1819 | 2024-12-12 | Bad News Capybaras | L   | 0.676      | -            | -                | -                | -         |   -11.73 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            8 |     1861 | 2024-12-11 | InControl          | W   | 0.669      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.35 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            7 |     1906 | 2024-12-10 | Bad News Capybaras | L   | 0.662      | -            | -                | -                | -         |   -11.90 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            6 |     2045 | 2024-12-07 | Alter Iron Club    | L   | 0.642      | -            | -                | -                | -         |    -8.97 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            5 |     2241 | 2024-12-03 | Make Your Mind     | L   | 0.616      | -            | -                | -                | -         |    -8.88 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            4 |     2308 | 2024-12-02 | MCS Gaming         | W   | 0.609      | 0.372        | 0.003 (0.001)    | 0.344 (0.078)    | 0 (0.000) |     8.48 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            3 |     2379 | 2024-12-01 | MIGHT              | W   | 0.602      | 0.372        | 0.002 (0.000)    | 0.444 (0.100)    | 0 (0.000) |    10.71 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            2 |     2567 | 2024-11-29 | Bad Boys           | W   | 0.589      | 0.372        | 0.004 (0.001)    | 0.144 (0.032)    | 0 (0.000) |     8.52 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            1 |     2689 | 2024-11-26 | Zomblers           | W   | 0.569      | 0.372        | 0.000 (0.000)    | 0.047 (0.010)    | 0 (0.000) |     3.16 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,141.79)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.649 | $3,300.00      | $2,141.79       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
