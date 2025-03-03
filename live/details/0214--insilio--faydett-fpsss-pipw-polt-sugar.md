### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [214](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [153]( ../standings_europe.md)<br />
<br />
Final Rank Value:  703.6<br />
<br />
Final Rank Value (703.6) = Starting Rank Value (685.7) + Head To Head Adjustments (17.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.7
- 400 + ( ( 0.143 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 685.7


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
|           23 |     1849 | 2024-12-12 | Fire Flux Esports   | L   | 0.664      | -            | -                | -                | -         |    -4.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     1890 | 2024-12-11 | CYBERSHOKE Esports  | L   | 0.658      | -            | -                | -                | -         |    -6.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     1933 | 2024-12-10 | FLuffy Gangsters    | W   | 0.652      | 0.143        | 0.014 (0.001)    | 0.909 (0.085)    | 0 (0.000) |    13.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     5804 | 2024-10-02 | Partizan Esports    | L   | 0.190      | -            | -                | -                | -         |    -0.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     5933 | 2024-09-30 | Team Space          | W   | 0.177      | 0.384        | -                | 0.021 (0.001)    | 0 (0.000) |     1.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     5991 | 2024-09-29 | 500                 | W   | 0.169      | 0.143        | 0.093 (0.002)    | 1.000 (0.024)    | 0 (0.000) |     4.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     6244 | 2024-09-26 | B8                  | L   | 0.149      | -            | -                | -                | -         |    -0.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     6533 | 2024-09-22 | Lynn Vision Gaming  | W   | 0.124      | 0.435        | 0.017 (0.001)    | 0.365 (0.020)    | 0 (0.000) |     2.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     6652 | 2024-09-20 | Rebels Gaming       | L   | 0.110      | -            | -                | -                | -         |    -1.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     6664 | 2024-09-20 | Los kogutos         | W   | 0.109      | 0.435        | 0.032 (0.002)    | 0.515 (0.024)    | 0 (0.000) |     2.93 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     6769 | 2024-09-18 | Endpoint            | L   | 0.098      | -            | -                | -                | -         |    -1.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     6917 | 2024-09-16 | The Suspect         | W   | 0.082      | 0.435        | 0.003 (0.000)    | 0.216 (0.008)    | 0 (0.000) |     1.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     6951 | 2024-09-15 | SINNERS Esports     | L   | 0.077      | -            | -                | -                | -         |    -0.54 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     7000 | 2024-09-14 | BC.Game Esports     | W   | 0.071      | 0.435        | 0.078 (0.002)    | 0.945 (0.029)    | 0 (0.000) |     1.97 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     7047 | 2024-09-14 | CYBERSHOKE Esports  | W   | 0.070      | 0.384        | 0.011 (0.000)    | 1.000 (0.027)    | 0 (0.000) |     1.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     7160 | 2024-09-12 | SAW                 | W   | 0.056      | 0.435        | 0.266 (0.007)    | 0.326 (0.008)    | 0 (0.000) |     1.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     7259 | 2024-09-10 | Revenant Esports    | W   | 0.044      | -            | -                | -                | 0 (0.000) |     0.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     7360 | 2024-09-08 | Rhyno Esports       | W   | 0.031      | 0.435        | 0.002 (0.000)    | -                | -         |     0.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     7376 | 2024-09-08 | SINNERS Esports     | W   | 0.029      | 0.384        | 0.027 (0.000)    | 0.446 (0.005)    | -         |     0.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     7495 | 2024-09-07 | Monte               | L   | 0.022      | -            | -                | -                | -         |    -0.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     7524 | 2024-09-06 | Team Space          | W   | 0.018      | -            | -                | -                | -         |     0.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     7542 | 2024-09-06 | BC.Game Esports     | L   | 0.016      | -            | -                | -                | -         |    -0.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     7618 | 2024-09-05 | Team Spirit Academy | L   | 0.010      | -            | -                | -                | -         |    -0.07 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,036.71)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.311 | $500.00        | $155.35         |
| 2024-10-03 |      0.197 | $2,500.00      | $493.29         |
| 2024-09-15 |      0.078 | $5,000.00      | $388.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
