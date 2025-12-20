---
layout: default
title: "Robotics & Control Systems"
project_id: "tehran-masters"
description: "M.Sc. research focused on telerobotics, non-linear control theory, and haptic systems."
---

# Robotics & Control Research
**University of Tehran (2014–2017)**

During my Master's at the Human & Robot Interaction Lab (TaarLab), I led R&D initiatives spanning telerobotics, control theory, and mechatronic design. Below are the key projects and their associated publications.

---

## 1. Telerobotics & Shared Control (Master's Thesis)
**Project:** Shared-control of a Mobile Robot via Haptic Feedback

This project addressed the challenge of operating mobile robots in dynamic environments where time delays and obstacles compromise safety. I developed a **shared-control architecture** where a human operator controls the robot via a haptic device, but the robot's autonomy (Model Predictive Control) intervenes to avoid collisions.

* **Key Innovation:** Used a Receding Horizon Control (RHC) approach combined with impedance control to blend human input with autonomous safety constraints.
* **Outcome:** The system successfully navigated unknown environments with moving obstacles. This work was featured on the cover of the *Journal of Intelligent & Robotic Systems*.

<div class="project-media">
  <h4>Experimental Demo</h4>
  <video width="100%" controls poster="/assets/poster-teleop.jpg">
    <source src="/assets/tehran-teleoperation.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Experimental validation of the shared-control framework avoiding dynamic obstacles.</em></p>
</div>

**Relevant Publications:**
* **M. [cite_start]Zarei**, N. Kashi, M. Tale Masouleh, A. Kalhor, *"Experimental Study on Shared-control of a Mobile Robot with a Haptic Device by a Synergy of Receding Horizon, Convex Optimization and Impedance Control Concept,"* Journal of Intelligent & Robotic Systems, 2020. (Featured on Cover) 

---

## 2. Non-Linear Control Theory
**Project:** Oscillation Damping & Arc Length Method

We introduced a novel mathematical concept—the **Arc Length Function**—to estimate the Domain of Attraction (DA) for non-linear control systems. By minimizing the arc length of the system's phase trajectory, we could design controllers that significantly reduced oscillation.

* **Contribution:** Proved that minimizing trajectory length correlates with faster settling times and reduced overshoot.
* **Application:** Validated on cable-driven parallel robots and haptic devices to suppress unwanted vibrations.

<div class="project-media">
  <img src="/assets/arclength-plot.png" alt="Phase Trajectory Comparison" style="width:100%; max-width:600px;">
  <p><em>Figure: Comparison of phase trajectories showing the reduced oscillation achieved by our proposed controller (blue) vs. standard methods (red).</em></p>
</div>

**Relevant Publications:**
* **M. [cite_start]Zarei**, A. Kalhor, D. Brake, *"Arc length based maximal Lyapunov functions and domains of attraction estimation for polynomial nonlinear systems,"* Automatica, 2018. [cite: 110]
* **M. [cite_start]Zarei**, A. Aflakian, A. Kalhor, M. Tale Masouleh, *"Oscillation damping of nonlinear control systems based on the phase trajectory length concept: An experimental case study on a cable-driven parallel robot,"* Mechanism and Machine Theory, 2018. [cite: 111]
* **M. [cite_start]Zarei**, A. Kalhor, M. Tale Masouleh, *"An experimental phase trajectory length based oscillation damping impedance control for Novint Falcon haptic device,"* Journal of Mechanical Engineering Science, 2018. [cite: 113]
* **M. Zarei**, A. Kalhor, M. Rastegar, *"Employing phase trajectory length concept as performance index in linear power oscillation damping controllers,"* International Journal of Electrical Power & Energy Systems, 2017.

---

## 3. Virtual Reality Dentistry Simulator
**Project:** National Grand Project for Dental Training

I served as a lead control and CAD engineer for a national initiative to build a **haptic-enabled VR dentistry trainer**. The goal was to allow dental students to "feel" the difference between tooth enamel, decay, and gum tissue during virtual drilling procedures.

To achieve realistic force feedback, we required a highly accurate dynamic model of the haptic device. I led the identification process to derive these parameters.

* **Role:** Designed the mechanical structure of the haptic stylus and implemented the control loops.
* **Tech Stack:** C++, SolidWorks, Haptic Rendering Algorithms.

<div class="project-media">
  <img src="/assets/dentistry-sim.jpg" alt="Virtual Dentistry Haptic Device" style="width:100%; max-width:600px;">
  <p><em>Figure: The custom-designed haptic interface used for virtual dental surgery training.</em></p>
</div>

**Relevant Publications:**
* N. Karbasizadeh, **M. [cite_start]Zarei**, A. Aflakian, M. Tale Masouleh, A. Kalhor, *"Experimental dynamic identification and model feed-forward control of Novint Falcon haptic device,"* Mechatronics, 2018. 

---

## 4. Parallel Robot Design
**Project:** Design and Manufacture of the ThesseraTaar/QuattroTaar Robot

We designed and operationalized a novel parallel robot. Parallel robots offer high precision and speed but are complex to control due to their closed-loop kinematics. This project involved the full lifecycle from optimal mechanical design to fabrication and control.

* **Achievement:** Successfully patented the mechanical design. The robot featured a unique kinematic structure optimized for pick-and-place operations.
* **Work:** Performed kinematic analysis, mechanical manufacturing, and real-time control implementation using ABC and PSO algorithms.

<div class="project-media">
  <h4>Robot in Action</h4>
  <video width="100%" controls>
    <source src="/assets/thesserataar-demo.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

**Relevant Publications:**
* **M. Zarei**, et al., *"Optimal design and fabrication of a 4-dof quattrotaar parallel robot with singularity-free workspace by ABC and PSO algorithms."*
