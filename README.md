# PDUslim
Commissioning and test


## PDM specs
(from Pisa)
| PDU position   | TILE name    | Trasmitter ch.| DAQ ch. | Technology |  photocurrent (μA) | PISA note (nt = not tested, ot = only-tile test) | DEAD |
| :------------: | :----------: | :----------:  |:-------:| :-------: | :----------: | -------: | :----: |
| 0 | T128 | 1 | 11 | run3 | -20 | ||
| 1 | T119 | 1 | 11 | run3 | -50 | ||
| 2 | T140 | 2 | 10 | AlSi | -50 | ||
| 3 | T144 | 2 | 10 | AlSi | -44 | nt ||
| 4 | T166 | 3 | 9 | AlCu | -21 | ot |y|
| 5 | T139 | 4 | 8 | AlSi | -50 | ot |y|
| 6 |  T157 | 4 | 8 | AlSi | -48 | ot ||
| 7 |  T118 | 5 | 15 | run3 | -50 | ||
| 8 |  T121 | 5 | 15 | run3 | -49 | ||
| 9 |  T159 | 3 | 9 | AlCu |-38 | ot ||
| 10 |  T168 | 6 | 14 | AlSi | -20 | ot ||
| 11 | T141 | 6 | 14 | AlSi | -20 | ot ||
| 12 | T146 | 7 | 13 | AlSi | -49 | |y|
| 13 | T170 | 7 | 13 | AlCu | -20 | ||
| 14 | T114 | 8 | 12 | run3 | -49 | nt ||
| 15 | T127 | 9 | 19 | run3 | -20 | ||
| 16 | T124 | 9 | 19 | run3 | -50 | ||
| 17 | T164 | 10 | 18 | AlCu | -49 | |y|
| 18 | T149 | 10 | 18 | AlCu | -20 | ||
| 19 | T112 | 8 | 12 | run3 | -40 | nt, scratches ||
| 20 | T116 | 11 | 17 | run3 | -49 | nt ||
| 21 | T103 | 11 | 17 | run3 | -20 | nt ||
| 22 | T102 | 12 | 16 | run3 | -49 | nt, feb: bent pin recovered |y|
| 23 | T131 | 12 | 16 | run3 | -20 | nt, feb: anomalous current ||
| 24 | T120 | NC | NC | run3 | -49 | nt, in a bad shape ||


## PDM map
| 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|
| 5 | 6 | 7 | 8 | 9 |
| 10 | 11 | 12 | 13 | 14 |
| 15 | 16 | 17 | 18 | 19 |
| 20 | 21 | 22 | 23 | 24 |
## Transmitter CH map
| 1 | 1 | 2 | 2 | 3 |
|---|---|---|---|---|
| 4| 4 | 5 | 5 | 3 |
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

