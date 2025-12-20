---
layout: default
title: "Robotics & Control Systems"
project_id: "tehran-masters"
description: "M.Sc. research focused on telerobotics, motion planning, non-linear control, and haptic systems."
---

<section class="section">
    <div class="section-header">
        <h2 class="section-title" style="color: #0056b3; text-transform: uppercase;">Robotics & Control Research</h2>
    </div>
    <div class="intro" style="margin-bottom: 30px;">
        <h3 style="color: #333; margin-top: 0;">University of Tehran (2014–2017)</h3>
        <p>During my Master's at the Human & Robot Interaction Lab (TaarLab), I led R&D initiatives spanning telerobotics, control theory, and mechatronic design.</p>
    </div>
</section>

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">1. Telerobotics, Shared Control & Motion Planning</h3>
    </div>
    
    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Shared-control of a Mobile Robot via Haptic Feedback</h4>
            <p>This project addressed the challenge of operating mobile robots in dynamic environments where time delays and obstacles compromise safety. I developed a <strong>shared-control architecture</strong> where a human operator controls the robot via a haptic device, but the robot's autonomy (Motion Planning) intervenes to avoid collisions.</p>
            
            <ul>
                <li><strong>Motion Planning:</strong> Developed a geometric-based motion planning algorithm (Receding Horizon Control) that navigates unknown environments.</li>
                <li><strong>Key Innovation:</strong> Synergized impedance control with convex optimization to blend human input with autonomous safety constraints.</li>
                <li><strong>Outcome:</strong> The system successfully navigated dynamic environments with moving obstacles.</li>
            </ul>

            <div style="margin: 20px 0; text-align: center;">
             <img src="{{ '/assets/Presentation2.png' | relative_url }}" alt="Phase Trajectory Comparison" style="max-width: 80%; height: auto;">
             <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Schematic of deployed teleoperation.</p>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/shared.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Experimental validation of the shared-control framework avoiding dynamic obstacles.</p>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/motion1.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Experimental validation of the motion planning for a single mobile robot.</p>
            </div>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, N. Kashi, M. Tale Masouleh, A. Kalhor, <em>"Experimental Study on Shared-control of a Mobile Robot with a Haptic Device by a Synergy of Receding Horizon, Convex Optimization and Impedance Control Concept,"</em> Journal of Intelligent & Robotic Systems, 2020. (Featured on Cover)</li>
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, et al., <em>"Experimental study on optimal motion planning of wheeled mobile robot using convex optimization and receding horizon concept."</em></li>
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, et al., <em>"An optimal motion planning and obstacle avoidance algorithm based on the finite time velocity obstacle approach."</em></li>
                </ul>
            </div>
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">2. Non-Linear Control Theory</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Oscillation Damping & Arc Length Method</h4>
            <p>We introduced a novel mathematical concept—the <strong>Arc Length Function</strong>—to estimate the Domain of Attraction (DA) for non-linear control systems. By minimizing the arc length of the system's phase trajectory, we could design controllers that significantly reduced oscillation.</p>

            <ul>
                <li><strong>Contribution:</strong> Proved that minimizing trajectory length correlates with faster settling times and reduced overshoot.</li>
                <li><strong>Application:</strong> Validated on cable-driven parallel robots and haptic devices to suppress unwanted vibrations.</li>
            </ul>

            <div style="margin: 20px 0; text-align: center;">
                 <img src="{{ '/assets/DoA.png' | relative_url }}" alt="Phase Trajectory Comparison" style="max-width: 80%; height: auto;">
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Estimated DoA for different nonlinear systems.</p>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/MocVSIAE.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Experimental oscillation damping controller for cable parallel robots.</p>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/Moc1.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Experimental oscillation damping controller for delta parallel robots.</p>
            </div>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, A. Kalhor, D. Brake, <em>"Arc length based maximal Lyapunov functions and domains of attraction estimation for polynomial nonlinear systems,"</em> Automatica, 2018.</li>
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, A. Aflakian, A. Kalhor, M. Tale Masouleh, <em>"Oscillation damping of nonlinear control systems based on the phase trajectory length concept,"</em> Mechanism and Machine Theory, 2018.</li>
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, A. Kalhor, M. Tale Masouleh, <em>"An experimental phase trajectory length based oscillation damping impedance control for Novint Falcon haptic device,"</em> Journal of Mechanical Engineering Science, 2018.</li>
                    <li style="margin-bottom: 8px;">S. Ansari-Rad, <strong>M. Zarei</strong>, et al., <em>"Stabilization of a two-dof spherical parallel robot via a novel adaptive approach,"</em> International Conference on Robotics and Mechatronics, 2018.</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">3. Virtual Reality Dentistry Simulator</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: National Grand Project for Dental Training</h4>
            <p>I served as a lead control and CAD engineer for a national initiative to build a <strong>haptic-enabled VR dentistry trainer</strong>. The goal was to allow dental students to "feel" the difference between tooth enamel, decay, and gum tissue during virtual drilling procedures.</p>

            <ul>
                <li><strong>Role:</strong> Designed the mechanical structure of the haptic stylus and implemented the control loops.</li>
                <li><strong>Tech Stack:</strong> C++, SolidWorks, Haptic Rendering Algorithms.</li>
            </ul>

            <div style="margin: 20px 0; text-align: center;">
                 <img src="{{ '/assets/Picture1.jpg' | relative_url }}" alt="Haptic Device End Effectors" style="max-width: 80%; height: auto;">
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Modified end effectors of the haptic device.</p>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/Vr.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Virtual reality environment for dentistry training.</p>
            </div>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;">N. Karbasizadeh, <strong>M. Zarei</strong>, A. Aflakian, M. Tale Masouleh, A. Kalhor, <em>"Experimental dynamic identification and model feed-forward control of Novint Falcon haptic device,"</em> Mechatronics, 2018.</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">4. Parallel Robot Design</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Design and Manufacture of the ThesseraTaar/QuattroTaar Robot</h4>
            <p>We designed and operationalized a novel parallel robot. Parallel robots offer high precision and speed but are complex to control due to their closed-loop kinematics. This project involved the full lifecycle from optimal mechanical design to fabrication and control.</p>

            <ul>
                <li><strong>Achievement:</strong> Successfully patented the mechanical design. The robot featured a unique kinematic structure optimized for pick-and-place operations.</li>
                <li><strong>Work:</strong> Performed kinematic analysis, mechanical manufacturing, and real-time control implementation using ABC and PSO algorithms.</li>
            </ul>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/delta.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Designed and manufactured robot in action.</p>
            </div>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;"><strong>M. Zarei</strong>, et al., <em>"Optimal design and fabrication of a 4-dof quattrotaar parallel robot with singularity-free workspace by ABC and PSO algorithms."</em></li>
                </ul>
            </div>
        </div>
    </div>
</section>
