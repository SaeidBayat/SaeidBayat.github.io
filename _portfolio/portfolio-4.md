---
title: "Model Predictive Control and Experimental Validation"
excerpt: "<br/><img src='/images/exp_work.png' style='max-width:900px;'>"
collection: portfolio
---

<p style="text-align: justify;">
A central goal of my research is to bridge advanced control theory with real-world experimental validation by developing model predictive control (MPC) tools that integrate naturally within control co-design (CCD) frameworks. Many dynamic systems of interest—such as renewable energy devices, robotic mechanisms, and mechanical platforms—operate under nonlinear, constrained, and uncertain conditions. MPC provides a principled way to address these challenges, but traditional formulations are often too computationally demanding for CCD or hardware-in-the-loop (HIL) workflows. My work develops scalable MPC methods and experimental platforms that close this gap and translate predictive control algorithms into practical, real-time implementations.
</p>

<p style="text-align: justify;">
A foundational contribution is the Single-Shooting MPC (SS-MPC) framework, which integrates real-time optimization with filtering and state estimation to produce a fast and open-source predictive control tool. SS-MPC is designed for CCD workflows and supports HIL testing, enabling seamless transitions from simulation to physical experimentation. To further enhance accuracy and scalability, I developed an MPC formulation based on Legendre–Gauss–Radau pseudospectral methods, enabling high-fidelity prediction and efficient gradient computation within multidisciplinary optimization settings.
</p>

<p style="text-align: justify;">
Building on these computational tools, I applied CCD and predictive control to a dual-hydrofoil marine energy converter, coupling hydrodynamics, structural dynamics, and power take-off modeling to identify optimal pitch trajectories. This work—recognized with the <b>2025 ASME IDETC–CIE Best Paper Award</b>—demonstrates a complete pipeline from algorithm development to experimental relevance. These efforts illustrate how predictive control, system modeling, and experimental platforms can be integrated to support CCD across diverse dynamic systems, including renewable energy devices, robotic mechanisms, and high-performance mechanical platforms.
</p>

<p style="text-align: justify;">
This focus on real-world experimentation is grounded in earlier experience designing high-precision mechatronic systems. For my Master’s research at Sharif University of Technology, I developed a complete nano-positioning platform using piezoelectric actuators with strain-gauge feedback. This work combined theoretical modeling with extensive hardware development: I designed custom signal-conditioning electronics, programmed STM32 microcontrollers in C/C++, and implemented advanced observer and control algorithms—including neural, fuzzy, and ANFIS-based estimators as well as hysteresis compensation—to achieve nanometer-level positioning accuracy. The system featured high-voltage actuation, strain-gauge feedback loops, and a MATLAB/Simulink real-time interface supported by a custom GUI.
</p>

<p style="text-align: justify;">
This hands-on experience with real-time control, embedded systems, and sensor integration provided the foundation for my later research on HIL platforms, MPC-enabled CCD, and experimental system validation. Together, these contributions establish a cohesive program that connects computational control methods with practical implementation and prototype testing.
</p>

### Key Contributions

- Developed SS-MPC, an open-source single-shooting MPC framework combining real-time optimization and state estimation for CCD and HIL applications.
- Designed a high-fidelity pseudospectral MPC formulation using Legendre–Gauss–Radau collocation, enabling accurate prediction and scalable optimization.
- Integrated predictive control within CCD workflows for nonlinear, constrained, and multi-domain dynamic systems.
- Applied MPC-enabled CCD to a dual-hydrofoil marine energy converter and validated performance improvements through experimental modeling.
- Designed and implemented a complete nano-positioning platform, including custom electronics, embedded programming, advanced observers, and real-time control interfaces.

### Selected Publications

- Bayat, S., and Allison, J. T.  
  “A Practical Open-Source Approach to Model Predictive Control Using the Legendre–Gauss–Radau Pseudospectral Method.”  
  *Software Impacts*, 100769 (2025).  
  [Link](https://www.sciencedirect.com/science/article/pii/S2665963825000296)

- Bayat, S., and Allison, J. T.  
  “SS-MPC: A User-Friendly Software Based on Single Shooting Optimization to Solve Model Predictive Control Problems.”  
  *Software Impacts*, 17:100566 (2023).  
  [Link](https://www.sciencedirect.com/science/article/pii/S2665963823001033)

- Vijayasankar, V., Bayat, S., and Zuo, L.  
  “Development of a Scaled Hydrofoil-Based Marine Energy Converter: Design, Modeling, and Parametric Optimization.”  
  *Journal of Vibration and Acoustics*, 2025.  
  [Link](https://asmedigitalcollection.asme.org/vibrationacoustics/article/doi/10.1115/1.4069429/1220940)

- Bayat, S., Pishkenari, H. N., and Salarieh, H.  
  “Observer Design for a Nano-Positioning System Using Neural, Fuzzy, and ANFIS Networks.”  
  *Mechatronics*, 59:10–24 (2019).  
  [Link](https://www.sciencedirect.com/science/article/pii/S0957415819300194)

### Experimental Image


<img src="/images/exp_work.png" style="width:100%;margin-top:20px;">
