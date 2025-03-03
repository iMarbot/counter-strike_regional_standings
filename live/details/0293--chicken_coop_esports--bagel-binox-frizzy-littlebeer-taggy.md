### Roster Details<br />
Team Name: Chicken Coop Esports<br />
Roster: BAGEL, BiNoX, FRIZZY, LittleBEER, taggy<br />
Global Rank: [293](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [59]( ../standings_americas.md)<br />
<br />
Final Rank Value:  653.4<br />
<br />
Final Rank Value (653.4) = Starting Rank Value (677.1) + Head To Head Adjustments (-23.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.1
- 400 + ( ( 0.139 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 677.1


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
|           13 |      590 | 2025-02-10 | MIGHT              | L   | 1.000      | -            | -                | -                | -         |   -11.64 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           12 |      630 | 2025-02-09 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |    -9.08 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           11 |      679 | 2025-02-08 | LAG Gaming         | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.120 (0.017)    | 0 (0.000) |    18.09 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|           10 |      746 | 2025-02-07 | Vagrants           | L   | 1.000      | -            | -                | -                | -         |   -14.88 | BAGEL, BiNoX, FRIZZY, LittleBEER, taggy |
|            9 |     1831 | 2024-12-12 | Bad News Capybaras | L   | 0.667      | -            | -                | -                | -         |   -11.55 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            8 |     1873 | 2024-12-11 | InControl          | W   | 0.661      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.25 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            7 |     1918 | 2024-12-10 | Bad News Capybaras | L   | 0.654      | -            | -                | -                | -         |   -11.70 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            6 |     2057 | 2024-12-07 | SUPER EVIL GANG    | L   | 0.634      | -            | -                | -                | -         |    -8.95 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            5 |     2253 | 2024-12-03 | Make Your Mind     | L   | 0.608      | -            | -                | -                | -         |    -8.87 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            4 |     2320 | 2024-12-02 | MCS Gaming         | W   | 0.601      | 0.372        | 0.003 (0.001)    | 0.343 (0.077)    | 0 (0.000) |     8.29 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            3 |     2391 | 2024-12-01 | MIGHT              | W   | 0.594      | 0.372        | 0.002 (0.000)    | 0.489 (0.108)    | 0 (0.000) |    11.88 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            2 |     2579 | 2024-11-29 | Bad Boys           | W   | 0.581      | 0.372        | 0.004 (0.001)    | 0.142 (0.031)    | 0 (0.000) |     8.33 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |
|            1 |     2701 | 2024-11-26 | Zomblers           | W   | 0.561      | 0.372        | 0.000 (0.000)    | 0.047 (0.010)    | 0 (0.000) |     3.06 | BAGEL, Freaky, FRIZZY, LittleBEER, supa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,114.75)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $3,300.00      | $2,114.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
