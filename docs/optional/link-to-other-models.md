## Link To Other Models

### General Linkage

The TIAM model is a technology rich bottom-up model that describes the competition of technologies (e.g. coal powerplants, solar pv, wind onshore in the power sector) to satisfy the energy service demands on a microeconomic level, see figure 1. In order to extend this view, different approaches of linkage can be applied, see table 1. 

![Model Comparison](./figs/model_comparison.png) 

Figure 1: Bottom-up and top-down models in comparison.

Table 1: Main benefits and challenges of different linking approaches.
| **Link approach** | **Main benefit(s)**         | **Main challenge(s)**                       |
| ----------------- | --------------------------- | ------------------------------------------- |
| Soft-linking      | Flexibility                 | Inconsistency                               |
| Hard-linking      | Consistency                 | Superficiality                              |
| Full integration  | Flexibility and consistency | Dimensionality and computational complexity |

### TIAM Macro Model

The TIAM model can be extended by a macro model in order to get the macroeconomic view included (cf. figure 1). TIAM is a linear energy system model while the macro module is represented by a non-linear macroeconomic model called TIAM-Macro Stand-alone (TSAM). The key function of the TSAM model is the constant elasticity of substitution (CES) function (cf. figure 2). By using the CES function the economic behaviour can be described. 
The TIAM model has connections to the energy system cost, es well es the energy service demands (cf. figure 2), while the TSAM model is using capital and labor for the CES function in order to create feedback loops that affect the TIAM model, based on the energy system costs (cf. figure 2).

![TIAM and TSAM combination](./figs/tsam_extension.png) 
Figure 2: TIAM Model linked to Macro extension.