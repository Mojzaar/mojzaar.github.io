---
layout: default
title: "AI & Medical Imaging Research"
project_id: "duke-phd"
description: "Ph.D. research bridging formal verification, physics-informed AI, and digital twin simulations for medical imaging."
---

<section class="section">
    <div class="section-header">
        <h2 class="section-title" style="color: #0056b3; text-transform: uppercase;">Ph.D. Research & Innovation</h2>
    </div>
    <div class="intro" style="margin-bottom: 30px;">
        <h3 style="color: #333; margin-top: 0;">Duke University (2018–2023)</h3>
        <p>My Ph.D. journey began with the rigorous mathematical verification of safety-critical autonomous systems and evolved into pioneering <strong>physics-informed AI</strong> for healthcare. By integrating <strong>Digital Twins</strong> with Deep Learning, I developed frameworks that not only analyze medical images but actively optimize how they are acquired and processed.</p>
    </div>
</section>

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">1. Formal Verification of AI-Driven Cyber-Physical Systems</h3>
    </div>
    
    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Ensuring Safety in Autonomous Systems</h4>
            <p>During the first phase of my Ph.D., I focused on the safety and reliability of complex, learning-enabled systems such as <strong>autonomous vehicles, bipedal robots, and medical devices</strong>. As these systems increasingly rely on "black-box" neural networks, guaranteeing their safety becomes critical.</p>
            
            <ul>
                <li><strong>Methodology:</strong> Developed <strong>Statistical Model Checking (SMC)</strong> algorithms to verify hyperproperties (e.g., robustness, opacity) in systems where traditional verification is computationally intractable.</li>
                <li><strong>Application:</strong> Successfully verified safety constraints for autonomous lane-keeping assist systems and bipedal robot locomotion.</li>
                <li><strong>Outcome:</strong> Created a probabilistic conformance framework that quantifies how well a physical system matches its design model under uncertainty.</li>
            </ul>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;">Y. Wang, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Probabilistic conformance for cyber-physical systems,"</em> ACM/IEEE ICCPS, 2021.</li>
                    <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"Statistical verification of learning-based cyber-physical systems,"</em> HSCC, 2020.</li>
                    <li style="margin-bottom: 8px;">Y. Wang, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Statistical verification of hyperproperties for cyber-physical systems,"</em> ACM Transactions on Embedded Computing Systems (Best Paper Finalist), 2019.</li>
                </ul>
            </div>

            <div style="margin: 20px 0; text-align: center;">
                 <video controls style="max-width: 100%; border-radius: 4px; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
                    <source src="{{ '/assets/attack.mp4' | relative_url }}" type="video/mp4">
                    Your browser does not support the video tag.
                 </video>
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Attack detection and safe control of autonomous vehicles in a simulator.</p>
            </div>
            
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">2. Prospective Optimization via Digital Twins</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Patient-Specific Imaging Protocols</h4>
            <p>Transitioning into medical imaging, I addressed the "one-size-fits-all" limitation of CT scanning protocols. Using <strong>Digital Twin</strong> technology (DukeSim), I created virtual replicas of patients to simulate thousands of imaging scenarios without radiation risk.</p>

            <ul>
                <li><strong>Innovation:</strong> Developed a Machine Learning framework that predicts the optimal scanning parameters (kVp, mAs) for a specific patient <em>before</em> the scan takes place.</li>
                <li><strong>Impact:</strong> Achieved a balance between image quality and radiation dose, ensuring diagnostic accuracy while minimizing patient exposure.</li>
            </ul>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                    <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"Multi-factorial optimization of imaging parameters for quantifying coronary stenosis in cardiac CT"</em></li>
                    <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"Coronary stenosis quantification in cardiac computed tomography angiography: multi-factorial optimization of image quality and radiation dose"</em></li>
                    <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"Protocol selection formalism for minimizing detectable differences in morphological radiomics features of lung lesions in repeated CT acquisitions,"</em> Journal of Medical Imaging, 2024.</li>
                    <li style="margin-bottom: 8px;">F.I Tushar, <strong>Mojtaba Zarei</strong>, ..., et al., <em>"Virtual NLST: towards replicating national lung screening trial"</em> Medical Imaging 2024: Physics of Medical Imaging</li>
                    <li style="margin-bottom: 8px;">F.I Tushar, <strong>Mojtaba Zarei</strong>, ..., et al., <em>"Virtual lung screening trial (VLST): An in silico study inspired by the national lung screening trial for lung cancer detection"</em>, Medical Image Analysis </li>
                </ul>
            </div>
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">3. Physics-Informed Deep Learning & Harmonization</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Image Harmonization & Material Decomposition</h4>
            <p>Medical images from different scanners often vary in texture and noise, complicating diagnosis. I developed <strong>Physics-Informed Deep Neural Networks</strong> that harmonize these images, making a scan from Scanner A look quantitatively identical to Scanner B.</p>

            <ul>
                <li><strong>Generalizability:</strong> Unlike standard "black-box" AI, I injected physics constraints (noise power spectra, modulation transfer functions) into the training process and model architecture. This ensured the model learned the underlying physics of image formation, not just dataset correlations.</li>
                <li><strong>Material Decomposition:</strong> Extended this work to spectral CT, using Deep Learning to accurately decompose images into their constituent materials (iodine, water, bone) for advanced diagnostics.</li>
            </ul>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                     <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"A truth-based primal-dual learning approach to reconstruct CT images utilizing the virtual imaging trial platform,"</em> SPIE Medical Imaging, 2022.</li>
                     <li style="margin-bottom: 8px;">J.H. Valand, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Truth-Based Physics Informed Estimation of Material Composition in Spectral CT,"</em> AAPM, 2024.</li>
                     <li style="margin-bottom: 8px;">S.J. Xia, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Evaluation of unified harmonization of CT images across multiple tasks: A step towards AI generalizability,"</em> Medical Physics, 2025.</li>
                     <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"The role of harmonization: a systematic analysis of various task-based scenarios"</em></li>
                     <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"A probabilistic conditional adversarial neural network to reduce imaging variation in radiography,"</em> SPIE Medical Imaging (Best Poster Award), 2021.</li>
                     <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"A physics-informed deep neural network for harmonization of CT images"</em></li>
                     <li style="margin-bottom: 8px;"><strong>Mojtaba Zarei</strong>, et al., <em>"Harmonizing CT images via physics-based deep neural networks"</em></li>
                </ul>
            </div>
            <div style="margin: 20px 0; text-align: center;">
                 <img src="{{ '/assets/CXR_harm.png' | relative_url }}" alt="Phase Trajectory Comparison" style="max-width: 80%; height: auto;">
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Comparison of clinical  harmonized and non-harmonized CXRs images generated by a physics-informed GAN trained solely on digital twin data.</p>
            </div>
            </div>
            <div style="margin: 20px 0; text-align: center;">
                 <img src="{{ '/assets/CT_harm.png' | relative_url }}" alt="Phase Trajectory Comparison" style="max-width: 80%; height: auto;">
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Comparison of clinical  harmonized and non-harmonized CT images generated by a physics-informed GAN trained solely on digital twin data.</p>
            </div>
            </div>
            <div style="margin: 20px 0; text-align: center;">
                 <img src="{{ '/assets/MD.png' | relative_url }}" alt="Phase Trajectory Comparison" style="max-width: 80%; height: auto;">
                 <p style="font-size: 0.9em; color: #666; font-style: italic;">Figure: Clinical material decomposition images from spectral CT generated using a physics-informed GAN trained exclusively on digital twin data.</p>
            </div>
        </div>
    </div>
