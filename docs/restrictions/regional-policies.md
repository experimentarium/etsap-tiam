## Regional Policies

Some countries set their own goals towards climate change. These policy goals include phase-out of conventional power plants, restrictions on nuclear technology installation, CO2-taxes and carbon neutrality.  Therefore, additional constraints are modelled in TIAM to include the policies of specific regions as well. 
### Implementazion

#### Carbon neutrality goal

An example is explained for the TIAM region-Germany. The German Climate Action Plan for 2050 describes the CO2 reduction targets for 2030, 2040 and 2045 for all demand sectors along with a goal of achieving carbon neutrality in industry, transport and building sectors by 2045 [1]. These emission reduction targets are modelled in TIAM with the appropriate TIMES attributes and linearly interpolated between the years. Table 1 below shows the constraint placed on the emissions from different sectors for Germany. 

Table 1: CO2 emissions per sector in Germany modelled in TIAM.
| Sector      | Emissions (kt) |        |        |      |
|-------------|----------------|--------|--------|------|
|             | 2030           | 2040   | 2045   | 2100 |
| Industry    | 143231         | 102348 | 0      | 0    |
| Transport   | 98158          | 60780  | 0      | 0    |
| Building    | 72116          | 44655  | 0      | 0    |
| Upstream    | 183308         | 113504 | 4543.4 | 0    |
| Agriculture | 61099          | 50655  | 40089  | 0    |

#### Technology restrictions

All the countries, except Germany, have defined policies on maximum nuclear power plant installations for the future. In the case of Germany, nuclear phase-out plan is already put in action since 2023 [2] and hence, the current and future capacity of nuclear plants are zero. Accordingly, In TIAM, constraints are defined for maximum nuclear capacity for every region. 

Table 2: Maximum nuclear technology capacity (GW) constraint for every region until 2100 in TIAM model.
| Region  | 2030 | 2050 | 2080 | 2100 |
|---------|------|------|------|------|
| AFR     | 17   | 37   | 75   | 99   |
| AUS     | 5    | 9    | 21   | 28   |
| CAN     | 27   | 41   | 69   | 96   |
| CHI     | 168  | 331  | 667  | 789  |
| CSA     | 11   | 54   | 122  | 161  |
| EEU     | 82   | 104  | 143  | 162  |
| FSU     | 68   | 101  | 132  | 161  |
| GER     | 0    | 0    | 0    | 0    |
| IND     | 48   | 97   | 168  | 274  |
| JPN     | 16   | 24   | 91   | 148  |
| MEA     | 6    | 27   | 57   | 75   |
| MEX     | 5    | 9    | 19   | 27   |
| ODA     | 19   | 30   | 59   | 77   |
| SKO     | 34   | 39   | 69   | 89   |
| USA     | 142  | 155  | 220  | 274  |
| WEU     | 62   | 32   | 35   | 42   |

Based on the regional policies, minimum electricity consumption from coal power plants is also defined for every region except Germany until 2030. Similar to the case of nuclear phase-out, Germany has also announced coal phase-out by 2038 [3]. Therefore, for Germany, the activities of all the coal processes are set to zero and for other regions, the region-specific policy restrictions on coal electricity consumption are entered as shown in Table 3. 

Table 3: Minimum electricity production from coal power plants (PJ) until 2030 in TIAM model. 
| Region  | 2020  | 2030  |
|---------|-------|-------|
| AFR     | 1018  | 1102  |
| AUS     | 539   | 479   |
| CAN     | 0.08  | 0.02  |
| CHI     | 14050 | 15517 |
| CSA     | 272   | 269   |
| EEU     | 717   | 339   |
| FSU     | 996   | 957   |
| GER     | -     | -     |
| IND     | 3864  | 5364  |
| JPN     | 1182  | 1078  |
| MEA     | 382   | 521   |
| MEX     | 78    | 17    |
| ODA     | 2262  | 3521  |
| SKO     | 804   | 733   |
| USA     | 4897  | 4345  |
| WEU     | 904   | 427   |


### Reference

[1] 	„Climate Action Plan 2050: Principles and goals of the German government's climate policy,“ Federal ministry for the environment, nature conservation, building and nuclear safety, 2016.

[2] 	„Germany brings era of nuclear power to an end,“ 2023. [Online]. Available: https://www.bmuv.de/en/pressrelease/germany-brings-era-of-nuclear-power-to-an-end.

[3] 	„Coal phase-out under KVBG Act,“ Oktober 2021. [Online]. Available: https://www.smard.de/page/en/topic-article/5892/206022.
