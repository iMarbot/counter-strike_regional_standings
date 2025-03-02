### Roster Details<br />
Team Name: Homyno<br />
Roster: Gabie, J0LZ, Melio, Sup3rant, YuZ<br />
Global Rank: [176](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  731.2<br />
<br />
Final Rank Value (731.2) = Starting Rank Value (713.8) + Head To Head Adjustments (17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.8
- 400 + ( ( 0.157 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 713.8


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
|           20 |     1598 | 2024-12-15 | Hite Gaming                 | W   | 0.696      | 0.333        | 0.005 (0.001)    | 0.063 (0.015)    | 0 (0.000) |     8.84 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           19 |     1738 | 2024-12-13 | Masso Chiasson              | W   | 0.682      | 0.333        | 0.003 (0.001)    | 0.031 (0.007)    | 0 (0.000) |     7.77 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           18 |     1820 | 2024-12-12 | Fisher College              | W   | 0.675      | 0.333        | 0.008 (0.002)    | 0.327 (0.074)    | 0 (0.000) |    12.65 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           17 |     1854 | 2024-12-11 | Reunion                     | W   | 0.669      | 0.333        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.64 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           16 |     1904 | 2024-12-10 | Bass Masters                | W   | 0.662      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     5.68 | Gabie, J0LZ, Melio, Sup3rant, YuZ  |
|           15 |     3401 | 2024-11-15 | Metizport                   | L   | 0.492      | -            | -                | -                | -         |    -1.55 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           14 |     3408 | 2024-11-15 | Mindfreak (Australian team) | L   | 0.491      | -            | -                | -                | -         |    -7.53 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           13 |     3424 | 2024-11-14 | Team Norway                 | L   | 0.487      | -            | -                | -                | -         |    -9.57 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           12 |     3505 | 2024-11-13 | Los kogutos                 | L   | 0.479      | -            | -                | -                | -         |    -3.99 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           11 |     3509 | 2024-11-13 | PCIFIC Espor                | W   | 0.479      | 0.617        | 0.004 (0.001)    | 0.254 (0.075)    | 1 (0.479) |     8.71 | Gabie, J0LZ, Melio, Pluto, YuZ     |
|           10 |     6359 | 2024-09-24 | Team Aether                 | L   | 0.147      | -            | -                | -                | -         |    -3.50 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            9 |     6431 | 2024-09-23 | Mythic                      | L   | 0.141      | -            | -                | -                | -         |    -3.40 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            8 |     6662 | 2024-09-19 | Jahsdnmasjdm v2             | W   | 0.115      | 0.371        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     0.81 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            7 |     6802 | 2024-09-17 | Akimbo Esports              | L   | 0.101      | -            | -                | -                | -         |    -1.85 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            6 |     6909 | 2024-09-15 | MIGHT                       | L   | 0.088      | -            | -                | -                | -         |    -1.28 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            5 |     7110 | 2024-09-12 | Lore Gaming                 | W   | 0.068      | 0.371        | 0.000 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     0.32 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            4 |     7267 | 2024-09-09 | Akimbo Esports              | L   | 0.049      | -            | -                | -                | -         |    -0.90 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            3 |     7369 | 2024-09-07 | Exceritus                   | W   | 0.035      | 0.372        | 0.000 (0.000)    | 0.238 (0.003)    | 0 (0.000) |     0.41 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            2 |     7542 | 2024-09-05 | Regain                      | W   | 0.022      | 0.372        | 0.000 (0.000)    | 0.157 (0.001)    | 0 (0.000) |     0.15 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|            1 |     7694 | 2024-09-03 | After Hours                 | W   | 0.008      | 0.372        | -                | 0.025 (0.000)    | -         |     0.04 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,595.52)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.696 | $3,500.00      | $2,434.93       |
| 2024-09-21 |      0.128 | $1,250.00      | $160.59         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
