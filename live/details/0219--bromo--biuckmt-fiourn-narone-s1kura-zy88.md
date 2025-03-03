### Roster Details<br />
Team Name: Bromo<br />
Roster: Biuckmt, FIOURN, NARONE, S1kura, Zy88<br />
Global Rank: [219](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [24]( ../standings_asia.md)<br />
<br />
Final Rank Value:  698.4<br />
<br />
Final Rank Value (698.4) = Starting Rank Value (698.1) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 698.1
- 400 + ( ( 0.149 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 698.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1246 | 2024-12-30 | E9 Esports              | L   | 0.788      | -            | -                | -                | -         |   -18.61 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            7 |     1319 | 2024-12-28 | DogEvil                 | L   | 0.770      | -            | -                | -                | -         |    -8.83 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            6 |     1348 | 2024-12-27 | Unsettled Resentment    | L   | 0.763      | -            | -                | -                | -         |   -11.65 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            5 |     2360 | 2024-12-02 | Nomads (Mongolian team) | W   | 0.597      | 0.143        | 0.000 (0.000)    | 0.407 (0.035)    | 0 (0.000) |     4.69 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            4 |     2364 | 2024-12-02 | The Huns Esports        | W   | 0.597      | 0.143        | 0.025 (0.002)    | 0.553 (0.047)    | 0 (0.000) |    13.43 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            3 |     2367 | 2024-12-02 | SUBUTAI                 | W   | 0.596      | 0.143        | 0.001 (0.000)    | 0.051 (0.004)    | 0 (0.000) |     4.61 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            2 |     2375 | 2024-12-02 | Eruption                | W   | 0.596      | 0.143        | 0.014 (0.001)    | 0.551 (0.047)    | 0 (0.000) |    13.80 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |
|            1 |     2379 | 2024-12-01 | Aogiri                  | W   | 0.596      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.82 | Biuckmt, FIOURN, NARONE, S1kura, Zy88 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,402.25)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.789 | $6,849.13      | $5,402.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
