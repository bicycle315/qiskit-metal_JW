# QiskitMetal

* Parametric Sweep

 I can now understand how the design is rendered to the renderer , how to **set variable** and to **sweep that variable**!!

---
* CapacitanceMtx & LOM Anaylsis => Q3D

Due to the license issue i cant directly analyze setup by running metal codes on jupyter. I render all the design to ansys by metal and diconnect metal from q3d. Inside ansys i submit job to my boss computer to calculate.

`c1.sim.run() , c1.sim._anayze()` : dont work

`cl.sim.capacitance_matrix` : only shows empty braket even though i finised my simulation in ansys gui and connected ansys with metal jupyter kernel by `cl.sim.strat()` again.

-> Marco's Idea **(PR)**

de-embedding data harvesting method `get_results_from_renderer()`   from 'analysis run' method `_analyze()` so that the former can be called independently from the latter, enabling running the simulation from the Ansys GUI and later harvest the results.

---
* S,Y,Z analysis => HFSS-DrivenModal Analysis
---
* Eigenmode & EPR Analysis => HFSS-Eigenmode Analysis

  * Analyzing & Tuning a Resonator => HFSS-Eigenmode & EPR
---



