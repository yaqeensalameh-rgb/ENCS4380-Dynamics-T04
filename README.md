# ENCS4380 – Dynamic Characteristics Interactive Toolkit

An interactive web-based toolkit developed for **ENCS4380 – Interfacing Techniques** at Birzeit University.

The project provides interactive simulations and visualizations to help students understand sensor dynamic characteristics, system responses, and PID control concepts.

## Live Demo

[Open the Interactive Toolkit](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/)

## Team Members

- Yaqeen Salameh
- Leen Badran
- Reem Tirawi
- Nora Issam

## Project Overview

This project is designed to provide an interactive learning experience for understanding the dynamic behavior of sensors and control systems.

It includes two main parts:

- **Homework 1 – Dynamic Characteristics:** Covers first-order and second-order system responses, frequency response, and sensor parameter estimation.
- **Homework 2 – PID Control:** Explores PID controllers, closed-loop systems, and the effect of sensor dynamics on control performance.

Users can adjust system parameters, run simulations, observe real-time plots, make predictions, and compare simulation results with theoretical behavior.

## How to Use the Toolkit

1. Open the Live Demo using the link provided above.
2. Select the desired homework section.
3. Choose one of the available modules or activities.
4. Adjust the system parameters using the available controls.
5. Run the simulation and observe the response curves.
6. Use the prediction activities to estimate system behavior.
7. Compare the simulation results with theoretical values and validation checks.

---

# Homework 1 – Dynamic Characteristics

## Modules

- **[Module 1 – First-Order Time Response](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/First_Order_time_Response_M1.html):** Explores step and ramp responses and the effect of the time constant (τ).

- **[Module 2 – First-Order Frequency Response](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/module2%20%282%29.html):** Demonstrates amplitude ratio, phase lag, Bode plots, and dynamic error.

- **[Module 3 – Second-Order Response](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/module3.html):** Explores damping conditions, response characteristics, poles, and state-space modeling.

- **[Module 4 – Guess the Sensor](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/module4.html):** Challenges users to estimate unknown sensor parameters from response curves.

## Validation – Homework 1

The toolkit includes all six validation checks specified in the Homework 1 instructions.

## Learning Objectives

### Module 1 – First-Order Time Response

- Understand the meaning and importance of the time constant (τ).
- Identify the 63.2% response point at t = τ.
- Understand the 95% response point at t = 3τ.
- Compare step and ramp input responses.
- Analyze the effect of τ on sensor response speed.
- Understand steady-state error and ramp lag.

### Module 2 – First-Order Frequency Response

- Understand how a first-order sensor responds to sinusoidal inputs.
- Calculate amplitude ratio and phase lag.
- Explore the relationship between input frequency and output amplitude.
- Understand the cutoff frequency (ω = 1/τ).
- Interpret Bode magnitude and phase plots.
- Calculate the dynamic error of a sensor.

### Module 3 – Second-Order Response

- Understand the effect of damping ratio (ζ) and natural frequency (ωn).
- Compare underdamped, critically damped, and overdamped responses.
- Analyze rise time, peak time, maximum overshoot, and settling time.
- Understand the relationship between system poles and response behavior.
- Explore the mass-spring-damper system using state-space representation.
- Observe the system trajectory in the phase plane.

### Module 4 – Guess the Sensor

- Identify unknown sensor characteristics from response curves.
- Estimate the time constant (τ) of a first-order system.
- Estimate the damping ratio (ζ) and natural frequency (ωn) of a second-order system.
- Use overshoot and peak time to analyze second-order responses.
- Compare estimated parameters with actual hidden values.
- Improve understanding through interactive challenges and scoring.

---

# Homework 2 – PID Control Toolkit

This section introduces interactive activities for understanding PID control and closed-loop system behavior.

## Available Activities

- **[P1 – PID Controller Playground](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/p1.html):** Explores Proportional, Integral, and Derivative control using interactive simulations, adjustable controller gains, response plots, and performance measurements.

- **[P2 – A Slow Sensor in the Loop](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/p2.html):** Demonstrates how sensor dynamics and measurement delay affect closed-loop control performance.

- **P3 – Digital PID (In Progress)**

- **P4 – PID Tuning Challenge (In Progress)**

## Learning Objectives

- Understand the role of PID controllers in feedback control systems.
- Explore the effects of proportional, integral, and derivative gains.
- Analyze the relationship between controller parameters and system response.
- Understand the difference between actual system output and sensor measurements.
- Investigate how sensor time constants affect closed-loop performance.
- Evaluate system behavior using response plots and performance metrics.

## Validation – Homework 2

The PID Control Toolkit includes three validation checks:

1. **P-only control with Kp = 9:** Closed-loop time constant of 0.1 s and steady-state error of 10%.
2. **PI control with Kp = 1 and Ki = 1:** Natural frequency of 1 rad/s and damping ratio of 1.
3. **PI control:** Zero steady-state error for a step input.

These checks are implemented in the P1 module.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Plotly.js
- GitHub
- GitHub Pages

## Work Distribution

### Homework 1

| Module | Responsible Member |
|---|---|
| Module 1 | Leen Badran |
| Module 2 | Yaqeen Salameh |
| Module 3 | Reem Tirawi |
| Module 4 | Nora Issam |

### Homework 2

| Module | Responsible Member |
|---|---|
| P1 – PID Playground | Nora Issam |
| P2 – Slow Sensor | Yaqeen Salameh |
| P3 – Digital PID | Leen Badran |
| P4 – Tuning Challenge | Reem Tirawi |

---

## AI Usage

AI tools were used for assistance with code development, debugging, understanding mathematical concepts, and improving the interactive simulations.

All implementations were reviewed and tested by the team.

---

## Screenshots

### Module 1 – First-Order Time Response

[View Module 1 Screenshot](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/Module1.png)

### Module 2 – First-Order Frequency Response

[View Screenshot 1](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/Module2_1.png)

[View Screenshot 2](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/Module2_2.png)

### Module 3 – Second-Order Response

[View Screenshot 1](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/Module3_1.png)

[View Screenshot 2](https://yaqeensalameh-rgb.github.io/ENCS4380-Dynamics-T04/Module3_2.png)

---

## Project Learning Outcomes

By completing this toolkit, users can:

- Explain the dynamic behavior of first-order and second-order systems.
- Predict sensor responses to different input signals.
- Interpret time-domain and frequency-domain characteristics.
- Estimate unknown system parameters from response curves.
- Understand PID control and closed-loop system behavior.
- Analyze the effect of sensor dynamics on control performance.
- Connect mathematical models, simulations, and real-world sensor behavior.

