### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [208](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [151]( ../standings_europe.md)<br />
<br />
Final Rank Value:  707.5<br />
<br />
Final Rank Value (707.5) = Starting Rank Value (688.4) + Head To Head Adjustments (19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 688.4
- 400 + ( ( 0.144 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 688.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     1837 | 2024-12-12 | Fire Flux Esports   | L   | 0.673      | -            | -                | -                | -         |    -4.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     1878 | 2024-12-11 | CYBERSHOKE Esports  | L   | 0.667      | -            | -                | -                | -         |    -6.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     1921 | 2024-12-10 | FLuffy Gangsters    | W   | 0.660      | 0.143        | 0.014 (0.001)    | 0.925 (0.087)    | 0 (0.000) |    14.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     5792 | 2024-10-02 | Partizan Esports    | L   | 0.198      | -            | -                | -                | -         |    -0.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     5921 | 2024-09-30 | Team Space          | W   | 0.185      | 0.384        | -                | 0.023 (0.002)    | 0 (0.000) |     1.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     5979 | 2024-09-29 | 500                 | W   | 0.178      | 0.143        | 0.091 (0.002)    | 1.000 (0.025)    | 0 (0.000) |     4.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     6232 | 2024-09-26 | B8                  | L   | 0.157      | -            | -                | -                | -         |    -0.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     6521 | 2024-09-22 | Lynn Vision Gaming  | W   | 0.132      | 0.435        | 0.017 (0.001)    | 0.368 (0.021)    | 0 (0.000) |     3.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     6640 | 2024-09-20 | Rebels Gaming       | L   | 0.118      | -            | -                | -                | -         |    -1.67 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     6652 | 2024-09-20 | Los kogutos         | W   | 0.117      | 0.435        | 0.032 (0.002)    | 0.527 (0.027)    | 0 (0.000) |     3.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     6757 | 2024-09-18 | Endpoint            | L   | 0.106      | -            | -                | -                | -         |    -1.31 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     6905 | 2024-09-16 | The Suspect         | W   | 0.090      | 0.435        | 0.003 (0.000)    | 0.220 (0.009)    | 0 (0.000) |     1.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     6939 | 2024-09-15 | SINNERS Esports     | L   | 0.085      | -            | -                | -                | -         |    -0.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     6988 | 2024-09-14 | BC.Game Esports     | W   | 0.079      | 0.435        | 0.077 (0.003)    | 0.945 (0.033)    | 0 (0.000) |     2.19 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     7035 | 2024-09-14 | CYBERSHOKE Esports  | W   | 0.078      | 0.384        | 0.011 (0.000)    | 1.000 (0.030)    | 0 (0.000) |     1.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     7148 | 2024-09-12 | SAW                 | W   | 0.064      | 0.435        | 0.262 (0.007)    | 0.329 (0.009)    | 0 (0.000) |     1.98 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     7247 | 2024-09-10 | Revenant Esports    | W   | 0.052      | -            | -                | -                | 0 (0.000) |     0.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     7348 | 2024-09-08 | Rhyno Esports       | W   | 0.039      | 0.435        | 0.002 (0.000)    | -                | -         |     0.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     7364 | 2024-09-08 | SINNERS Esports     | W   | 0.037      | 0.384        | 0.027 (0.000)    | 0.451 (0.007)    | -         |     0.93 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     7483 | 2024-09-07 | Monte               | L   | 0.030      | -            | -                | -                | -         |    -0.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     7512 | 2024-09-06 | Team Space          | W   | 0.026      | -            | -                | -                | -         |     0.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     7530 | 2024-09-06 | BC.Game Esports     | L   | 0.025      | -            | -                | -                | -         |    -0.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     7606 | 2024-09-05 | Team Spirit Academy | L   | 0.019      | -            | -                | -                | -         |    -0.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     7726 | 2024-09-03 | Team Space          | W   | 0.006      | -            | -                | -                | -         |     0.05 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,102.27)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.319 | $500.00        | $159.44         |
| 2024-10-03 |      0.206 | $2,500.00      | $513.77         |
| 2024-09-15 |      0.086 | $5,000.00      | $429.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
