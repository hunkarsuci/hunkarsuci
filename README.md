# Hünkar Suci

**M.Sc. Mechanical Engineering student at the Technical University of Munich**

I focus on guidance, navigation and control (GNC), flight dynamics, state estimation, and testable aerospace software. I build physics-based simulations, control systems, estimation algorithms, and embedded prototypes using Python, MATLAB/Simulink, and C/C++.

📍 Munich, Germany · [LinkedIn](https://www.linkedin.com/in/hunkar-suci)

## Engineering focus

- **Guidance, navigation and control** — modeling, trim, linearization, feedback control, and closed-loop evaluation
- **Flight dynamics and control systems** — nonlinear and linear aircraft models, actuator dynamics, PID/LQR, and response analysis
- **State estimation and sensor fusion** — Kalman filtering, error-state estimation, IMU/GPS/barometer models, and numerical verification
- **Embedded software** — C/C++, Arduino, deterministic and testable engineering code
- **Avionics foundations** — currently expanding my knowledge of ROS 2 integration, RF systems, and antenna engineering

## Selected engineering work

| Project | Engineering evidence | Scope |
| --- | --- | --- |
| [Generic delta-canard 6DOF](https://github.com/hunkarsuci/generic_delta_canard_fighter_6dof) | Nonlinear rigid-body dynamics, trim, numerical linearization, PID/LQR, actuator models, CI, and validation matrix | Generic research model with synthetic aerodynamic and propulsion data |
| [Drone error-state Kalman filter](https://github.com/hunkarsuci/KF_Implementation_for_Drone) | IMU prediction, GPS/barometer updates, quaternion attitude, deterministic metrics, and Jacobian checks | Synthetic sensors; no flight-data validation |
| [Lateral-directional FCS](https://github.com/hunkarsuci/F16-Inspired-Lateral-Directional-FCS) | State feedback, command shaping, actuator limits, closed-loop simulation, and automated tests | Simplified teaching model; not an aircraft-qualified control law |
| [3D quadcopter simulation](https://github.com/hunkarsuci/3d-quadcopter-simulation) | Newton–Euler dynamics, RK4 integration, cascaded PID control, waypoint tracking, telemetry, and CI | Educational simulation with synthetic scenarios |
| [32×32 cable tester](https://github.com/hunkarsuci/32x32-Cable-Tester) | Arduino firmware, multiplexer-based continuity scanning, wiring documentation, and fault classification | Prototype design; physical verification report is still planned |

## How I work

I aim to make engineering assumptions reviewable: coordinate frames and units, actuator and sensor limits, numerical checks, reproducible scenarios, and the distinction between simulated performance and measured performance. My repositories document what their tests verify—and what they do not.

## Current development

I am strengthening my embedded C++ and ROS 2 skills through project-based work, with the goal of connecting flight-control and estimation algorithms to modular, testable avionics software. In parallel, I am developing my RF and antenna fundamentals as part of my current coursework.

**Core tools:** Python · NumPy · SciPy · MATLAB/Simulink · C/C++ · Arduino · pytest · GitHub Actions

---

Interested in GNC, flight-control, state-estimation, avionics, and embedded aerospace engineering opportunities in the Munich area.
