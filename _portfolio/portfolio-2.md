---
title: "Surrogate Modeling and Data-Driven Design"
excerpt: "<br/><img src='/images/xdsm_plot.png' style='width:70%;'>"
collection: portfolio
---


<p style="text-align: justify;">
Large-scale control co-design (CCD) problems often depend on high-fidelity physics models—such as aero-hydro-servo dynamics or multi-domain structural simulations—that are far too computationally expensive for iterative optimization. My research addresses this challenge by developing surrogate modeling frameworks that dramatically accelerate simulation without sacrificing essential dynamic behavior. These surrogates enable fast exploration of complex, nonlinear design spaces and support thousands or even tens of thousands of CCD iterations that would otherwise be infeasible with full-order simulation.
</p>

<p style="text-align: justify;">
A central contribution of this work is the Dynamic Function Surrogate Model (DFSM), which approximates key system dynamics with high accuracy while reducing computational cost by nearly two orders of magnitude. This framework enables efficient prediction of dynamic responses and gradients, making surrogate-assisted CCD practical for real-world engineering systems. Complementing DFSM, I have developed physics-informed low-order models that preserve essential floating wind turbine and wave-structure interaction dynamics while achieving more than an order-of-magnitude speedup. These approaches extend naturally to vertical-axis wind turbine systems, supporting trade-offs among energy capture, structural loading, manufacturability, and control responsiveness.
</p>

<p style="text-align: justify;">
More broadly, the surrogate modeling strategies I develop generalize to many engineered systems in which multi-physics simulations are computationally burdensome. These include reduced-order aerodynamic models, vehicle and structural dynamics approximations, and digital twin architectures used for monitoring and predictive analysis. By accelerating the feedback loop between design, dynamics, and control, these surrogate-based tools enable intelligent, adaptive, and computationally efficient co-design across a wide range of complex mechanical and dynamic systems.
</p>

### Key Contributions

- Developed the Dynamic Function Surrogate Model (DFSM), enabling large-scale CCD by approximating nonlinear system behavior with high accuracy and a ~100× speedup.
- Designed physics-informed low-order models for floating wind and wind–wave platforms that preserve essential dynamics while dramatically reducing computational cost.
- Extended surrogate modeling approaches to vertical-axis wind turbines to support design trade-offs among energy capture, loading, and manufacturability.
- Demonstrated broad applicability of surrogate-enabled modeling to multi-physics engineering systems where high-fidelity simulation is too expensive for iterative optimization.

### Selected Publications

- Lee, Y. H., Bayat, S., and Allison, J. T.  
  "Wind Turbine Control Co-Design Using Dynamic System Derivative Function Surrogate Model (DFSM) Based on OpenFAST Linearization."  
  *Applied Energy*, 396:126203 (2025).  
  [Link](https://www.sciencedirect.com/science/article/abs/pii/S030626192500933X)

- Bayat, S., Lee, Y. H., and Allison, J. T.  
  "Nested Control Co-Design of a Spar Buoy Horizontal-Axis Floating Offshore Wind Turbine."  
  *Ocean Engineering*, 2025.  
  [Link](https://www.sciencedirect.com/science/article/pii/S0029801825007504)

- Lee, Y. H., Bayat, S., Allison, J. T., Hossain, M. S., and Griffith, D. T.  
  "Multidisciplinary Modeling and Control Co-Design of a Floating Offshore Vertical-Axis Wind Turbine System."  
  *Journal of Mechanical Design*, 2025.  
  [Link](https://asmedigitalcollection.asme.org/mechanicaldesign/article/147/6/061702/1213031/Multidisciplinary-Modeling-and-Control-Co-Design)

<img src="/images/xdsm_plot.png" style="width:70%;margin-top:20px;">
