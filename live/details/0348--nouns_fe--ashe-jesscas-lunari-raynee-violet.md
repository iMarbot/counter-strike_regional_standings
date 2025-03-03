### Roster Details<br />
Team Name: Nouns.fe<br />
Roster: ashe, jesscas, lunari, raynee, violet<br />
Global Rank: [348](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [73]( ../standings_americas.md)<br />
<br />
Final Rank Value:  625.8<br />
<br />
Final Rank Value (625.8) = Starting Rank Value (615.4) + Head To Head Adjustments (10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 615.4
- 400 + ( ( 0.108 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 615.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     1061 | 2025-02-01 | MEGA JUNERS      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     6.93 | ashe, jesscas, lunari, raynee, violet    |
|            6 |     4880 | 2024-10-18 | Blue Otter Karma | W   | 0.300      | 0.333        | 0.001 (0.000)    | 0.005 (0.001)    | 0 (0.000) |     4.52 | ashe, jesscas, katalyyst, lunari, raynee |
|            5 |     5715 | 2024-10-03 | Lotus            | W   | 0.200      | 0.333        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     3.02 | ashe, jesscas, katalyyst, lunari, raynee |
|            4 |     6261 | 2024-09-25 | Supernova Comets | L   | 0.146      | -            | -                | -                | -         |    -1.56 | ashe, jesscas, katalyyst, lunari, raynee |
|            3 |     6742 | 2024-09-18 | TSM Impact       | L   | 0.100      | -            | -                | -                | -         |    -1.55 | ashe, jesscas, katalyyst, lunari, raynee |
|            2 |     7171 | 2024-09-11 | FlyQuest RED     | L   | 0.053      | -            | -                | -                | -         |    -0.74 | ashe, jesscas, katalyyst, lunari, raynee |
|            1 |     7560 | 2024-09-05 | FLUFFY MAFIA     | L   | 0.013      | -            | -                | -                | -         |    -0.20 | ashe, Chowdzz, jesscas, lunari, raynee   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($404.63)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.300 | $1,350.00      | $404.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
