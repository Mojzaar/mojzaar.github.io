---
layout: default
title: "Robotics & Control Systems"
project_id: "tehran-masters"
description: "M.Sc. research focused on telerobotics, motion planning, non-linear control, and haptic systems."
---

<style>
  /* Container for each project to give it a 'card' look */
  .project-card {
    background-color: #fff; /* White background */
    border: 1px solid #e0e0e0; /* Subtle border */
    border-radius: 8px; /* Rounded corners */
    padding: 25px;
    margin-bottom: 40px; /* Space between projects */
    box-shadow: 0 4px 6px rgba(0,0,0,0.05); /* Soft shadow */
  }

  /* Dark mode support (if your theme uses it) */
  @media (prefers-color-scheme: dark) {
    .project-card {
      background-color: #2d2d2d;
      border-color: #444;
      color: #e0e0e0;
    }
  }

  /* Typography tweaks */
  .project-card h2 {
    margin-top: 0;
    font-size: 1.5rem;
    color: #2b579a; /* Use a nice blue or theme color */
    border-bottom: 2px solid #f0f0f0;
    padding-bottom: 10px;
    margin-bottom: 15px;
  }
  
  .project-card h4 {
    margin-top: 15px;
    font-weight: 600;
  }

  /* Media container styling */
  .project-media {
    text-align: center; /* Centers the content */
    margin: 20px 0;
    padding: 10px;
    background: rgba(0,0,0,0.03); /* Very light gray background for media area */
    border-radius: 8px;
  }

  /* Style the video/images themselves */
  .project-media video, 
  .project-media img {
    max-width: 80%; /* Only take up 80% of width */
    height: auto;
    border-radius: 6px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2); /* Shadow for depth */
    display: inline-block;
  }
  
  /* Caption text */
  .project-media p {
    font-size: 0.9em;
    color: #666;
    margin-top: 8px;
    font-style: italic;
  }
</style>

# Robotics & Control Research
**University of Tehran (2014–2017)**

During my Master's at the Human & Robot Interaction Lab (TaarLab), I led R&D initiatives spanning telerobotics, control theory, and mechatronic design.

---

<div class="project-card">

<h2>1. Telerobotics, Shared Control & Motion Planning</h2>

**Project:** Shared-control of a Mobile Robot via Haptic Feedback

This project addressed the challenge of operating mobile robots in dynamic environments where time delays and obstacles compromise safety. I developed a **shared-control architecture** where a human operator controls the robot via a haptic device, but the robot's autonomy (Motion Planning) intervenes to avoid collisions.

* **Motion Planning:** Developed a geometric-based motion planning algorithm (Receding Horizon Control) that navigates unknown environments.
* **Key Innovation:** Synergized impedance control with convex optimization to blend human input with autonomous safety constraints.
* **Outcome:** The system successfully navigated dynamic environments with moving obstacles.

<div class="project-media">
  <h4>Experimental Demo: Shared Control</h4>
  <video controls>
    <source src="{{ '/assets/shared.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Experimental validation of the shared-control framework avoiding dynamic obstacles.</p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Mobile Robot Navigation</h4>
  <video controls>
    <source src="{{ '/assets/motion1.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Experimental validation of the motion planning for a single mobile robot.</p>
</div>

**Relevant Publications:**
* **M. Zarei**, N. Kashi, M. Tale Masouleh, A. Kalhor, *"Experimental Study on Shared-control of a Mobile Robot with a Haptic Device by a Synergy of Receding Horizon, Convex Optimization and Impedance Control Concept,"* Journal of Intelligent & Robotic Systems, 2020. (Featured on Cover)
* **M. Zarei**, et al., *"Experimental study on optimal motion planning of wheeled mobile robot using convex optimization and receding horizon concept."*
* **M. Zarei**, et al., *"An optimal motion planning and obstacle avoidance algorithm based on the finite time velocity obstacle approach."*
* **M. Zarei**, et al., *"Motion planning of mobile robots in the unknown circumstances based on the receding horizon control and velocity obstacle concepts."*
* **M. Zarei**, et al., *"Vision based control and simulation of a spherical rolling robot based on ROS and Gazebo."*

</div>

<div class="project-card">

<h2>2. Non-Linear Control Theory</h2>

**Project:** Oscillation Damping & Arc Length Method

We introduced a novel mathematical concept—the **Arc Length Function**—to estimate the Domain of Attraction (DA) for non-linear control systems. By minimizing the arc length of the system's phase trajectory, we could design controllers that significantly reduced oscillation.

