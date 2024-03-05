## Transport

The transport sector is defined on the basis of the energy services demanded, the transport technologies used and the goods transported. A total of 14 energy services and a demand segment to map non-energy uses are defined and mapped in the model (cf. energy service demands). 8 energy services are assigned to road transport and 6 are characterized as "general demand" - international and domestic air transport (TAI, TAD), rail freight and passenger transport (TTF, TTP) and national and international shipping (TWD, TWI). For road transport, the demand for energy services is given in billion vehicle kilometres (Bv-km), for the other sectors in petajoules (PJ), compare Table 1. The projection of demand for energy services up to the year 2100 is carried out using suitable [drivers and elasticities](../regional_coverage/demand-projection.md).

Table 1: Energy service demands in transport.

| **Code** | **Energy service demand**     | **Unit** | **Driver** |
| -------- | ----------------------------- | -------- | ---------- |
| **TAD**  | Domestic Aviation             | PJ       | GDP        |
| **TAI**  | International Aviation        | PJ       | GDP        |
| **TRB**  | Road Bus Demand               | Bv-km    | POP        |
| **TRC**  | Road Commercial Trucks Demand | Bv-km    | GDP        |
| **TRE**  | Road Three Wheels Demand      | Bv-km    | POP        |
| **TRH**  | Road Heavy Trucks Demand      | Bv-km    | GDP        |
| **TRL**  | Road Light Vehicle Demand     | Bv-km    | GDP        |
| **TRM**  | Road Medium Trucks Demand     | Bv-km    | GDP        |
| **TRT**  | Road Auto Demand              | Bv-km    | GDPP       |
| **TRW**  | Road Two Wheels Demand        | Bv-km    | POP        |
| **TTF**  | Rail-Freight                  | PJ       | GDP        |
| **TTP**  | Rail-Passengers               | PJ       | POP        |
| **TWD**  | Domestic Internal Navigation  | PJ       | GDP        |
| **TWI**  | International Navigation      | PJ       | GDP        |

For the base year, the final energy consumption for the transport sector is modelled by region using the IEA database (consumption estimates for the most important modes of transport without allocation to specific vehicle types) and calibrated using the extended IEA energy balance data. The share estimates for fuel distribution in road and rail transport are carried out by the modeler on the basis of expert estimates and/or regional data. While fuel consumption (IEA data) is broken down into different vehicle classes for road transport, a distinction is made between passenger and freight transport for rail transport. The template for the base year 2018 also contains the data for balancing the emissions generated in the transport sector.

For the transport sector, energy carriers, such as coal, gas, diesel, gasoline, aviation gas, kerosene, heavy fuel oil, ethanol and electricity are considered. All of them are linked as an input to the specific process (e.g. car). Fuel switches are modelled endogenously based on the given technologies. Each energy carrier has a specific emission output, which is calculated based on the endogenous emission factor stored in TIAM.

The technologies for covering the energy service demand of the transport sector are broken down into the individual subsectors based on the area of application. The existing technologies have so far been modelled in such a way that the demand for energy services could be covered in the base year 2018. New investments in existing technologies are not planned - these will be gradually replaced by new technologies, which are also characterized by parameters such as efficiency and investment costs. Due to the fact that several technologies are available for each end use, there is competition between them. Due to the technological competition between them, a constant improvement of the technologies in terms of process efficiency and costs is expected over the modelling period. There are major differences between the transport sectors - many new technologies are ready for use in road transport, while only a few alternative technologies are available for rail, air and sea transport. When modelling different regions, location-specific factors must be taken into account when calculating the investment and operating costs (in US$).