</section>

<hr style="border: 0; border-top: 1px solid #eee; margin: 30px 0;">

<section class="section" style="margin-bottom: 40px;">
    <div class="section-header">
        <h3 class="section-title" style="color: #0056b3;">4. Clinical Evaluation of Next-Gen Technology</h3>
    </div>

    <div class="item">
        <div class="details">
            <h4 style="color: #000; margin-bottom: 10px;">Project: Evaluating Photon-Counting CT (Alpha PCCT)</h4>
            <p>I led the performance verification of cutting-edge imaging hardware, specifically the <strong>Photon-Counting CT (PCCT)</strong>. This technology promises higher resolution and better contrast but requires rigorous validation before clinical deployment.</p>

            <ul>
                <li><strong>Work:</strong> Designed and executed virtual clinical trials to benchmark the PCCT against conventional energy-integrating detectors.</li>
                <li><strong>Outcome:</strong> Quantified the improvements in lung and bone lesion detection and abdominal CT quantification, providing the data needed to support the adoption of this new technology.</li>
            </ul>

            <div style="margin-top: 20px;">
                <h4 style="color: #333;">Relevant Publications:</h4>
                <ul style="list-style-type: none; padding-left: 0;">
                <li style="margin-bottom: 8px;">F R. Schwartz, <strong> Mojtaba Zarei,</strong>, ... et al., <em>"Image quality of photon counting and energy integrating chest CT –Prospective head-to-head comparison on same patients ,"</em> European Journal of Radiology, 2023.</li>
                    <li style="margin-bottom: 8px;">C. McCabe, <strong> Mojtaba Zarei,</strong>, ... et al., <em>"A systematic assessment of photon-counting CT for bone mineral density and microarchitecture quantifications,"</em> SPIE Medical Imaging, 2023.</li>
                    <li style="margin-bottom: 8px;">C. McCabe, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Optimization of imaging parameters of an investigational photon-counting CT prototype for lung lesion radiomics,"</em> SPIE Medical Imaging, 2022.</li>
                    <li style="margin-bottom: 8px;">C. McCabe, <strong>Mojtaba Zarei</strong>, ... et al., <em>"The potential of photon-counting CT for the improved precision of lung nodule radiomics,"</em> Physics in Medicine & Biology, 2025.</li>
                    <li style="margin-bottom: 8px;">J.R. Rajagopal, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Technology characterization through diverse evaluation methodologies: application to thoracic imaging in photon-counting computed tomography,"</em> Journal of Thoracic Imaging, 2024.</li>
                    <li style="margin-bottom: 8px;">F. Ria, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Performance assessment of photon counting versus energy integrated CT: concordance of in vivo and phantom measurements,"</em> SPIE Medical Imaging, 2024.</li>
                    <li style="margin-bottom: 8px;">L. Lofino, <strong>Mojtaba Zarei</strong>, ..., et al., <em>"Comparison of image quality of abdominal CT examinations and virtual noncontrast images between photon-counting and energy-integrating detector CT"</em> RSNA 2023</li>
                    <li style="margin-bottom: 8px;">F. Ria, <strong>Mojtaba Zarei</strong>, ... et al., <em>"Evaluation and extension of in vivo detectability index to deep-learning and photon counting CT techniques,"</em> RSNA, 2022.</li>
                    <li style="margin-bottom: 8px;">J. Rajagopal, <strong>Mojtaba Zarei</strong>, ..., et al., <em>"Impact of image formation factors on material discrimination in spectral CT"</em></li>
                </ul>
            </div>
        </div>
    </div>
</section>
