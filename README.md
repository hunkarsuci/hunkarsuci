# Hünkar Suci

### Flight Control & GNC · Aerospace Software · Avionics & Embedded Systems

**M.Sc. Mechanical Engineering (Maschinenwesen) student at the Technical University of Munich**

I am an aerospace-focused engineer in the Munich area, working toward a career in guidance, navigation and control (GNC). My experience spans flight-control and estimation projects, avionics software verification, HIL/DAQ, autonomous UAV navigation, embedded hardware, and production C++/Qt test automation.

My current technical focus is robust flight-control software, control allocation, state estimation, and verifiable avionics systems. This semester, I am also expanding my RF and antenna-engineering foundation, building on earlier SDR, GNSS telemetry, and SATCOM link-budget work.

📍 Munich area, Germany · [LinkedIn](https://www.linkedin.com/in/hunkar-suci)

## Technical focus

- **Guidance, navigation and control** — dynamic modeling, trim, linearization, control laws, guidance logic, and closed-loop evaluation
- **Flight dynamics and control systems** — nonlinear and linear aircraft models, actuator dynamics, PID/LQR, control allocation, and response analysis
- **State estimation and sensor fusion** — Kalman filtering, error-state estimation, visual-inertial odometry, IMU/GPS/barometer models, and numerical verification
- **Embedded and avionics software** — C/C++, Qt/PyQt, MATLAB/Simulink, hardware interfaces, automated verification, and CI
- **SIL/HIL and test automation** — LabVIEW, DAQ, sensor simulation, calibration, traceable regression testing, and reproducible debugging
- **RF and antenna engineering** — current antenna coursework with prior SDR front-end, GNSS telemetry, and SATCOM link-budget experience

## Engineering experience

| Organization | Role and evidence |
| --- | --- |
| **Rohde & Schwarz** | C++/Qt software development and regression-test automation for Linux/Wayland applications; CI integration, defect investigation, and verification traceability |
| **Qualcomm** | Embedded software and hardware work for ADAS/AD lab systems; CAN-bus harnesses, Embedded C, and a 32-I/O cable-tester prototype |
| **TUM Institute of Flight System Dynamics** | Avionics software testing in a DO-178C-oriented environment; C/C++, MATLAB, and a Python/PyQt avionics data viewer |
| **Airbus Defence and Space** | LabVIEW-based HIL/DAQ automation for thermal-vacuum testing; UART/CAN/Ethernet interfaces, sensor simulation, calibration, and lab-data pipelines |
| **TUM student research** | Autonomous UAV navigation in ROS with C++/Python control algorithms and Gazebo waypoint simulations |
| **WARR - TUM Student Space Program** | SDR-based RF front-end work for GNSS telemetry/beacon signals and SATCOM link-budget validation |
| **Turkish Aerospace** | Internship experience in UAV flight dynamics, control, and performance analysis using MATLAB/C++ |

## Selected GNC and flight-control work

| Project | Engineering evidence | Scope |
| --- | --- | --- |
| [Generic delta-canard 6DOF](https://github.com/hunkarsuci/generic_delta_canard_fighter_6dof) | Nonlinear rigid-body dynamics, trim, numerical linearization, modal analysis, PID/LQR, control allocation, actuator models, CI, and validation matrix | Generic research model with synthetic aerodynamic and propulsion data |
| [Drone error-state Kalman filter](https://github.com/hunkarsuci/KF_Implementation_for_Drone) | IMU prediction, GPS/barometer updates, quaternion attitude, deterministic metrics, covariance diagnostics, and Jacobian checks | Synthetic sensors; no flight-data validation |
| [Lateral-directional FCS](https://github.com/hunkarsuci/F16-Inspired-Lateral-Directional-FCS) | State feedback, command shaping, actuator constraints, closed-loop simulation, and automated tests | Simplified teaching model; not an aircraft-qualified control law |
| [B747 longitudinal C* control](https://github.com/hunkarsuci/b747-longitudinal-cstar-control) | Load-factor tracking, pitch-rate washout, actuator dynamics, saturation, and anti-windup | Educational single-trim-point control study |
| [Hydraulic-servo actuator dynamics](https://github.com/hunkarsuci/Hydraulic-Servo-Actuator-Dynamics) | Second-order response with acceleration, rate, and travel limits plus automated tests and CI | Software model without hydraulic hardware calibration |
| [32×32 cable tester](https://github.com/hunkarsuci/32x32-Cable-Tester) | Arduino firmware, multiplexer-based continuity scanning, wiring documentation, and fault classification | Prototype design; physical verification evidence is still planned |

## Current development

- Taking current coursework in **RF and antenna engineering**
- Strengthening **modern C++** for numerical, real-time, and safety-conscious engineering software
- Building further practical experience with **ROS 2** through new projects
- Extending flight-control and state-estimation projects with reproducible tests and explicit validation boundaries

## Engineering approach

I aim to make assumptions reviewable: coordinate frames and units, actuator and sensor limits, numerical checks, reproducible scenarios, and the distinction between simulated and measured performance. My repositories document both what their tests verify and what remains unvalidated.

## Toolkit

**Control and modeling:** State-space methods · Flight dynamics · LQR/state feedback · Control allocation · Actuator modeling · Kalman filtering · Numerical simulation  
**Programming:** C · C++ · Python · MATLAB/Simulink · Embedded C · Qt/PyQt · LabVIEW  
**Robotics and interfaces:** ROS/ROS 2 · Gazebo · CAN · UART · Ethernet · Arduino  
**Verification and tooling:** SIL/HIL · Test automation · Git/GitHub Actions · CI/CD · CMake · Docker  
**RF and communications:** SDR fundamentals · GNSS telemetry · SATCOM link budgets · Antenna engineering *(current coursework)*

## Education and languages

- **TUM:** M.Sc. Mechanical Engineering (Maschinenwesen), focus on Flight Control and GNC — expected 2027
- **TUM:** Graduate studies in Aerospace Engineering, 2021-2026
- **Çukurova University:** B.Sc. Mechanical Engineering and B.Sc. Automotive Engineering
- **Languages:** Turkish (native) · English (full professional proficiency) · German (B2, continuing development)

---

Interested in flight-control, GNC, state-estimation, avionics, embedded-aerospace, and RF/antenna engineering opportunities in the Munich area.
