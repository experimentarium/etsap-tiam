# Demand Projection

As TIAM operates as a partial-equilibrium model, it requires a baseline [energy service demand](../sectoral_coverage/energy-service-demands.md) level for all energy service considered. [Sectoral coverage](../sectoral_coverage/index.md) presents a comprehensive list of energy-service demands for every sector. Each energy-service demand is associated with a specific driver, facilitating the projection of future demand throughout the model horizon (2018 to 2100). These drivers are linked to the energy-service demands through a constant and an elasticity, following equation (1).

$$ Demand_{t}=\ Demand_{t-1} \times driver^{elasticity} $$  (1)

The demand drivers encompass various factors such as population (POP), GDP, number of households (HOU), GDP per capita (GDPP), GDP per household (GDPPHOU), and drivers specific to agriculture (PAGR), services (PSER), and industry. The projection for these drivers are collected from the Shared Socio-economic Pathways (SSP) [1-2] for each [region](../regional_coverage/index.md) of ETSAP-TIAM. The user decides which SSP drives the projection of GDP, population, and households.
Empirically, the elasticties of the demands to their driver are set and interpolated linearly from 0.8 in 2018 to 0.6 in 2100 for developped economies (CAN, USA, WEU, SKO, JPN, FSU and AUS) to account for a certain decoupling in economic growth and demands. For developing economies (MEX, CSA, AFR, EEU, ODA, IND, MEA) elasticities are set from 1 in 2018 to 0.8 in 2100, and China shows a more rapid decoupling, moving  from 1 in 2018 to 0.6 in 2100.

## References
[1]	Riahi, K., van Vuuren, D.P., Kriegler, E., Edmonds, J., O’Neill, B.C., Fujimori, S., Bauer, N., Calvin, K., Dellink, R., Fricko, O., Lutz, W., Popp, A., Cuaresma, J.C., Kc, S., Leimbach, M., Jiang, L., Kram, T., Rao, S., Emmerling, J., Ebi, K., Hasegawa, T., Havlik, P., Humpenöder, F., Da Silva, L.A., Smith, S., Stehfest, E., Bosetti, V., Eom, J., Gernaat, D., Masui, T., Rogelj, J., Strefler, J., Drouet, L., Krey, V., Luderer, G., Harmsen, M., Takahashi, K., Baumstark, L., Doelman, J.C., Kainuma, M., Klimont, Z., Marangoni, G., Lotze-Campen, H., Obersteiner, M., Tabeau, A., Tavoni, M., 2017. The Shared Socioeconomic Pathways and their energy, land use, and greenhouse gas emissions implications: An overview. Global Environmental Change 42, 153–168. https://doi.org/10.1016/j.gloenvcha.2016.05.009

[2] Dellink, R., Chateau, J., Lanzi, E., Magné, B., 2017. Long-term economic growth projections in the Shared Socioeconomic Pathways. Global Environmental Change 42, 200–214. https://doi.org/10.1016/j.gloenvcha.2015.06.004

