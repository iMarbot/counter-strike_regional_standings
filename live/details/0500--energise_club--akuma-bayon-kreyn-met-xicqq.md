### Roster Details<br />
Team Name: Energise Club<br />
Roster: akuma, bayon, kreyn, met, XICQQ<br />
Global Rank: [500](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [312]( ../standings_europe.md)<br />
<br />
Final Rank Value:  516.1<br />
<br />
Final Rank Value (516.1) = Starting Rank Value (512.8) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 512.8
- 400 + ( ( 0.056 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 512.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     1235 | 2024-12-30 | The Agency Clan | L   | 0.794      | -            | -                | -                | -         |    -3.07 | akuma, bayon, kreyn, met, XICQQ   |
|            5 |     1564 | 2024-12-17 | Leça FC Esports | W   | 0.707      | 0.143        | 0.000 (0.000)    | 0.032 (0.003)    | 0 (0.000) |     7.92 | akuma, bayon, kreyn, met, XICQQ   |
|            4 |     1865 | 2024-12-11 | Agency CSPT     | W   | 0.667      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.40 | akuma, bayon, kreyn, met, XICQQ   |
|            3 |     4592 | 2024-10-25 | GOOFYBOYZ       | L   | 0.352      | -            | -                | -                | -         |    -2.25 | bayon, Jarimba, kreyn, met, XICQQ |
|            2 |     4771 | 2024-10-20 | The Agency Clan | L   | 0.320      | -            | -                | -                | -         |    -1.36 | bayon, Jarimba, kreyn, met, XICQQ |
|            1 |     4784 | 2024-10-20 | RogerBall       | L   | 0.319      | -            | -                | -                | -         |    -5.37 | bayon, Jarimba, kreyn, met, XICQQ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($124.19)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.794 | $156.43        | $124.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