![WhatsApp Image 2021-12-01 at 12 11 49](https://user-images.githubusercontent.com/75016958/145374145-6a3b67e8-bb21-4328-94a0-120a962d3347.jpeg)




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
## Warm IVs 11/11/2021 CEST Naples (DEPRECATED)
### IVs
![IV_tot_f](https://user-images.githubusercontent.com/75016958/142066592-ef2d97b7-2da4-4fd5-bd7c-880adddacea6.png)
PDM6 arrived dead (broken wire bonding) and PDM18 showed extra current (not good devices anyway) and are switched off.
 
 ### 75V current-channel distribution
 
![75V_clean](https://user-images.githubusercontent.com/75016958/142195353-16a2addb-9ea2-4c2a-b891-231829dff24e.png)


### 75V hist current distribution + fit
![75V_fit](https://user-images.githubusercontent.com/75016958/142198595-9931e6f6-344f-4140-92be-074ed490c8da.png)

## Cold IVs 19/11/2021 Naples
### IVs
![IV_cold](https://user-images.githubusercontent.com/75016958/142669048-33d58dbc-8304-46be-ae72-e36a4fc70999.png)
### Single IV

||||
|:--:|:--:|:--:|
|![PDM0](https://user-images.githubusercontent.com/75016958/142742247-cc8a2b89-13d9-4a60-8241-958f789bb455.png)|![PDM1](https://user-images.githubusercontent.com/75016958/142742249-8f68f101-7511-4b72-9884-e6506adba173.png)|![PDM2](https://user-images.githubusercontent.com/75016958/142742255-f8130bc6-6604-493d-b992-22169329c226.png)|
|![PDM3](https://user-images.githubusercontent.com/75016958/142742277-63f8011f-49f3-4c21-8da1-e7def1236561.png)|![PDM6](https://user-images.githubusercontent.com/75016958/142742280-3c95cf8d-f726-4aec-b52a-ea1ff6a5c1a7.png)|![PDM7](https://user-images.githubusercontent.com/75016958/142742284-5ef54602-d986-4b72-a9b9-472dbb064008.png)|
|![PDM8](https://user-images.githubusercontent.com/75016958/142742287-bd2eab00-1f93-4f53-bf54-772a92090f91.png)|![PDM9](https://user-images.githubusercontent.com/75016958/142742292-d0a927ae-dd6f-426e-9a79-4483a5c95694.png)|![PDM10](https://user-images.githubusercontent.com/75016958/142742295-d435268b-4aef-4595-b215-6ca2bce1d4b2.png)|
|![PDM11](https://user-images.githubusercontent.com/75016958/142742297-a32985e9-e8a0-4241-8c21-97d6ffa2b6fd.png)|![PDM13](https://user-images.githubusercontent.com/75016958/142742305-c69b168c-1ed2-4980-bf0c-4546713f499c.png)|![PDM14](https://user-images.githubusercontent.com/75016958/142742310-eb05279c-6a66-4436-9ead-39ad08045673.png)|
|![PDM15](https://user-images.githubusercontent.com/75016958/142742316-cbe2c836-7bd7-4aaa-9f9d-7b15afbe004e.png)|![PDM16](https://user-images.githubusercontent.com/75016958/142742318-332c6ae4-8d66-4feb-8143-b8f9f6c4f177.png)|![PDM18](https://user-images.githubusercontent.com/75016958/142742320-166e3c45-9e58-425e-9cc1-bf4afb5b0f9d.png)|
|![PDM19](https://user-images.githubusercontent.com/75016958/142742324-c436abf5-6b4f-4b4d-9b3d-80c736cf6a9f.png)|![PDM20](https://user-images.githubusercontent.com/75016958/142742326-34f62f55-bb3a-45a6-a5b7-f8b97d3dc182.png)|![PDM21](https://user-images.githubusercontent.com/75016958/142742331-2d92e358-97c9-4b3f-9134-40d19d89bf5e.png)|
|![PDM23](https://user-images.githubusercontent.com/75016958/142742333-fc37cc3f-b4b2-4840-adf9-0d9a0e273f94.png)||

# LASER RUN 22/11/2021

| RUN TYPE             | all channel scan                                             | 22/11/2021 |      |          |
| -------------------- | ------------------------------------------------------------ | ---------- | ---- | -------- |
|                      |                                                              |            |      |          |  |
|                      |                                                              |            |      |          |  |
| V\_set (V)           | Current (uA)                                                 | V\_real (V)| RUN# | VoV (V)  | ev. number |
| 74.3                 | 126                                                          | 73.04      | 765  | 9.02     | 100k |
| 70.2                 | 118.7                                                        | 69.013     | 766  | 7.0065   | 113k |
| 66.2                 | 111.7                                                        | 65.083     | 767  | 5.0415   | 115k |
| 63.1                 | 106.3                                                        | 62.037     | 768  | 3.5185   | 113k |
| 50.85                | 85.18                                                        | 49.9982    | 769  | \-2.5009 | 113k |
|                      |                                                              |            |      |          |  |
|                      | even channels (1,3,4,5,7,9,11,12,13,15,17,19,21,22,23,24)OFF |            |      |          |  |
| V\_set (V)           | Current (uA)                                                 | V\_real (V)| RUN# | VoV (V)  | ev. number |
| 73.55                | 55.67                                                        | 72.9933    | 774  | 8.99665  | 111k |
| 69.55                | 52.6                                                         | 69.024     | 773  | 7.012    | 102k |
| 65.5                 | 49.5                                                         | 65.005     | 772  | 5.0025   | 111k |
| 62.5                 | 47.2                                                         | 62.028     | 771  | 3.514    | 112k |
| 50.4                 | 37.9                                                         | 50.021     | 770  | \-2.4895 | 112k |
|                      |                                                              |            |      |          |  |
|                      |                                                              |            |      |          |  |
|                      | ODD channels (0,2,4,6,8,10,12,14,16,17,18,20,22,24)OFF       |            |      |          |  |
| V\_set (V)           | Current (uA)                                                 | V\_real (V)| RUN# | VoV (V)  | ev. number |
| 73.75                | 70.6                                                         | 73.044     | 780  | 9.022    | 113k |
| 69.7                 | 66.38                                                        | 69.0362    | 779  | 7.0181   | 112k |
| 65.65                | 62.36                                                        | 65.0264    | 778  | 5.0132   | 112k |
| 62.6                 | 59.3                                                         | 62.007     | 776  | 3.5035   | 112k |
| 50.5                 | 47.4                                                         | 50.026     | 775  | \-2.487  | 112k |
| note: 777 broken run |                                                              |            |      |
|continue...|||


# Analysis
Four best channels (both tiles turned on and pretty homogeneous) are chosen for the analysis:
* ch11
* ch14
* ch15
* ch19

## Cold IVs

![IV_cold_belle](https://user-images.githubusercontent.com/75016958/143454421-26465230-70f2-48ec-8293-dda4571e80d6.png)

## Performance
Typical signal:
![immagine](https://user-images.githubusercontent.com/75016958/145374349-eb6b01a0-0a65-41a4-b8f6-e7a58178ce51.png)
The signal from channel 11 with the two tiles in the pair alternatively turned on (red: TILE01 on, TILE00 off; blue: TILE01 off, TILE00 on).
![immagine](https://user-images.githubusercontent.com/75016958/145374426-7f33db1a-737d-4c86-b8ef-048a16c0923d.png)

### SNR
| Channel              | SNR @VoV = 5                                                 | SNR @ VoV = 7V |  SNR @ VoV = 9V    | 
| -------------------- | ------------------------------------------------------------ | ---------- | ---- | 
|11 (charge spectrum)  |       7.4                                                    |    10.2    |  13.8| 
|11 (filtered amplitude spectrum)  |       7.3                                                    |    10.0    |  13.0| 
|14 (charge spectrum)  |       6.9                                                    |    9.2    |  13.0| 
|14 (filtered amplitude spectrum)  |       6.7                                                    |    9.1    |  12.0| 
|15 (charge spectrum)  |       8.2                                                    |    11.1    |  13.6| 
|15 (filtered amplitude spectrum)  |       7.4                                                    |    13.0    |  17.0| 
|19 (charge spectrum)  |       10.2                                                    |    14.1    |  18.6| 
|19 (filtered amplitude spectrum)  |       11                                                    |    14.0    |  19.0| 


### Time resolution
![immagine](https://user-images.githubusercontent.com/75016958/145374592-5d3c48dd-0fe3-4d52-9516-f84e81edb4c1.png)


