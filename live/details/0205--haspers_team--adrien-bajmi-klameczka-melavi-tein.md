### Roster Details<br />
Team Name: Haspers Team<br />
Roster: AdrieN, bajmi, Klameczka, Melavi, tein<br />
Global Rank: [205](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [147]( ../standings_europe.md)<br />
<br />
Final Rank Value:  709.5<br />
<br />
Final Rank Value (709.5) = Starting Rank Value (709.7) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.7
- 400 + ( ( 0.155 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 709.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     2903 | 2024-11-23 | K27                | W   | 0.537      | 0.372        | 0.008 (0.002)    | 0.769 (0.154)    | 0 (0.000) |    12.29 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           22 |     2907 | 2024-11-23 | Nexus Gaming       | L   | 0.537      | -            | -                | -                | -         |    -1.43 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           21 |     2915 | 2024-11-23 | 1win               | L   | 0.537      | -            | -                | -                | -         |    -7.18 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           20 |     2985 | 2024-11-22 | Endpoint           | W   | 0.531      | 0.372        | 0.009 (0.002)    | 0.377 (0.075)    | 0 (0.000) |     9.54 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           19 |     3056 | 2024-11-21 | Lilmix             | W   | 0.524      | 0.372        | 0.001 (0.000)    | 0.127 (0.025)    | 0 (0.000) |     6.24 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           18 |     3095 | 2024-11-20 | FAVBET Team        | L   | 0.519      | -            | -                | -                | -         |    -4.45 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           17 |     3120 | 2024-11-20 | GenOne             | L   | 0.518      | -            | -                | -                | -         |    -5.01 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           16 |     3133 | 2024-11-20 | Illuminar Gaming   | L   | 0.518      | -            | -                | -                | -         |    -5.71 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           15 |     3163 | 2024-11-19 | Permitta Esports   | L   | 0.512      | -            | -                | -                | -         |    -6.00 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           14 |     3166 | 2024-11-19 | 500                | L   | 0.511      | -            | -                | -                | -         |    -2.29 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           13 |     3169 | 2024-11-19 | Fire Flux Esports  | L   | 0.511      | -            | -                | -                | -         |    -3.84 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           12 |     3194 | 2024-11-18 | Nuclear TigeRES    | L   | 0.505      | -            | -                | -                | -         |    -6.07 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           11 |     3437 | 2024-11-14 | Ex-9INE Academy    | W   | 0.479      | 0.372        | 0.000 (0.000)    | 0.033 (0.006)    | 0 (0.000) |     4.29 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           10 |     3472 | 2024-11-14 | HyperSpirit        | W   | 0.477      | 0.372        | 0.004 (0.001)    | 0.119 (0.021)    | 0 (0.000) |     6.33 | AdrieN, bajmi, Klameczka, Melavi, tein |
|            9 |     4012 | 2024-11-04 | Dark Cloud Esports | L   | 0.412      | -            | -                | -                | -         |    -4.44 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            8 |     4414 | 2024-10-28 | GOSTIVAR           | W   | 0.366      | 0.143        | 0.000 (0.000)    | 0.030 (0.002)    | 0 (0.000) |     2.73 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            7 |     4753 | 2024-10-21 | Los kogutos        | W   | 0.318      | 0.143        | 0.032 (0.001)    | 0.515 (0.023)    | 0 (0.000) |     8.16 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            6 |     5420 | 2024-10-08 | GOSTIVAR           | L   | 0.232      | -            | -                | -                | -         |    -5.57 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            5 |     6129 | 2024-09-27 | Dark Cloud Esports | W   | 0.158      | 0.143        | 0.039 (0.001)    | 0.819 (0.019)    | 0 (0.000) |     3.29 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            4 |     6381 | 2024-09-24 | Sampi NEXT         | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     1.04 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            3 |     6392 | 2024-09-24 | UNiTY esports      | L   | 0.138      | -            | -                | -                | -         |    -1.39 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            2 |     6460 | 2024-09-23 | Illuminar Gaming   | L   | 0.132      | -            | -                | -                | -         |    -1.25 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            1 |     6569 | 2024-09-21 | Mollitiem          | W   | 0.119      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.56 | AdrieN, bajmi, hfah, Klameczka, Markoś |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,396.40)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-16 |      0.491 | $8,962.94      | $4,396.40       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
