## Handling Shells

The energy systems model TIAM was developed using the [VEDA approach](https://times.readthedocs.io/en/latest/part-4) to TIMES model specification. VEDA2.0 is a data management system used to manage TIMES model input data and analyse results of optimisation. Via a UI, VEDA allows creating, maintaining, browsing and modifying model databases.

VEDA reads TIMES model data (e.g. ETSAP-TIAM), specified in Excel files, into an internal database. Using the interface, one can specify which input data should be used for a specific model run. In order to solve the model, VEDA outputs the input values, constraints and the objective function to GAMS which uses the data together with [TIMES source code](https://github.com/etsap-TIMES/TIMES_model). GAMS stands for Generic Algebraic Modeling System. It is an efficient modeling language used to formulate optimisation problems [2]. After the model is solved, the solution is read by VEDA. It facilitates the analysis of results by filtering the data and displaying it as tables and charts. A simplified schematic showing interrelation between the model data inputs, VEDA, TIMES source code, GAMS and the model output is shown in Figure 1.

![Interrelation between TIMES model data, VEDA, TIMES source code, GAMS and the model output](./figs/veda_20_framework.png) 
Figure 1: Block diagram of the interrelation between TIMES model data, VEDA, TIMES source code, GAMS and the model output [1].

### References

[1] 	"ETSAP, VEDA Description", 2023. [Online]. Available: https://www.iea-etsap.org/index.php/etsap-tools/data-handling-shells/veda.

[2] 	"GAMS- General Algebraic Modelling System", 2023. [Online]. Available: https://www.gams.com/.
