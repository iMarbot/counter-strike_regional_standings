### Roster Details<br />
Team Name: Blaze (Uzbek team)<br />
Roster: BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr<br />
Global Rank: [180](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
<br />
Final Rank Value:  725.6<br />
<br />
Final Rank Value (725.6) = Starting Rank Value (727.9) + Head To Head Adjustments (-2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.163[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 727.9
- 400 + ( ( 0.164 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 727.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1356 | 2024-12-25 | GamePoint (Uzbek team) | W   | 0.758      | 0.143        | 0.003 (0.000)    | 0.034 (0.004)    | 1 (0.758) |     6.45 | BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr |
|            4 |     1448 | 2024-12-21 | OCTAZONE               | W   | 0.733      | 0.143        | 0.001 (0.000)    | 0.034 (0.004)    | 0 (0.000) |     5.52 | BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr |
|            3 |     1806 | 2024-12-13 | DEPO                   | L   | 0.678      | -            | -                | -                | -         |    -8.62 | BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr |
|            2 |     1814 | 2024-12-12 | ALLINNERS              | L   | 0.677      | -            | -                | -                | -         |   -10.47 | BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr |
|            1 |     2032 | 2024-12-07 | OCTAZONE               | W   | 0.644      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.644) |     4.82 | BEASTOFEAST, CEKKA, KanshineF, teygu, yngtrxpstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,761.99)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-25 |      0.758 | $2,325.21      | $1,761.99       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
