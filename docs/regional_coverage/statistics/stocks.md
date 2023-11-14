## Stocks

The stocks describe the existing capacity in the base year of the TIAM model. Stocks need to be decommissioned after time, this is done in a linear manner by TIMES. If the decommissioning is not linear, this can be manually adjusted in the model.

### Power Sector

As the energy balance provides energy flows instead of the actual installed capacity, this can be recalculated by using the availability of the technology (e.g. wind onshore or coal power plants) and the activity to capacity ratio. The capacity to activity ratio measures the maximum quantity of energy that is produced by using 1 unit of capacity in relation to the energy unit. In TIAM the activity unit is Petajoule (PJ) and the capacity unit is Gigawatt (GW). With 1 year having 8760 hours 8760 GWh are produced for 1 GW of installed capacity and an availability of 100%. 

$CAP2ACT=\frac{CAP}{ACT}=\frac{(1GW⋅8760h)}{PJ}=\frac{(8760 GWh)}{PJ}=\frac{(31,536 PJ)}{PJ}=31,536$

1 PJ of coal with an estimated availability factor of 95% equals 0,033 GW of capacity.
This procedure is done for all energy flows in order to get the associating capacity for all technologies in the power sector (cf. Power Sector).

### Industry

The industry is split into 6 different end products (cf. Industry). While some of the end products as steel are modelled in the activity unit megatons (MT) others as the chemical sector are modelled in PJ. For all of the end products energy service demands are necessary as steam, process heat etc. All of the service demands for the industry are modelled in an energetic manner. The stocks therefore are applied to the energy service demands which relates the years of machine capacity. 

### Residential

The residential sector is modelled in an energetic manner. Capacities are not considered, instead the energy service demand (e.g. heat, cooling or light) are deposited as a stock for the base year technologies. 

### Commercial

The commercial sector is modelled as the residential sectors in terms of stocks. 

Agriculture

There is no capacity considered in the agriculture sector. The energy demands are modelled via energy flows (cf. Agriculture). 

### Transport

In the transport sector the activity unit of a technology (e.g. road car) is Bv-km while the capacity unit is Bv-km/a. Therefore, the conversion factor is 1. 
Based on the energy balance the quantity of oil, gas etc. is provided for the whole sector. In order to get the Bv-km for each category (e.g. road car) the efficiency must be applied. The efficiency describes the ratio of Bv-km per PJ of energy input. In TIAM a stock of Bv-km is modelled which refer to the lifetime of technology.
