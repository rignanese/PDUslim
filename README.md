# PDUslim
Commissioning and test


## PDM specs
(from Pisa)
| PDU position   | TILE name    | Technology |  photocurrent (μA) | note (nt = not tested, ot = only-tile test) |
| :------------: | :----------: | :-------: | :----------: | -------: |
| 0 | T128 | run3 | -20 | |
| 1 | T119 | run3 | -50 | |
| 2 | T140 | AlSi | -50 | |
| 3 | T144 | AlSi | -44 | nt |
| 4 | T166 | AlCu | -21 | ot |
| 5 | T139 | AlSi | -50 | ot |
| 6 |  T157 | AlSi | -48 | ot |
| 7 |  T118 | run3 | -50 | |
| 8 |  T121 | run3 | -49 | |
| 9 |  T159 | AlCu |-38 | ot |
| 10 |  T168 | AlSi | -20 | ot |
| 11 | T141 | AlSi | -20 | ot |
| 12 | T146 | AlSi | -49 | |
| 13 | T170 | AlCu | -20 | |
| 14 | T114 | run3 | -49 | nt |
| 15 | T127 | run3 | -20 | |
| 16 | T124 | run3 | -50 | |
| 17 | T164 | AlCu | -49 | |
| 18 | T149 | AlCu | -20 | |
| 19 | T112 | run3 | -40 | nt, scratches |
| 20 | T116 | run3 | -49 | nt |
| 21 | T103 | run3 | -20 | nt |
| 22 | T102 | run3 | -49 | nt, feb: bent pin recovered |
| 23 | T131 | run3 | -20 | nt, feb: anomalous current |
| 24 | T120 | run3 | -49 | nt, in a bad shape |


## PDM map
| 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|
| 5 | 6 | 7 | 8 | 9 |
| 10 | 11 | 12 | 13 | 14 |
| 15 | 16 | 17 | 18 | 19 |
| 20 | 21 | 22 | 23 | 24 |
## Transmitter CH map
| 1 | 1 | 2 | 2 | 5 |
|---|---|---|---|---|
| 3| 3 | 4 | 4 | 5 |
| 6 | 6 | 7 | 7 | 8 |
| 9 | 9 | 10 | 10 | 8 |
| 11 | 11 | 12 | 12 | == |
## DAQ CH map
| 11 | 11 | 10 | 10 | 9|
|---|---|---|---|---|
| 8 | 8 | 15 | 15 | 9 |
| 14 | 14 | 13 | 13 | 12 |
| 19 | 19 | 18 | 18 | 12 |
| 17 | 17 | 16 | 16 | == |



## Channels' specs.
(from Pisa)

| Channel number | Technology | comment |
| :------------: | :----------: | ------- |
| 1 | run3 | double peaks expected |
| 2 | AlSi | 140 ok, 144 not tested. probable wire bonding boken on both |
| 3 | AlCu | double peaks expected |
| 4 | AlSi | likely good |
| 5 | run3 | ok |
| 6 | AlSi | double peaks expected |
| 7 | AlSi + AlCu | ok
| 8 | run3 | not tested |
| 9 | run3 | double peaks expected |
| 10 | AlCu | T149 good, probable double peaks the other |
| 11 | run3 | not tested |
| 12 | run3 | not tested. Problematic FEBs |


# IVs
## Warm IVs 11/11/2021 19:07-19:39 CEST Naples
### IVs
![IV_tot_f](https://user-images.githubusercontent.com/75016958/142066592-ef2d97b7-2da4-4fd5-bd7c-880adddacea6.png)
PDM6 arrived dead (broken wire bonding) and PDM18 showed extra current (not good devices anyway) and are switched off.
 
 ### 75V current-channel distribution
 
![75V_clean](https://user-images.githubusercontent.com/75016958/142195353-16a2addb-9ea2-4c2a-b891-231829dff24e.png)


### 75V hist current distribution + fit
![75V_fit](https://user-images.githubusercontent.com/75016958/142198595-9931e6f6-344f-4140-92be-074ed490c8da.png)



