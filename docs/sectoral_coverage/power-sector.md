# Power Sector

The electricity or power generation sector represents many different types of technologies ranging from fossil-based coal power plants to renewable technologies, e.g. PV and wind power plants. TIAM model focuses explicitly on renewable power plants - Solar PV, Biomass, Hydropower, Nuclear, Onshore and Off-shore wind power plants. The power sector Base-Year template is employed for calibration of the base year electricity generation. The complete electricity production is fed into the grid/transmission network for use in energy demand sectors. Off-grid power production (micro-generation technologies) is not yet modelled in TIAM.

In terms of economic evaluation, TIAM considers explicitly CAPEX, OPEX, efficiency and lifetime of the power plants for electricity supply. The model considers unlimited commodities/resources for renewable plants  (subject to restrictions described in the section on [renewable potentials](../restrictions/potentials-renewable.md)). Unlike coal or oil which incur expenses for production; renewable sources - solar radiation or wind energy are supplied at no costs. Hence, no additional expenses for fuel are considered. As explained in the [time resolution](../model_objective/time-horizon.md) section, TIAM model has ten different periods. The table below shows CAPEX costs for four different time periods. This illustrates the trend in declining CAPEX as the technologies get more mature and become less expensive to invest in the future.

These technologies are used as input to the TIAM model for power generation, green hydrogen production and are part of the objective function of minimizing the total costs.

Table 1: CAPEX, OPEX, efficiency and lifetime of different renewable power plants
| Technology    | CAPEX in 2020 [EUR/kW] | CAPEX in 2030 [EUR/kW] | CAPEX in 2040 [EUR/kW] | CAPEX in 2050 [EUR/kW] | OPEX [%CAPEX/a] | Efficiency [%] | Lifetime [Years] | Source  |
|---------------|-----------|-------|-------|-------|------------|------------|----------|----------|
| Onshore Wind  | 1257     | 1137 | 987   | 923   | 3          | 100        | 25       | [1]      |
| Solar PV      | 703       | 395   | 340   | 326   | 1          | 100        | 25       | [1]      |
| Biomass       | 2037     | 1954 | 1892 | 1826 | 3.5        | 100        | 25       | [2], [3] |
| Hydro Power   | 2793         | 2783     | 2783     | 2718 | 2          | 100        | 100      | [2], [4] |
| Offshore-Wind | 2858         | 2731     | 2634     | 2523 | 3          | 100        | 25       | [4]      |
| Nuclear       | 4912         | 4912     | 4912     | 4912 | 4          | 30         | 60       | [4]      |

## Carbon capture technology options
Carbon Capture technologies are included for certain fossil-based and biomass gasification plants. Technologies like oxyfuel process is combined with the coal and natural gas power plants to produce a storable and transportable CO2 commodity alongside electricity. This CO2 commodity is then transported to different long-term storage locations as mentioned in [CCS potentials]( https://etsap-tiam.readthedocs.io/en/latest/restrictions/ccs-potentials.html). For the case of biomass plants, CO2 can be directly captured from the atmosphere (negative emissions) and transported to the storage locations. 


## References

[1]	R. C. Pietzcker, S. Osorio, and R. Rodrigues, “Tightening EU ETS targets in line with the European Green Deal: Impacts on the decarbonization of the EU power sector,” Applied Energy, vol. 293, p. 116914, 2021, doi: 10.1016/j.apenergy.2021.116914.

[2]	F. Ausfelder, D. Du Tran, A. Cadavid Isaza, C. de La Rua, J. Gawlick, and T. e. a. Hamacher, 4. Roadmap des Kopernikus-Projektes P2X Phase II – OPTIONEN FÜR EIN NACHHALTIGES ENERGIE- SYSTEM MIT POWER-TO-X- TECHNOLOGIEN.: Transformation – Anwendungen – Potenziale.

[3]	IEA, “World Energy Outlook 2018,” Paris, Nov. 2018. Accessed: Jan. 30 2023. [Online]. Available: https://www.iea.org/reports/world-energy-outlook-2018.

[4]	Joint Research Centre Data Catalogue. Accessed: Jan. 30 2023. [Online]. Available: https://data.jrc.ec.europa.eu/collection/id-00287.
