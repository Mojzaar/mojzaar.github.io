---
layout: default
title: "Robotics & Control Systems"
project_id: "tehran-masters"
description: "M.Sc. research focused on telerobotics, motion planning, non-linear control, and haptic systems."
---

# Robotics & Control Research
**University of Tehran (2014–2017)**

During my Master's at the Human & Robot Interaction Lab (TaarLab), I led R&D initiatives spanning telerobotics, control theory, and mechatronic design. Below are the key projects and their associated publications.

---

## 1. Telerobotics, Shared Control & Motion Planning
**Project:** Shared-control of a Mobile Robot via Haptic Feedback

This project addressed the challenge of operating mobile robots in dynamic environments where time delays and obstacles compromise safety. I developed a **shared-control architecture** where a human operator controls the robot via a haptic device, but the robot's autonomy (Motion Planning) intervenes to avoid collisions.

* **Motion Planning:** Developed a geometric-based motion planning algorithm (Receding Horizon Control) that navigates unknown environments.
* **Key Innovation:** Synergized impedance control with convex optimization to blend human input with autonomous safety constraints.
* **Outcome:** The system successfully navigated dynamic environments with moving obstacles.

<div class="project-media">
  <h4>Experimental Demo: Shared Control</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/shared.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Experimental validation of the shared-control framework avoiding dynamic obstacles.</em></p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Mobile Robot Navigation</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/motion1.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Experimental validation of the motion planning for a single mobile robot.</em></p>
</div>

**Relevant Publications:**
* **M. Zarei**, N. Kashi, M. Tale Masouleh, A. Kalhor, *"Experimental Study on Shared-control of a Mobile Robot with a Haptic Device by a Synergy of Receding Horizon, Convex Optimization and Impedance Control Concept,"* Journal of Intelligent & Robotic Systems, 2020. (Featured on Cover)
* **M. Zarei**, et al., *"Experimental study on optimal motion planning of wheeled mobile robot using convex optimization and receding horizon concept."*
* **M. Zarei**, et al., *"An optimal motion planning and obstacle avoidance algorithm based on the finite time velocity obstacle approach."*
* **M. Zarei**, et al., *"Motion planning of mobile robots in the unknown circumstances based on the receding horizon control and velocity obstacle concepts."*
* **M. Zarei**, et al., *"Vision based control and simulation of a spherical rolling robot based on ROS and Gazebo."*

---

## 2. Non-Linear Control Theory
**Project:** Oscillation Damping & Arc Length Method

We introduced a novel mathematical concept—the **Arc Length Function**—to estimate the Domain of Attraction (DA) for non-linear control systems. By minimizing the arc length of the system's phase trajectory, we could design controllers that significantly reduced oscillation.

* **Contribution:** Proved that minimizing trajectory length correlates with faster settling times and reduced overshoot.
* **Application:** Validated on cable-driven parallel robots and haptic devices to suppress unwanted vibrations.


<div class="project-media">
  <img src="{{ '/assets/DoA.png' | relative_url }}" alt="Phase Trajectory Comparison" style="width:100%; max-width:600px;">
  <p><em>Figure: Estimated DoA for different nonlinear systems.</em></p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Oscillation Damping (Cable Robot)</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/MocVSIAE.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Experimental oscillation damping controller for cable parallel robots.</em></p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Oscillation Damping (Delta Robot)</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/Moc1.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Experimental oscillation damping controller for delta parallel robots.</em></p>
</div>


**Relevant Publications:**
* **M. Zarei**, A. Kalhor, D. Brake, *"Arc length based maximal Lyapunov functions and domains of attraction estimation for polynomial nonlinear systems,"* Automatica, 2018.
* **M. Zarei**, A. Aflakian, A. Kalhor, M. Tale Masouleh, *"Oscillation damping of nonlinear control systems based on the phase trajectory length concept: An experimental case study on a cable-driven parallel robot,"* Mechanism and Machine Theory, 2018.
* **M. Zarei**, A. Kalhor, M. Tale Masouleh, *"An experimental phase trajectory length based oscillation damping impedance control for Novint Falcon haptic device,"* Journal of Mechanical Engineering Science, 2018.
* **M. Zarei**, A. Kalhor, M. Rastegar, *"Employing phase trajectory length concept as performance index in linear power oscillation damping controllers,"* International Journal of Electrical Power & Energy Systems, 2017.
* **M. Zarei**, K. Javadi, A. Kalhor, *"Perturbed tumor immunotherapy domain of attraction estimation via the arc-length function,"* International Iranian Conference on Biomedical Engineering (ICBME), 2018.
* S. Ansari-Rad, **M. Zarei**, et al., *"Stabilization of a two-dof spherical parallel robot via a novel adaptive approach,"* International Conference on Robotics and Mechatronics, 2018.

---

## 3. Virtual Reality Dentistry Simulator
**Project:** National Grand Project for Dental Training

I served as a lead control and CAD engineer for a national initiative to build a **haptic-enabled VR dentistry trainer**. The goal was to allow dental students to "feel" the difference between tooth enamel, decay, and gum tissue during virtual drilling procedures.

To achieve realistic force feedback, we required a highly accurate dynamic model of the haptic device. I led the identification process to derive these parameters.

* **Role:** Designed the mechanical structure of the haptic stylus and implemented the control loops.
* **Tech Stack:** C++, SolidWorks, Haptic Rendering Algorithms.

<div class="project-media">
  <img src="{{ '/assets/Picture1.jpg' | relative_url }}" alt="Phase Trajectory Comparison" style="width:100%; max-width:600px;">
  <p><em>Figure: Modified end effectors of the haptic device.</em></p>
</div>

<div class="project-media">
  <h4>Experimental Demo: VR Dentistry</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/Vr.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Virtual reality environment for dentistry training.</em></p>
</div>

**Relevant Publications:**
* N. Karbasizadeh, **M. Zarei**, A. Aflakian, M. Tale Masouleh, A. Kalhor, *"Experimental dynamic identification and model feed-forward control of Novint Falcon haptic device,"* Mechatronics, 2018.

---

## 4. Parallel Robot Design
**Project:** Design and Manufacture of the ThesseraTaar/QuattroTaar Robot

We designed and operationalized a novel parallel robot. Parallel robots offer high precision and speed but are complex to control due to their closed-loop kinematics. This project involved the full lifecycle from optimal mechanical design to fabrication and control.

* **Achievement:** Successfully patented the mechanical design. The robot featured a unique kinematic structure optimized for pick-and-place operations.
* **Work:** Performed kinematic analysis, mechanical manufacturing, and real-time control implementation using ABC and PSO algorithms.

<div class="project-media">
  <h4>Experimental Demo: 4-DOF Delta Robot</h4>
  <video width="100%" controls>
    <source src="{{ '/assets/delta.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>Video: Designed and manufactured robot in action.</em></p>
</div>

**Relevant Publications:**
* **M. Zarei**, et al., *"Optimal design and fabrication of a 4-dof quattrotaar parallel robot with singularity-free workspace by ABC and PSO algorithms."*
