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
| 5 | T139 | 4 | 8 | AlSi | -50 | ot ||
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

## Cold IVs 19/11/2021 Naples (deprecated)
### IVs
![IV_cold](https://user-images.githubusercontent.com/75016958/142669048-33d58dbc-8304-46be-ae72-e36a4fc70999.png)

## Cold IVs 19/11/2021 Naples


||||
|:--:|:--:|:--:|
|![PDM0](https://user-images.githubusercontent.com/75016958/142742247-cc8a2b89-13d9-4a60-8241-958f789bb455.png)|![PDM1](https://user-images.githubusercontent.com/75016958/142742249-8f68f101-7511-4b72-9884-e6506adba173.png)|![PDM2](https://user-images.githubusercontent.com/75016958/142742255-f8130bc6-6604-493d-b992-22169329c226.png)
|
|![PDM3](https://user-images.githubusercontent.com/75016958/142742277-63f8011f-49f3-4c21-8da1-e7def1236561.png)|![PDM5](https://user-images.githubusercontent.com/75016958/142742279-753e976a-c382-4fec-b9be-f552b699fff9.png)|![PDM6](https://user-images.githubusercontent.com/75016958/142742280-3c95cf8d-f726-4aec-b52a-ea1ff6a5c1a7.png)
|
|![PDM7](https://user-images.githubusercontent.com/75016958/142742284-5ef54602-d986-4b72-a9b9-472dbb064008.png)|![PDM8](https://user-images.githubusercontent.com/75016958/142742287-bd2eab00-1f93-4f53-bf54-772a92090f91.png)|![PDM9](https://user-images.githubusercontent.com/75016958/142742292-d0a927ae-dd6f-426e-9a79-4483a5c95694.png)
|
|![PDM10](https://user-images.githubusercontent.com/75016958/142742295-d435268b-4aef-4595-b215-6ca2bce1d4b2.png)|![PDM11](https://user-images.githubusercontent.com/75016958/142742297-a32985e9-e8a0-4241-8c21-97d6ffa2b6fd.png)|![PDM13](https://user-images.githubusercontent.com/75016958/142742305-c69b168c-1ed2-4980-bf0c-4546713f499c.png)
|
|![PDM14](https://user-images.githubusercontent.com/75016958/142742310-eb05279c-6a66-4436-9ead-39ad08045673.png)|![PDM15](https://user-images.githubusercontent.com/75016958/142742316-cbe2c836-7bd7-4aaa-9f9d-7b15afbe004e.png)|![PDM16](https://user-images.githubusercontent.com/75016958/142742318-332c6ae4-8d66-4feb-8143-b8f9f6c4f177.png)
|
|![PDM18](https://user-images.githubusercontent.com/75016958/142742320-166e3c45-9e58-425e-9cc1-bf4afb5b0f9d.png)|![PDM19](https://user-images.githubusercontent.com/75016958/142742324-c436abf5-6b4f-4b4d-9b3d-80c736cf6a9f.png)|![PDM20](https://user-images.githubusercontent.com/75016958/142742326-34f62f55-bb3a-45a6-a5b7-f8b97d3dc182.png)
|
|![PDM21](https://user-images.githubusercontent.com/75016958/142742331-2d92e358-97c9-4b3f-9134-40d19d89bf5e.png)|![PDM23](https://user-images.githubusercontent.com/75016958/142742333-fc37cc3f-b4b2-4840-adf9-0d9a0e273f94.png)|
|
