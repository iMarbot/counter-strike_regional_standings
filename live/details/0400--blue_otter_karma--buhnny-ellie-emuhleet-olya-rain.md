### Roster Details<br />
Team Name: Blue Otter Karma<br />
Roster: buhnny, Ellie, EMUHLEET, olya, rain<br />
Global Rank: [400](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [85]( ../standings_americas.md)<br />
<br />
Final Rank Value:  596.5<br />
<br />
Final Rank Value (596.5) = Starting Rank Value (605.0) + Head To Head Adjustments (-8.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.157[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.0
- 400 + ( ( 0.103 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 605.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4868 | 2024-10-18 | Nouns.fe     | L   | 0.308      | -            | -                | -                | -         |    -4.66 | buhnny, Ellie, EMUHLEET, olya, rain |
|            5 |     5743 | 2024-10-02 | FlyQuest RED | L   | 0.201      | -            | -                | -                | -         |    -2.65 | buhnny, Ellie, EMUHLEET, olya, rain |
|            4 |     6250 | 2024-09-25 | FLUFFY MAFIA | L   | 0.155      | -            | -                | -                | -         |    -2.27 | buhnny, Ellie, EMUHLEET, olya, rain |
|            3 |     6667 | 2024-09-19 | Aware Impact | W   | 0.115      | 0.333        | 0.001 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.80 | buhnny, Ellie, EMUHLEET, olya, rain |
|            2 |     7160 | 2024-09-11 | TSM Impact   | L   | 0.061      | -            | -                | -                | -         |    -0.93 | buhnny, Ellie, EMUHLEET, olya, rain |
|            1 |     7635 | 2024-09-04 | Lotus        | W   | 0.015      | 0.333        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.23 | buhnny, Ellie, EMUHLEET, olya, rain |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($384.90)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.308 | $1,250.00      | $384.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
