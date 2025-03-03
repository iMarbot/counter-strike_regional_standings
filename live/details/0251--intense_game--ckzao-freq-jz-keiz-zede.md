### Roster Details<br />
Team Name: Intense Game<br />
Roster: ckzao, fREQ, jz, keiz, zede<br />
Global Rank: [251](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [49]( ../standings_americas.md)<br />
<br />
Final Rank Value:  679.0<br />
<br />
Final Rank Value (679.0) = Starting Rank Value (665.2) + Head To Head Adjustments (13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.2
- 400 + ( ( 0.133 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 665.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     3655 | 2024-11-10 | TROPA DO TACO          | L   | 0.452      | -            | -                | -                | -         |    -6.14 | ckzao, fREQ, jz, keiz, zede  |
|           24 |     3831 | 2024-11-07 | TROPA DO TACO          | L   | 0.433      | -            | -                | -                | -         |    -6.04 | ckzao, fREQ, jz, keiz, zede  |
|           23 |     3886 | 2024-11-06 | MIBR Academy           | W   | 0.425      | 0.143        | 0.001 (0.000)    | 0.464 (0.028)    | 0 (0.000) |     6.82 | ckzao, fREQ, jz, keiz, zede  |
|           22 |     3922 | 2024-11-05 | Sharks Esports         | L   | 0.420      | -            | -                | -                | -         |    -1.84 | ckzao, fREQ, jz, keiz, zede  |
|           21 |     3981 | 2024-11-04 | UNO MILLE              | L   | 0.413      | -            | -                | -                | -         |    -5.49 | ckzao, fREQ, jz, keiz, zede  |
|           20 |     4005 | 2024-11-04 | Floripa Stars          | W   | 0.412      | 0.143        | 0.001 (0.000)    | 0.296 (0.017)    | 0 (0.000) |     6.37 | ckzao, fREQ, jz, keiz, zede  |
|           19 |     4038 | 2024-11-03 | Galorys Academy        | W   | 0.407      | 0.143        | 0.001 (0.000)    | 0.154 (0.009)    | 0 (0.000) |     5.55 | ckzao, fREQ, jz, keiz, zede  |
|           18 |     4110 | 2024-11-02 | RED Canids Academy     | L   | 0.400      | -            | -                | -                | -         |    -5.90 | ckzao, fREQ, jz, keiz, zede  |
|           17 |     4115 | 2024-11-02 | ODDIK                  | L   | 0.399      | -            | -                | -                | -         |    -3.89 | ckzao, fREQ, jz, keiz, zede  |
|           16 |     4180 | 2024-11-01 | Team Solid             | L   | 0.393      | -            | -                | -                | -         |    -3.87 | ckzao, fREQ, jz, keiz, zede  |
|           15 |     4183 | 2024-11-01 | Bounty Hunters Esports | W   | 0.393      | 0.143        | 0.005 (0.000)    | 0.523 (0.029)    | 0 (0.000) |     6.57 | ckzao, fREQ, jz, keiz, zede  |
|           14 |     4206 | 2024-11-01 | 20/70                  | W   | 0.392      | 0.333        | 0.001 (0.000)    | 0.286 (0.037)    | 0 (0.000) |     5.48 | ckzao, fREQ, jz, keiz, zede  |
|           13 |     4289 | 2024-10-30 | RED Canids Academy     | W   | 0.380      | 0.333        | 0.005 (0.001)    | 0.236 (0.030)    | 0 (0.000) |     6.45 | ckzao, fREQ, jz, keiz, zede  |
|           12 |     4308 | 2024-10-30 | Fluxo                  | L   | 0.379      | -            | -                | -                | -         |    -2.31 | ckzao, fREQ, jz, keiz, zede  |
|           11 |     4361 | 2024-10-29 | América eSports        | W   | 0.373      | 0.143        | -                | 0.426 (0.023)    | 0 (0.000) |     4.88 | ckzao, fREQ, jz, keiz, zede  |
|           10 |     4403 | 2024-10-28 | AdalYamigos            | W   | 0.367      | 0.143        | 0.004 (0.000)    | 0.193 (0.010)    | 0 (0.000) |     7.34 | ckzao, fREQ, jz, keiz, zede  |
|            9 |     4425 | 2024-10-28 | Myth e-Sports          | L   | 0.365      | -            | -                | -                | -         |    -6.96 | ckzao, fREQ, jz, keiz, zede  |
|            8 |     4652 | 2024-10-23 | UNO MILLE              | W   | 0.333      | 0.333        | 0.010 (0.001)    | 0.522 (0.058)    | 0 (0.000) |     6.08 | ckzao, fREQ, jz, keiz, zede  |
|            7 |     4655 | 2024-10-23 | Bounty Hunters Esports | W   | 0.332      | 0.333        | 0.001 (0.000)    | -                | 0 (0.000) |     5.18 | ckzao, fREQ, jz, keiz, zede  |
|            6 |     4979 | 2024-10-16 | Dusty Roots            | W   | 0.286      | 0.333        | 0.009 (0.001)    | 0.366 (0.035)    | -         |     5.93 | ckzao, fREQ, keiz, mxa, zede |
|            5 |     5754 | 2024-10-02 | 20/70                  | L   | 0.193      | -            | -                | -                | -         |    -3.18 | ckzao, fREQ, keiz, mxa, zede |
|            4 |     5842 | 2024-10-01 | UNO MILLE              | L   | 0.186      | -            | -                | -                | -         |    -2.31 | ckzao, fREQ, keiz, mxa, zede |
|            3 |     6260 | 2024-09-25 | RED Canids Academy     | L   | 0.147      | -            | -                | -                | -         |    -2.14 | ckzao, fREQ, keiz, mxa, zede |
|            2 |     6689 | 2024-09-19 | Bounty Hunters Esports | L   | 0.106      | -            | -                | -                | -         |    -1.77 | ckzao, fREQ, keiz, mxa, zede |
|            1 |     6749 | 2024-09-18 | Dusty Roots            | L   | 0.099      | -            | -                | -                | -         |    -1.04 | ckzao, fREQ, keiz, mxa, zede |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($840.86)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.421 | $1,035.89      | $435.72         |
| 2024-11-03 |      0.405 | $1,000.00      | $405.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
