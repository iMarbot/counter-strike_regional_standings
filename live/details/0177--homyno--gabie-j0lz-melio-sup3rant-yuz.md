### Roster Details<br />
Team Name: Homyno<br />
Roster: Gabie, J0LZ, Melio, Sup3rant, YuZ<br />
Global Rank: [177](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  731.4<br />
<br />
Final Rank Value (731.4) = Starting Rank Value (713.6) + Head To Head Adjustments (17.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.6
- 400 + ( ( 0.157 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 713.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1610 | 2024-12-15 | Hite Gaming                 | W   | 0.688      | 0.333        | 0.005 (0.001)    | 0.062 (0.014)    | 0 (0.000) |     8.74 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           19 |     1750 | 2024-12-13 | Masso Chiasson              | W   | 0.674      | 0.333        | 0.003 (0.001)    | 0.031 (0.007)    | 0 (0.000) |     7.69 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           18 |     1832 | 2024-12-12 | Fisher College              | W   | 0.667      | 0.333        | 0.008 (0.002)    | 0.324 (0.072)    | 0 (0.000) |    12.51 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           17 |     1866 | 2024-12-11 | Reunion                     | W   | 0.661      | 0.333        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.57 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           16 |     1916 | 2024-12-10 | Bass Masters                | W   | 0.654      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     5.60 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           15 |     3413 | 2024-11-15 | Metizport                   | L   | 0.484      | -            | -                | -                | -         |    -1.55 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           14 |     3420 | 2024-11-15 | Mindfreak (Australian team) | L   | 0.483      | -            | -                | -                | -         |    -7.43 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           13 |     3436 | 2024-11-14 | Team Norway                 | L   | 0.479      | -            | -                | -                | -         |    -9.45 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           12 |     3517 | 2024-11-13 | Los kogutos                 | L   | 0.471      | -            | -                | -                | -         |    -3.95 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           11 |     3521 | 2024-11-13 | PCIFIC Espor                | W   | 0.470      | 0.617        | 0.004 (0.001)    | 0.251 (0.073)    | 1 (0.470) |     8.54 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           10 |     6371 | 2024-09-24 | Team Aether                 | L   | 0.139      | -            | -                | -                | -         |    -3.30 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            9 |     6443 | 2024-09-23 | Mythic                      | L   | 0.133      | -            | -                | -                | -         |    -3.18 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            8 |     6674 | 2024-09-19 | Jahsdnmasjdm v2             | W   | 0.107      | 0.371        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     0.75 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            7 |     6814 | 2024-09-17 | Akimbo Esports              | L   | 0.093      | -            | -                | -                | -         |    -1.71 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            6 |     6921 | 2024-09-15 | MIGHT                       | L   | 0.080      | -            | -                | -                | -         |    -0.96 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            5 |     7122 | 2024-09-12 | Lore Gaming                 | W   | 0.060      | 0.371        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.28 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            4 |     7279 | 2024-09-09 | Akimbo Esports              | L   | 0.040      | -            | -                | -                | -         |    -0.75 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            3 |     7381 | 2024-09-07 | Exceritus                   | W   | 0.027      | 0.372        | 0.000 (0.000)    | 0.238 (0.002)    | 0 (0.000) |     0.32 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            2 |     7554 | 2024-09-05 | Regain                      | W   | 0.014      | 0.372        | 0.000 (0.000)    | 0.155 (0.001)    | 0 (0.000) |     0.10 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            1 |     7706 | 2024-09-03 | After Hours                 | W   | 0.000      | 0.372        | -                | 0.024 (0.000)    | -         |     0.00 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,556.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.688 | $3,500.00      | $2,406.25       |
| 2024-09-21 |      0.120 | $1,250.00      | $150.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
