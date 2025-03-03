### Roster Details<br />
Team Name: Lotus<br />
Roster: ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu<br />
Global Rank: [410](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [92]( ../standings_americas.md)<br />
<br />
Final Rank Value:  591.4<br />
<br />
Final Rank Value (591.4) = Starting Rank Value (600.0) + Head To Head Adjustments (-8.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.149[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.0
- 400 + ( ( 0.100 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 600.0


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
|            6 |     4879 | 2024-10-18 | Supernova Comets | L   | 0.300      | -            | -                | -                | -         |    -3.00 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            5 |     5715 | 2024-10-03 | Nouns.fe         | L   | 0.200      | -            | -                | -                | -         |    -3.02 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            4 |     6180 | 2024-09-26 | FlyQuest RED     | L   | 0.153      | -            | -                | -                | -         |    -2.01 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            3 |     6741 | 2024-09-18 | FLUFFY MAFIA     | L   | 0.100      | -            | -                | -                | -         |    -1.45 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            2 |     7127 | 2024-09-12 | Aware Impact     | W   | 0.060      | 0.333        | 0.001 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     0.95 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |
|            1 |     7647 | 2024-09-04 | Blue Otter Karma | L   | 0.006      | -            | -                | -                | -         |    -0.10 | ARIANARCHIST, Axessor, Fawx, Knopk@, Zazu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($344.68)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.300 | $1,150.00      | $344.68         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
