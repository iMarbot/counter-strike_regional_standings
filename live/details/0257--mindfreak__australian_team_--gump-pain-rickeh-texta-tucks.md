### Roster Details<br />
Team Name: Mindfreak (Australian team)<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [257](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [34]( ../standings_asia.md)<br />
<br />
Final Rank Value:  675.2<br />
<br />
Final Rank Value (675.2) = Starting Rank Value (706.8) + Head To Head Adjustments (-31.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.268[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.8
- 400 + ( ( 0.154 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 706.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      646 | 2025-02-08 | Chinggis Warriors                | L   | 1.000      | -            | -                | -                | -         |    -8.60 | gump, pain, Rickeh, Texta, tucks      |
|           24 |      727 | 2025-02-07 | Believe.                         | L   | 1.000      | -            | -                | -                | -         |   -21.78 | gump, pain, Rickeh, Texta, tucks      |
|           23 |     2914 | 2024-11-22 | Justice For Tomorrow             | L   | 0.543      | -            | -                | -                | -         |   -10.38 | gump, Omichella, Rickeh, Texta, tucks |
|           22 |     2918 | 2024-11-22 | Housebets                        | W   | 0.543      | 0.264        | 0.001 (0.000)    | 0.123 (0.018)    | 0 (0.000) |     6.49 | gump, Omichella, Rickeh, Texta, tucks |
|           21 |     3396 | 2024-11-15 | Los kogutos                      | L   | 0.492      | -            | -                | -                | -         |    -4.02 | gump, pain, Rickeh, Texta, tucks      |
|           20 |     3408 | 2024-11-15 | Homyno                           | W   | 0.491      | 0.617        | 0.008 (0.002)    | 0.192 (0.058)    | 1 (0.491) |     7.53 | gump, pain, Rickeh, Texta, tucks      |
|           19 |     3420 | 2024-11-14 | PCIFIC Espor                     | L   | 0.487      | -            | -                | -                | -         |    -6.40 | gump, pain, Rickeh, Texta, tucks      |
|           18 |     3506 | 2024-11-13 | Team Norway                      | L   | 0.479      | -            | -                | -                | -         |    -9.85 | gump, pain, Rickeh, Texta, tucks      |
|           17 |     3510 | 2024-11-13 | Metizport                        | L   | 0.479      | -            | -                | -                | -         |    -1.72 | gump, pain, Rickeh, Texta, tucks      |
|           16 |     4823 | 2024-10-19 | FlyQuest                         | L   | 0.316      | -            | -                | -                | -         |    -1.02 | gump, pain, Rickeh, Texta, tucks      |
|           15 |     4864 | 2024-10-19 | Housebets                        | W   | 0.310      | 0.333        | 0.001 (0.000)    | 0.123 (0.013)    | 0 (0.000) |     3.64 | gump, pain, Rickeh, Texta, tucks      |
|           14 |     4907 | 2024-10-18 | FlyQuest                         | L   | 0.304      | -            | -                | -                | -         |    -0.97 | gump, pain, Rickeh, Texta, tucks      |
|           13 |     4959 | 2024-10-17 | Only One Word                    | W   | 0.297      | 0.333        | 0.001 (0.000)    | 0.191 (0.019)    | 0 (0.000) |     3.73 | gump, pain, Rickeh, Texta, tucks      |
|           12 |     5363 | 2024-10-09 | FlyQuest                         | W   | 0.244      | 0.333        | 0.105 (0.009)    | 0.239 (0.019)    | 0 (0.000) |     6.97 | gump, pain, Rickeh, Texta, tucks      |
|           11 |     5366 | 2024-10-09 | FlyQuest                         | W   | 0.244      | 0.333        | 0.105 (0.009)    | 0.239 (0.019)    | 0 (0.000) |     7.01 | gump, pain, Rickeh, Texta, tucks      |
|           10 |     5550 | 2024-10-05 | Only One Word                    | L   | 0.222      | -            | -                | -                | -         |    -4.16 | gump, pain, Rickeh, Texta, tucks      |
|            9 |     5633 | 2024-10-04 | SemperFi Esports                 | L   | 0.216      | -            | -                | -                | -         |    -4.82 | gump, pain, Rickeh, Texta, tucks      |
|            8 |     5635 | 2024-10-04 | Housebets                        | W   | 0.216      | -            | -                | -                | 0 (0.000) |     2.59 | gump, pain, Rickeh, Texta, tucks      |
|            7 |     5641 | 2024-10-04 | Above The Rest (Australian team) | W   | 0.215      | -            | -                | -                | 0 (0.000) |     1.01 | gump, pain, Rickeh, Texta, tucks      |
|            6 |     5797 | 2024-10-02 | KZG                              | W   | 0.198      | 0.333        | 0.001 (0.000)    | 0.165 (0.011)    | 0 (0.000) |     2.38 | gump, pain, Rickeh, Texta, tucks      |
|            5 |     5799 | 2024-10-02 | KZG                              | W   | 0.197      | 0.333        | 0.001 (0.000)    | 0.165 (0.011)    | 0 (0.000) |     2.42 | gump, pain, Rickeh, Texta, tucks      |
|            4 |     6319 | 2024-09-25 | Only One Word                    | W   | 0.151      | 0.333        | 0.001 (0.000)    | 0.191 (0.010)    | -         |     1.94 | gump, pain, Rickeh, Texta, tucks      |
|            3 |     6325 | 2024-09-25 | Only One Word                    | L   | 0.151      | -            | -                | -                | -         |    -2.84 | gump, pain, Rickeh, Texta, tucks      |
|            2 |     6776 | 2024-09-18 | Housebets                        | W   | 0.104      | 0.333        | 0.001 (0.000)    | 0.123 (0.004)    | -         |     1.29 | gump, pain, Rickeh, Texta, tucks      |
|            1 |     6777 | 2024-09-18 | Housebets                        | L   | 0.104      | -            | -                | -                | -         |    -2.00 | gump, pain, Rickeh, Texta, tucks      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($632.78)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.316 | $2,000.00      | $632.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
