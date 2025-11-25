---
title: "Control Co-Design (CCD) Frameworks"
excerpt: "<br/><img src='/images/CCD_methods.png'>"
collection: portfolio
---

<p style="text-align: justify;">
Control Co-Design (CCD) is a unified optimization paradigm that simultaneously determines both the physical architecture of a system and the control strategy that governs its operation. In traditional engineering workflows, structural design and control design occur in separate, sequential stages: engineers first fix the physical configuration and only afterward design the controller. This separation ignores the deep coupling between dynamics and actuation, often producing conservative, over-engineered, or suboptimal solutions.
</p>

<p style="text-align: justify;">
My research addresses this limitation by developing scalable CCD frameworks that explicitly integrate plant dynamics, control logic, structural design variables, and real-world operating conditions into a single mathematical formulation. By embedding control performance directly into the system-level design space, these frameworks reveal new trade-offs—such as energy capture versus structural loading, stability versus actuation limits, and performance versus cost—that are not visible under sequential design. Through model-based and surrogate-enabled formulations, I extend CCD to systems with nonlinear dynamics, multi-domain interactions, and large design spaces, demonstrating that CCD is broadly applicable to nearly any engineered system where physical design and control decisions are inherently intertwined.
</p>

### Key Contributions

- Developed unified control co-design formulations that couple plant design variables with advanced control strategies in a single optimization framework.

- Built and validated CCD methods for floating wind turbines, hybrid wind–wave energy systems, vertical-axis platforms, and marine energy converters, demonstrating improved performance across multiple renewable energy applications.

- Shown that CCD principles generalize broadly to engineered systems with strong coupling between physical design and control, including robotics, vehicle suspension systems, dynamic mechanical systems, and other domains where plant configuration and control architecture must be designed together.

### Selected Publications

- Bayat, S., Zuo, J., and Sun, J.  
  "Modeling and Dynamic Simulation of a Hybrid Floating Wind–Wave Platform with Integrated Flap-Type Wave Energy Converters."  
  *Ocean Engineering*, 2025. [Link](https://arxiv.org/abs/2510.15285)

- Bayat, S., and Zuo, L.  
  "Multidisciplinary Control Co-Design of a Spar–Torus Hybrid Wind–Wave Energy System."  
  *Journal of Mechanical Design*, 2025. [Link](https://asmedigitalcollection.asme.org/mechanicaldesign/article/doi/10.1115/1.4070400/1228297?casa_token=8lxhAcPokOwAAAAA:v_JSaXavPQ1Una_h_NzBsqLauS-8xd-m4jcFtADpXfWdLHfTjuWHkxAhk9TqmNX9XfpilZCJ)

- Bayat, S., Lee, Y. H., and Allison, J. T.  
  "Nested Control Co-Design of a Spar Buoy Horizontal-Axis Floating Offshore Wind Turbine."  
  *Ocean Engineering*, 2025. [Link](https://www.sciencedirect.com/science/article/pii/S0029801825007504)

- Bayat, S., and Allison, J. T.  
  "Impact of Control Strategies on the Control Co-Design of Spar Floating Offshore Wind Turbines."  
  *Ocean Engineering*, 2025. [Link](https://www.sciencedirect.com/science/article/pii/S0029801825014696)

- Lee, Y. H., Bayat, S., and Allison, J. T.  
  "Wind Turbine Control Co-Design Using Dynamic System Derivative Function Surrogate Model (DFSM) Based on OpenFAST Linearization."  
  *Applied Energy*, 396:126203 (2025). [Link](https://www.sciencedirect.com/science/article/abs/pii/S030626192500933X)

- Lee, Y. H., Bayat, S., Allison, J. T., Hossain, M. S., and Griffith, D. T.  
  "Multidisciplinary Modeling and Control Co-Design of a Floating Offshore Vertical-Axis Wind Turbine System."  
  *Journal of Mechanical Design*, 2025. [Link](https://asmedigitalcollection.asme.org/mechanicaldesign/article/147/6/061702/1213031/Multidisciplinary-Modeling-and-Control-Co-Design)

- Bayat, S., and Allison, J. T.  
  "Control Co-Design with Varying Available Information Applied to Vehicle Suspensions."  
  *Journal of Dynamic Systems, Measurement, and Control*, accepted (2025). [Link](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=pKbaaS0AAAAJ&citation_for_view=pKbaaS0AAAAJ:qUcmZB5y_30C)

<img src="/images/CCD_methods.png" style="width:100%;margin-top:20px;">

