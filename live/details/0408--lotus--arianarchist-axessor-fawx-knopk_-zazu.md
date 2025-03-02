### Roster Details<br />
Team Name: Lotus<br />
Roster: ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu<br />
Global Rank: [408](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [89]( ../standings_americas.md)<br />
<br />
Final Rank Value:  590.8<br />
<br />
Final Rank Value (590.8) = Starting Rank Value (600.5) + Head To Head Adjustments (-9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.150[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.5
- 400 + ( ( 0.100 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 600.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     4867 | 2024-10-18 | Supernova Comets | L   | 0.308      | -            | -                | -                | -         |    -3.77 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            5 |     5703 | 2024-10-03 | Nouns.fe         | L   | 0.208      | -            | -                | -                | -         |    -3.15 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            4 |     6168 | 2024-09-26 | FlyQuest RED     | L   | 0.161      | -            | -                | -                | -         |    -2.12 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            3 |     6729 | 2024-09-18 | FLUFFY MAFIA     | L   | 0.108      | -            | -                | -                | -         |    -1.57 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            2 |     7115 | 2024-09-12 | Aware Impact     | W   | 0.068      | 0.333        | 0.001 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.08 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            1 |     7635 | 2024-09-04 | Blue Otter Karma | L   | 0.015      | -            | -                | -                | -         |    -0.23 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($354.10)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.308 | $1,150.00      | $354.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
