### Roster Details<br />
Team Name: RED Canids<br />
Roster: dav1deuS, hardzao, HEN1, nython, venomzera<br />
Global Rank: [218](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [42]( ../standings_americas.md)<br />
<br />
Final Rank Value:  701.7<br />
<br />
Final Rank Value (701.7) = Starting Rank Value (693.6) + Head To Head Adjustments (8.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.6
- 400 + ( ( 0.147 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 693.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     6358 | 2024-09-24 | ODDIK       | W   | 0.140      | 0.450        | 0.028 (0.002)    | 0.518 (0.033)    | 0 (0.000) |     2.91 | dav1deuS, hardzao, HEN1, nython, venomzera |
|            4 |     6364 | 2024-09-24 | ODDIK       | L   | 0.139      | -            | -                | -                | -         |    -1.49 | dav1deuS, hardzao, HEN1, nython, venomzera |
|            3 |     6383 | 2024-09-24 | Fluxo       | W   | 0.138      | 0.143        | 0.056 (0.001)    | 0.423 (0.008)    | 0 (0.000) |     3.42 | dav1deuS, gtw, HEN1, nython, venomzera     |
|            2 |     6449 | 2024-09-23 | PaiN Gaming | L   | 0.132      | -            | -                | -                | -         |    -0.02 | dav1deuS, gtw, HEN1, nython, venomzera     |
|            1 |     6476 | 2024-09-23 | Fluxo       | W   | 0.131      | 0.143        | 0.056 (0.001)    | 0.423 (0.008)    | 0 (0.000) |     3.26 | dav1deuS, gtw, HEN1, nython, venomzera     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,041.29)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.312 | $5,000.00      | $1,559.72       |
| 2024-10-05 |      0.211 | $16,491.66     | $3,481.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
