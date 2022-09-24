---
layout: page
title: UAM Digital Twin Technology
---

# Digital Twin Requirements
It is required to develop a vehicle digital twin (DT) for urban air mobility (UAM) which relies on an accurate, physics-based emulator to characterize the statics and dynamics of a vehicle. Because, the adoption of digital twin in operations and control of the vehicle is necessary for the UAM operational digital twin infrastructures (UAM-ODT). The issues are: (i) lack of digital twin engines for the digitalization (twinization) of dynamics and control of UAM vehicle running at the core center of UAM-ODT systems; and (ii) lack of back-end system engineering in the development of UAM vehicle DT. In that regard, our research proposes and discusses on an engineering direction for the development of UAM vehicle DT engines and systems.

# Introduction
Innovative DT technology has the potential to transform a number of expanding industries. In DT, the idea of incorporating physical-twin-specific calculations into a feedback loop of data-driven analysis and dynamically updated decision-making is introduced. DTs are collections of connected computational models that progressively change state-spaces over time to mimic the underlying structure, behaviours, and environment of their physical counterparts [1,2]. This research presents a study on how the UAM vehicle DT can be developed by proposing fundamental engines for the transformation of dynamics and control of a UAM vehicle from real to digital spaces.

# UAM Vehicle Digital Twinization Engines

The overall architecture of an UAM-ODT entails four fundamental modules, as shown in Fig. 1: (i) neural digital twin dynamic engines (DTDE), (ii) neural digital twin control engines (DTCE), (iii) digital twin control frame, and (iv)  (DTCI) cloud infrastructure. The DTDE module uses learning-based approaches to duplicate the UAM cars' aerodynamics. DTCE module handles the control duties, whereby robust control, optimum control, and adaptive control may be produced for the vehicle's safety.

![](../assets/img/UAM_ODT.png)
**Fig. 1. UAM Vehicle Digital Twinization Engines**

These two components will digitalize the vehicle's dynamics and control, ensuring that its operations in both the digital and physical worlds may be exact replicas of one another. The DTCF module is designed to provide a DT bridge connecting the vehicle's physical and DTs. This module can offer tele-operation services, fault-tolerant control, or traffic prediction and management. Without loss of generality, if the physical vehicle's dynamics and control are accurately represented in the digital space, along with the digital environment (such as cities, regions, and countries), the operations in the digital space can be successfully applied to the physical space. The UAM-ODT system as a whole runs continuously on the DTCI module to create a virtual representation of the actual UAM physical infrastructure.

# Digital Twin Dynamics Engine (DTDE)
To twinize the dynamics of a vehicle, we develop a deep learning based dynamics engine in the form of a deep neural network (DNN) which can capture the real behaviors of vehicle dynamics as shown in Fig. 2. The DNN (Fig. 2 (a)) is trained upon the real flight test data in manual control mode to capture the correlation between the control input and the response states, which is the real vehicle dynamics. 

![](../assets/img/DTDE.png)

*(a) Neural Dynamics Engine*

![](../assets/img/DTDE_Transfer_Learning.png)

*(b) Transfer Learning for Fidelity Improvement*

![](../assets/img/DTDE_Dynamics_Prediction.png)

*(c) Dynamics prediction*

**Fig. 2: Digital Twin Dynamics Engines (DTDE)**

Transfer learning (Fig. 2 (b)) is used to enhance the coverage of training data and to improve the fidelity of dynamics engine. Since the simulation models from different levels of fidelity can provide sufficient operational flight modes. Preliminary results in Fig. 2 (c) show that the approach can apparently clone the flight dynamics of the vehicle both based on simulation data and real flight test data of hexa-copter drone “Sundori” and KP-01 eVTOL vehicle under development in Konkuk Aerospace Design-Airworthiness Institute (KADA), Konkuk university, Seoul, South Korea.  

# Digital Twin Control Engine (DTCE)
Control algorithms of the real vehicle are encapsulated in the DTCE module which includes (i) robust control, es-DNLC [3], a deep neural network control with exponentially stabilizing control Lyapunov functions for attitude stabilization of PAVs in Fig. 3 (a), (ii) optimal control, tilting optimization using reinforcement learning in Fig. 3 (b) to find optimal strategy for tilting scheduling during transition mode, (iii) adaptive control in Fig. 3 (c), which is to optimize control parameters using Bayesian optimization approach and Gaussian processes for dynamics representation.
The preliminary results in Fig. 3 (d) show that our approach using deep learning based control with Lyapunov stability can guarantee a high level of robustness for operational flights (attitude stabilization) of the UAM vehicle KP-01.

![](../assets/img/Control_Robust.png)

*(a) es-DNLC*

![](../assets/img/Control_Optimal.png)

*(b) Tiltiing Optimization using RL*

![](../assets/img/Control_Adaptive_Optimization.png)

*(c) Bayesian optimization of controller*

![](../assets/img/Preliminary_Results_DTCE.png)

*(d) Preliminary results of deep neural Lyapunov control*

**Fig. 3: Digital Twin Control Engine (DTCE)**

# Digital Twin Control Frame (DTCF)
It is believed that the DTDE, and DTCE can capture exactly how the physical vehicle can fly in the real space. At this time, the control in the digital space can be adopted for the real-world operations of the physical vehicle in the physical space. Tele-operations and fail-safe flights can be developed through the DTCF module in Fig. 4.  A bridge for virtual-real space connection is developed using MAVLink API to transmit and receive aerospace data between the physical-digital vehicles in asynchronous and irregular manner.

![](../assets/img/DTCF.png)

**Fig. 4: Digital Twin Control Frame (DTCF)**

# Digital Twin Cloud Infrastructure (DTCI)
The above modules are for the DT development of a single UAM vehicle. To develop the UAM-ODT system for a huge number of vehicles, a cloud infrastructure is involved for the deployment of nucleus cores of **[dynamics and control]** of heterogeneous vehicles as shown in Fig. 5.

![](../assets/img/DTCI.png)

**Fig. 5: Digital Twin Cloud Infrastructure (DTCI)**

# Remarks
This research proposes and discusses an overall engineering direction for the development of UAM vehicle digital twin system. Preliminary results prove that the approaches can clone the dynamics and control of UAM vehicles for the development of UAM-ODT.

# References

[1] T.A. Nguyen, S.W. Jeon, A.A. Maw, D.K. Min, J.W. Lee, (2020), “Toward dependable blockchain and AI engines of digital twin systems for urban air mobility”, The Korean Society for Aeronautical & Space Sciences, 한국항공우주학회 학술발표회 초록집, 2021.07, 408-409.

[2] T.A. Nguyen, J. Li, M. Jang, A.A. Maw, V. Pham, J.W Lee, (2022), “Cloud-in-the-loop simulation: A cloud-based digital twin HW/SW framework for multi-mode AI control simulation of eVTOL KADA-UAM Personal Aerial Vehicles”, The Korean Society for Aeronautical & Space Sciences, 한국항공우주학회 학술발표회 초록집, 2022.04, 138-139.

[3] M. Jang, J. Hyun, T.A. Nguyen, J.W. Lee, (2022), “Attitude Stabilization of eVTOL in Hovering Mode using Neural Network based Control with Lyapunov Theorem”, The Korean Society for Aeronautical & Space Sciences, 한국항공우주학회 학술발표회 초록집, 2022.04, 322-323.
