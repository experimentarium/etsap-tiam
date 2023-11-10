## Security of Supply

When it comes to global commodity trades (cf. [Global Trade of Commodities](https://etsap-tiam.readthedocs.io/en/latest/restrictions/trading-restrictions.html)) in least cost linear energy system models there is the “the winner takes it all” phenomenon that might occur if the demand is satisfied by the production of a single TIAM region.
In order to avoid this phenomenon, trading restrictions can be applied. This could either be done by using bounds on market shares or restricting the commodity flows itself. 
Table 1 shows two examples of scenarios to ensure security of supply (SoS). 


Table 1: Trading restrictions to ensure security of supply based on two examples.

| No. | Scenario name | Description                                                                                                                                                                                              |
|-----|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | SoS1          | Security of Supply scenario, At least 50% of a commodity must be out of domestic production.                                                                                                            |
|  2 | SoS2          | Security of Supply scenario. At least 33% of a commodity must be out of domestic production. At least two trading partners. Each trading partner can satisfy a maximum share of 33% of the local demand. |

### Implementation

Scenario 1 (SoS1), see Table 1, could be described via mathematical formulation in order to apply restrictions. The hydrogen demand ($H_2Demand$) can be satisfied by using local production ($H_2Loc$) and hydrogen exportet from other regions ($H_2Exp$), see Equation 1. In order to ensure that at least 50% is out of local production $H_2Loc$ must be equal or greater than half of the total demand, see Equation. Bringing Equation (1) and ) together (see Equation 3) and rearrange, Equation 4 gives the final description that can be used for applying flow restrictions in the TIAM model. Scenario 2 can also be similarly described using the mathematical formulation.

$H_2Demand=H_2Loc+H_2Exp$ (1)


$H_2Loc\geq\frac{1}{2}\ H_2Demand\ $ (2)

$H_2Loc\geq\ \frac{1}{2}\ \left(H_2Loc+H_2Exp\right) $ (3)

$\frac{1}{2}H_2Loc\ -\frac{1}{2}H_2Ex\geq0\ $ (4)
