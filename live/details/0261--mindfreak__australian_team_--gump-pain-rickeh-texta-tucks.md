### Roster Details<br />
Team Name: Mindfreak (Australian team)<br />
Roster: gump, pain, Rickeh, Texta, tucks<br />
Global Rank: [261](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [34]( ../standings_asia.md)<br />
<br />
Final Rank Value:  674.2<br />
<br />
Final Rank Value (674.2) = Starting Rank Value (705.9) + Head To Head Adjustments (-31.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.268[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.9
- 400 + ( ( 0.153 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 705.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      658 | 2025-02-08 | Chinggis Warriors                | L   | 1.000      | -            | -                | -                | -         |    -8.64 | gump, pain, Rickeh, Texta, tucks      |
|           24 |      739 | 2025-02-07 | Believe.                         | L   | 1.000      | -            | -                | -                | -         |   -21.74 | gump, pain, Rickeh, Texta, tucks      |
|           23 |     2926 | 2024-11-22 | Justice For Tomorrow             | L   | 0.535      | -            | -                | -                | -         |   -10.21 | gump, Omichella, Rickeh, Texta, tucks |
|           22 |     2930 | 2024-11-22 | Housebets                        | W   | 0.535      | 0.264        | 0.001 (0.000)    | 0.122 (0.017)    | 0 (0.000) |     6.42 | gump, Omichella, Rickeh, Texta, tucks |
|           21 |     3408 | 2024-11-15 | Los kogutos                      | L   | 0.484      | -            | -                | -                | -         |    -3.95 | gump, pain, Rickeh, Texta, tucks      |
|           20 |     3420 | 2024-11-15 | Homyno                           | W   | 0.483      | 0.617        | 0.008 (0.002)    | 0.189 (0.056)    | 1 (0.483) |     7.43 | gump, pain, Rickeh, Texta, tucks      |
|           19 |     3432 | 2024-11-14 | PCIFIC Espor                     | L   | 0.479      | -            | -                | -                | -         |    -6.29 | gump, pain, Rickeh, Texta, tucks      |
|           18 |     3518 | 2024-11-13 | Team Norway                      | L   | 0.471      | -            | -                | -                | -         |    -9.68 | gump, pain, Rickeh, Texta, tucks      |
|           17 |     3522 | 2024-11-13 | Metizport                        | L   | 0.470      | -            | -                | -                | -         |    -1.70 | gump, pain, Rickeh, Texta, tucks      |
|           16 |     4835 | 2024-10-19 | FlyQuest                         | L   | 0.308      | -            | -                | -                | -         |    -1.01 | gump, pain, Rickeh, Texta, tucks      |
|           15 |     4875 | 2024-10-19 | Housebets                        | W   | 0.302      | 0.333        | 0.001 (0.000)    | 0.122 (0.012)    | 0 (0.000) |     3.55 | gump, pain, Rickeh, Texta, tucks      |
|           14 |     4919 | 2024-10-18 | FlyQuest                         | L   | 0.295      | -            | -                | -                | -         |    -0.96 | gump, pain, Rickeh, Texta, tucks      |
|           13 |     4970 | 2024-10-17 | Only One Word                    | W   | 0.289      | 0.333        | 0.001 (0.000)    | 0.190 (0.018)    | 0 (0.000) |     3.64 | gump, pain, Rickeh, Texta, tucks      |
|           12 |     5375 | 2024-10-09 | FlyQuest                         | W   | 0.236      | 0.333        | 0.105 (0.008)    | 0.235 (0.018)    | 0 (0.000) |     6.72 | gump, pain, Rickeh, Texta, tucks      |
|           11 |     5378 | 2024-10-09 | FlyQuest                         | W   | 0.236      | 0.333        | 0.105 (0.008)    | 0.235 (0.018)    | 0 (0.000) |     6.76 | gump, pain, Rickeh, Texta, tucks      |
|           10 |     5562 | 2024-10-05 | Only One Word                    | L   | 0.214      | -            | -                | -                | -         |    -4.00 | gump, pain, Rickeh, Texta, tucks      |
|            9 |     5645 | 2024-10-04 | SemperFi Esports                 | L   | 0.208      | -            | -                | -                | -         |    -4.63 | gump, pain, Rickeh, Texta, tucks      |
|            8 |     5647 | 2024-10-04 | Housebets                        | W   | 0.208      | -            | -                | -                | 0 (0.000) |     2.50 | gump, pain, Rickeh, Texta, tucks      |
|            7 |     5653 | 2024-10-04 | Above The Rest (Australian team) | W   | 0.207      | -            | -                | -                | 0 (0.000) |     0.98 | gump, pain, Rickeh, Texta, tucks      |
|            6 |     5809 | 2024-10-02 | KZG                              | W   | 0.189      | 0.333        | 0.001 (0.000)    | 0.164 (0.010)    | 0 (0.000) |     2.29 | gump, pain, Rickeh, Texta, tucks      |
|            5 |     5811 | 2024-10-02 | KZG                              | W   | 0.189      | 0.333        | 0.001 (0.000)    | 0.164 (0.010)    | 0 (0.000) |     2.32 | gump, pain, Rickeh, Texta, tucks      |
|            4 |     6331 | 2024-09-25 | Only One Word                    | W   | 0.143      | 0.333        | 0.001 (0.000)    | 0.190 (0.009)    | -         |     1.84 | gump, pain, Rickeh, Texta, tucks      |
|            3 |     6337 | 2024-09-25 | Only One Word                    | L   | 0.142      | -            | -                | -                | -         |    -2.68 | gump, pain, Rickeh, Texta, tucks      |
|            2 |     6788 | 2024-09-18 | Housebets                        | W   | 0.096      | 0.333        | 0.001 (0.000)    | 0.122 (0.004)    | -         |     1.19 | gump, pain, Rickeh, Texta, tucks      |
|            1 |     6789 | 2024-09-18 | Housebets                        | L   | 0.096      | -            | -                | -                | -         |    -1.84 | gump, pain, Rickeh, Texta, tucks      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($616.39)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.308 | $2,000.00      | $616.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
