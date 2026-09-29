# Hünkar Suci

Aerospace and mechanical engineer in Munich, focused on flight dynamics, guidance and control, state estimation, and testable aerospace software.

M.Sc. Aerospace and Mechanical Engineering, Technical University of Munich · [LinkedIn](https://www.linkedin.com/in/hunkar-suci)

## Selected engineering work

| Project | What to inspect | Scope |
| --- | --- | --- |
| [Generic delta-canard 6DOF](https://github.com/hunkarsuci/generic_delta_canard_fighter_6dof) | Rigid-body model, trim, linearization, control studies, and validation matrix | Generic research model; see its documented assumptions |
| [Drone error-state Kalman filter](https://github.com/hunkarsuci/KF_Implementation_for_Drone) | IMU prediction, GPS/barometer updates, deterministic evaluation, Jacobian checks | Synthetic sensors; no flight-data validation |
| [Lateral-directional FCS](https://github.com/hunkarsuci/F16-Inspired-Lateral-Directional-FCS) | State feedback, command shaping, actuator limits, and tests | Simplified F-16-inspired linear model, not aircraft-qualified |
| [B747 longitudinal C* control](https://github.com/hunkarsuci/b747-longitudinal-cstar-control) | Fixed-trim state-space model, C* command, response metrics | Illustrative model and simulation, not identified aircraft data |
| [Hydraulic-servo actuator dynamics](https://github.com/hunkarsuci/Hydraulic-Servo-Actuator-Dynamics) | Second-order response with acceleration, rate, and travel limits | No hydraulic pressure or hardware calibration |

I like making the assumptions visible: coordinate frames and units, actuator and sensor limits, numerical checks, and the difference between a simulation result and measured performance. The repositories include run instructions and describe what their tests actually cover.

For embedded work, [32×32 Cable Tester](https://github.com/hunkarsuci/32x32-Cable-Tester) contains firmware and wiring notes for a cable continuity matrix. Hardware verification is still needed.

**Tools used across these projects:** Python, NumPy, SciPy, MATLAB/Simulink, C/C++, Arduino, pytest, and GitHub Actions. My current focus is estimation and control software that can be reproduced and reviewed from the model through the tests.