* **Contribution:** Proved that minimizing trajectory length correlates with faster settling times and reduced overshoot.
* **Application:** Validated on cable-driven parallel robots and haptic devices to suppress unwanted vibrations.

<div class="project-media">
  <img src="{{ '/assets/DoA.png' | relative_url }}" alt="Phase Trajectory Comparison">
  <p>Figure: Estimated DoA for different nonlinear systems.</p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Oscillation Damping (Cable Robot)</h4>
  <video controls>
    <source src="{{ '/assets/MocVSIAE.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Experimental oscillation damping controller for cable parallel robots.</p>
</div>

<div class="project-media">
  <h4>Experimental Demo: Oscillation Damping (Delta Robot)</h4>
  <video controls>
    <source src="{{ '/assets/Moc1.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Experimental oscillation damping controller for delta parallel robots.</p>
</div>

**Relevant Publications:**
* **M. Zarei**, A. Kalhor, D. Brake, *"Arc length based maximal Lyapunov functions and domains of attraction estimation for polynomial nonlinear systems,"* Automatica, 2018.
* **M. Zarei**, A. Aflakian, A. Kalhor, M. Tale Masouleh, *"Oscillation damping of nonlinear control systems based on the phase trajectory length concept: An experimental case study on a cable-driven parallel robot,"* Mechanism and Machine Theory, 2018.
* **M. Zarei**, A. Kalhor, M. Tale Masouleh, *"An experimental phase trajectory length based oscillation damping impedance control for Novint Falcon haptic device,"* Journal of Mechanical Engineering Science, 2018.
* **M. Zarei**, A. Kalhor, M. Rastegar, *"Employing phase trajectory length concept as performance index in linear power oscillation damping controllers,"* International Journal of Electrical Power & Energy Systems, 2017.
* **M. Zarei**, K. Javadi, A. Kalhor, *"Perturbed tumor immunotherapy domain of attraction estimation via the arc-length function,"* International Iranian Conference on Biomedical Engineering (ICBME), 2018.
* S. Ansari-Rad, **M. Zarei**, et al., *"Stabilization of a two-dof spherical parallel robot via a novel adaptive approach,"* International Conference on Robotics and Mechatronics, 2018.

</div>

<div class="project-card">

<h2>3. Virtual Reality Dentistry Simulator</h2>

**Project:** National Grand Project for Dental Training

I served as a lead control and CAD engineer for a national initiative to build a **haptic-enabled VR dentistry trainer**. The goal was to allow dental students to "feel" the difference between tooth enamel, decay, and gum tissue during virtual drilling procedures.

To achieve realistic force feedback, we required a highly accurate dynamic model of the haptic device. I led the identification process to derive these parameters.

* **Role:** Designed the mechanical structure of the haptic stylus and implemented the control loops.
* **Tech Stack:** C++, SolidWorks, Haptic Rendering Algorithms.

<div class="project-media">
  <img src="{{ '/assets/Picture1.jpg' | relative_url }}" alt="Haptic Device End Effectors">
  <p>Figure: Modified end effectors of the haptic device.</p>
</div>

<div class="project-media">
  <h4>Experimental Demo: VR Dentistry</h4>
  <video controls>
    <source src="{{ '/assets/Vr.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Virtual reality environment for dentistry training.</p>
</div>

**Relevant Publications:**
* N. Karbasizadeh, **M. Zarei**, A. Aflakian, M. Tale Masouleh, A. Kalhor, *"Experimental dynamic identification and model feed-forward control of Novint Falcon haptic device,"* Mechatronics, 2018.

</div>

<div class="project-card">

<h2>4. Parallel Robot Design</h2>

**Project:** Design and Manufacture of the ThesseraTaar/QuattroTaar Robot

We designed and operationalized a novel parallel robot. Parallel robots offer high precision and speed but are complex to control due to their closed-loop kinematics. This project involved the full lifecycle from optimal mechanical design to fabrication and control.

* **Achievement:** Successfully patented the mechanical design. The robot featured a unique kinematic structure optimized for pick-and-place operations.
* **Work:** Performed kinematic analysis, mechanical manufacturing, and real-time control implementation using ABC and PSO algorithms.

<div class="project-media">
  <h4>Experimental Demo: 4-DOF Delta Robot</h4>
  <video controls>
    <source src="{{ '/assets/delta.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Designed and manufactured robot in action.</p>
</div>

**Relevant Publications:**
* **M. Zarei**, et al., *"Optimal design and fabrication of a 4-dof quattrotaar parallel robot with singularity-free workspace by ABC and PSO algorithms."*

</div>
