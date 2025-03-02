### Roster Details<br />
Team Name: PCIFIC Espor<br />
Roster: EMSTAR, eNs, jresy, lugseN, scolleN<br />
Global Rank: [178](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [129]( ../standings_europe.md)<br />
<br />
Final Rank Value:  726.7<br />
<br />
Final Rank Value (726.7) = Starting Rank Value (774.2) + Head To Head Adjustments (-47.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.298[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.113[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.2
- 400 + ( ( 0.187 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 774.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      338 | 2025-02-16 | Hesta                       | L   | 1.000      | -            | -                | -                | -         |   -12.76 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           28 |     1359 | 2024-12-24 | Des1ngnadted                | W   | 0.753      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     5.53 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           27 |     1979 | 2024-12-08 | VOLT (European team)        | L   | 0.647      | -            | -                | -                | -         |   -11.25 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           26 |     1983 | 2024-12-08 | LEON Esports                | W   | 0.647      | 0.143        | 0.010 (0.001)    | 0.275 (0.025)    | 0 (0.000) |    11.31 | EMSTAR, eNs, jresy, lugseN, scolleN  |
|           25 |     2869 | 2024-11-23 | DUSTY                       | L   | 0.546      | -            | -                | -                | -         |   -10.36 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           24 |     2878 | 2024-11-23 | Endpoint                    | L   | 0.546      | -            | -                | -                | -         |    -8.98 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           23 |     2893 | 2024-11-23 | Kubix Esports               | W   | 0.545      | 0.372        | 0.045 (0.009)    | 0.496 (0.101)    | 0 (0.000) |    12.96 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           22 |     2953 | 2024-11-22 | Impulse GW                  | L   | 0.540      | -            | -                | -                | -         |    -9.01 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           21 |     2975 | 2024-11-22 | ALTERNATE aTTaX             | L   | 0.539      | -            | -                | -                | -         |    -4.67 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           20 |     3008 | 2024-11-21 | Soul's Heart Esport         | L   | 0.534      | -            | -                | -                | -         |   -12.57 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           19 |     3022 | 2024-11-21 | GODSENT                     | W   | 0.533      | 0.372        | 0.001 (0.000)    | 0.275 (0.055)    | 0 (0.000) |     6.77 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           18 |     3397 | 2024-11-15 | Team Norway                 | L   | 0.492      | -            | -                | -                | -         |   -10.68 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           17 |     3410 | 2024-11-15 | Los kogutos                 | L   | 0.491      | -            | -                | -                | -         |    -5.22 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           16 |     3420 | 2024-11-14 | Mindfreak (Australian team) | W   | 0.487      | 0.617        | 0.002 (0.001)    | 0.093 (0.028)    | 1 (0.487) |     6.40 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           15 |     3504 | 2024-11-13 | Metizport                   | W   | 0.479      | 0.617        | 0.074 (0.022)    | 0.513 (0.152)    | 1 (0.479) |    13.02 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           14 |     3509 | 2024-11-13 | Homyno                      | L   | 0.479      | -            | -                | -                | -         |    -8.71 | EMSTAR, h0kz, imoRR, lugseN, scolleN |
|           13 |     3793 | 2024-11-08 | Betera Esports              | L   | 0.446      | -            | -                | -                | -         |    -7.73 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           12 |     3871 | 2024-11-06 | Los kogutos                 | L   | 0.434      | -            | -                | -                | -         |    -4.59 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           11 |     3982 | 2024-11-04 | Lazer Cats                  | W   | 0.420      | 0.372        | 0.005 (0.001)    | 0.387 (0.061)    | 0 (0.000) |     5.93 | Cizzx, eNs, jresy, lugseN, scolleN   |
|           10 |     4291 | 2024-10-30 | The Suspect                 | W   | 0.387      | 0.372        | 0.003 (0.000)    | 0.220 (0.032)    | 0 (0.000) |     5.27 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            9 |     4434 | 2024-10-28 | Permitta Esports            | L   | 0.373      | -            | -                | -                | -         |    -5.53 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            8 |     4662 | 2024-10-23 | THE SPELLS                  | W   | 0.339      | 0.372        | 0.000 (0.000)    | 0.147 (0.019)    | 0 (0.000) |     2.47 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            7 |     4726 | 2024-10-21 | ROUNDS                      | W   | 0.326      | -            | -                | -                | 0 (0.000) |     2.13 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            6 |     4981 | 2024-10-16 | GenOne                      | L   | 0.293      | -            | -                | -                | -         |    -3.84 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            5 |     5096 | 2024-10-14 | XP Academy                  | W   | 0.280      | 0.372        | -                | 0.204 (0.021)    | -         |     2.09 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            4 |     5333 | 2024-10-09 | Lilmix                      | W   | 0.246      | 0.372        | 0.001 (0.000)    | 0.130 (0.012)    | -         |     2.64 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            3 |     5464 | 2024-10-07 | Illuminar Gaming            | L   | 0.233      | -            | -                | -                | -         |    -2.66 | Cizzx, eNs, jresy, lugseN, scolleN   |
|            2 |     6310 | 2024-09-25 | ROYALS                      | L   | 0.151      | -            | -                | -                | -         |    -2.95 | Cizzx, Ckanic, eNs, jresy, lugseN    |
|            1 |     6474 | 2024-09-23 | Lazer Cats                  | L   | 0.139      | -            | -                | -                | -         |    -2.51 | Cizzx, Ckanic, eNs, jresy, lugseN    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,468.53)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-27 |      0.772 | $709.45        | $548.05         |
| 2024-11-24 |      0.552 | $1,250.00      | $690.63         |
| 2024-11-10 |      0.460 | $500.00        | $229.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
