### Roster Details<br />
Team Name: TSM Impact<br />
Roster: bungee, di^, Juli, Lx, madss<br />
Global Rank: [361](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [76]( ../standings_americas.md)<br />
<br />
Final Rank Value:  620.7<br />
<br />
Final Rank Value (620.7) = Starting Rank Value (618.2) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 618.2
- 400 + ( ( 0.109 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 618.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4882 | 2024-10-18 | FLUFFY MAFIA     | W   | 0.300      | 0.333        | 0.002 (0.000)    | 0.024 (0.002)    | 0 (0.000) |     4.89 | bungee, di^, Juli, Lx, madss |
|            5 |     5756 | 2024-10-02 | Supernova Comets | L   | 0.193      | -            | -                | -                | -         |    -2.08 | bungee, di^, Juli, Lx, madss |
|            4 |     6181 | 2024-09-26 | Aware Impact     | L   | 0.153      | -            | -                | -                | -         |    -2.53 | bungee, di^, Juli, Lx, madss |
|            3 |     6742 | 2024-09-18 | Nouns.fe         | W   | 0.100      | 0.333        | 0.001 (0.000)    | 0.070 (0.002)    | 0 (0.000) |     1.55 | bungee, di^, Juli, Lx, madss |
|            2 |     7172 | 2024-09-11 | Blue Otter Karma | W   | 0.053      | 0.333        | 0.001 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.80 | bungee, di^, Juli, Lx, madss |
|            1 |     7648 | 2024-09-04 | FlyQuest RED     | L   | 0.006      | -            | -                | -                | -         |    -0.09 | bungee, di^, Juli, Lx, madss |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($434.60)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.300 | $1,450.00      | $434.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
