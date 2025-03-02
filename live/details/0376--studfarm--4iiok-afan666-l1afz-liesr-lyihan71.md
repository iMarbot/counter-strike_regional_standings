### Roster Details<br />
Team Name: StudFarm<br />
Roster: 4iiok, Afan666, L1afz, Liesr, Lyihan71<br />
Global Rank: [376](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [62]( ../standings_asia.md)<br />
<br />
Final Rank Value:  609.8<br />
<br />
Final Rank Value (609.8) = Starting Rank Value (604.2) + Head To Head Adjustments (5.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.195[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.102<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 604.2
- 400 + ( ( 0.102 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 604.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     5612 | 2024-10-05 | FengDa Gaming    | L   | 0.218      | -            | -                | -                | -         |    -2.60 | 4iiok, Afan666, L1afz, Liesr, Lyihan71 |
|            4 |     5620 | 2024-10-05 | Magic Cape       | W   | 0.217      | 0.143        | 0.004 (0.000)    | 0.201 (0.006)    | 0 (0.000) |     4.14 | 4iiok, Afan666, L1afz, Liesr, Lyihan71 |
|            3 |     5624 | 2024-10-05 | ShanghaiBaiDuRen | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.31 | 4iiok, Afan666, L1afz, Liesr, Lyihan71 |
|            2 |     5679 | 2024-10-04 | CatEvil          | L   | 0.211      | -            | -                | -                | -         |    -3.08 | 4iiok, Afan666, L1afz, Liesr, Lyihan71 |
|            1 |     5685 | 2024-10-04 | Change The Game  | W   | 0.211      | 0.143        | 0.061 (0.002)    | 0.221 (0.007)    | 0 (0.000) |     4.89 | 4iiok, Afan666, L1afz, Liesr, Lyihan71 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25.52)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-06 |      0.224 | $113.99        | $25.52          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
