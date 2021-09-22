# More_Birds_than_Stones
Contains the Mathematica code of the model used in the paper "More birds than stones – A framework for second-best energy and climate policy adjustments".

*******************************
* Model documentation
* 
* "More birds than stones - A framework for second-best energy and climate policy adjustments"
*
* Carolyn Fischer, Michael Huebler &  Oliver Schenker
*
* September 2021
*******************************

This file documents the model used to run the numerical simulations in this paper. The model and its calibration is described in Section 5 of the paper

The model has been programmed in Mathematica. In order to execute the model a running Mathematica environment is necessary.


****************************
FHS_base-first-best.nb

This is the base file that always needs to run first. It calibrates the model and computes the relevant benchmarks -- the no-policy and the first-best policy case.
****************************

The subsequent files are then 2nd-best simulations under incomplete policies.
We recommend to clear memory after each simulation of incomplete policies and start with the base file again. 

****************************
FHS_2ndb_no_ee.nb

* No Energy Efficiency Subsidies
Generates table 3 in the paper and the respective part in table 6 on missing energy efficiency subsidies. It generates also the respective part in table A.4 in the appendix.

****************************
FHS_2ndb_no_rnd.nb

* No R&D Subsidies
Generates Table 4 in the paper and the respective part in Table 6. It generates also the respective part in table A.4 in the appendix.


****************************
FHS_2ndb_no_lbd.nb

* No Output Subsidies for Renewables
Generates Table 5 in the paper and the respective part in Table 6. It generates also the respective part in table A.4 in the appendix.

******************





