---
layout: default
title: "Open Challenges and Emerging Opportunities<br>in Robot Control"
description: "ECC 2026 Workshop - Reykjavík, Iceland"
date: "Tuesday, July 7th 08:30-16:25"
venue: "Uni 5"
---

<div id="custom-header-logos" class="custom-header-logos">
  <a href="https://ecc26.euca-ecc.org/" target="_blank" rel="noopener noreferrer">
    <img src="assets/logos/ecc26.svg" alt="ECC 2026">
  </a>
  <a href="https://ieee-ras-robot-control.github.io/" target="_blank" rel="noopener noreferrer">
    <img src="assets/logos/robot_control_tc_white.svg" alt="TC">
  </a>
</div>

<script>
  // This script waits for the page to load, then moves the logos inside the Cayman green header
  document.addEventListener("DOMContentLoaded", function() {
    var pageHeader = document.querySelector('.page-header');
    var logos = document.getElementById('custom-header-logos');
    if (pageHeader && logos) {
      pageHeader.appendChild(logos);
    }
  });
</script>

## About the Workshop
Robot control has matured into a rich and diverse discipline, yet its intellectual coherence is increasingly strained by fragmentation across paradigms, application domains, and publication venues. Classical problems stability under interaction, modeling uncertainty, underactuation, hybrid dynamics, etc. are often treated as "solved" by practitioners, yet they persistently reappear in modern robotic systems operating in contact-rich, uncertain, and learning-enabled environments. 

At the same time, new challenges and opportunities are emerging, ranging from unconventional robotic platforms (e.g., soft and biohybrid robots) to the growing role of machine learning and large-scale physical data. This workshop provides a focused forum to reassess which problems in robot control remain fundamentally open, how their formulation has evolved with advances in hardware, autonomy, and learning, and which challenges genuinely require new control-theoretic perspectives rather than incremental refinements. The emphasis is on conceptual clarity, modeling assumptions, and the limits of existing methods, rather than polished experimental performance.

## Objectives
The objectives are threefold:
* To collectively articulate the most pressing open challenges for control in robotics, across systems, paradigms, and application domains.
* To clarify how recent technological and conceptual advances reshape both long-standing and emerging control problems.
* To strengthen intellectual cohesion across the control and robotics communities by fostering dialogue grounded in shared concepts and explicit problem formulation.

## Target Audience
The workshop targets researchers in control and robotics whose work engages with the modeling, analysis, and control of complex robotic systems, particularly in settings involving physical interaction, uncertainty, hybrid behavior, and learning-enabled components. It is especially relevant for those interested in the foundations of robotics control, the limits of existing frameworks, and the formulation of new problems arising from emerging robotic platforms and technologies.

## Invited Speakers

<!-- ### Early to Mid Career -->
<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/speakers/early_mid/laura.jpg" alt="Laura Ferranti" class="profile-image">
    <div class="profile-info">
      <h3>Laura Ferranti</h3>
      <h4>Delft University of Technology, Netherlands</h4>
      <!-- <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p> -->
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/chiara.png" alt="Chiara Gabellieri" class="profile-image">
    <div class="profile-info">
      <h3>Chiara Gabellieri</h3>
      <h4>University of Twente, Netherlands</h4>
      <p><strong>Title:</strong> Modeling and Control Challenges in Aerial Robotics</p>
      <p><strong>Abstract:</strong> Recent advances in aerial robotics are posing new modeling and control challenges. Novel multirotor platforms are being developed to enhance dexterity and efficiency. Driven by the need for efficient aerial transportation, cooperative aerial manipulation using non-stopping flying vehicles has emerged as a promising paradigm. Furthermore, moving beyond straight-cable models, recent research explores aerial robotic manipulation through flexible cables. This talk will present some of the key modeling and control challenges arising from these research directions.</p>
      <p><strong>Bio:</strong> Chiara Gabellieri is an Assistant Professor in the Robotics and Mechatronics group of the EEMCS faculty at the University of Twente, in the Netherlands. Chiara received her Ph.D. in Information Engineering in 2021 from the University of Pisa. She was an intern at LAAS-CNRS in Toulouse, France, and a visiting Ph.D. student at DLR Institute of Robotics and Mechatronics in Germany. She is a co-applicant in the Dutch NWO-OTP project AVIATOR and local PI in the Marie Skłodowska-Curie Staff Exchange project NEUTRAWEED. She is an Associate Editor for IEEE RA-L and an Editor for the Unmanned Aviation Magazine. She has served as an Associate Editor for ICRA 2021-2026, IROS 2022-2026, and ICUAS 2026. Her research interests include aerial robotic cooperative manipulation and physical interaction.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center (DLR), Germany</h4>
      <p><strong>Title:</strong> Don’t Fight the Dynamics: Structure-Preserving Control of Compliant Robots</p>
      <p><strong>Abstract:</strong> Elastic and variable-stiffness actuators equip robots with safety, impact-robustness, accurate and stable force control, and the potential for energy storage, but at a control-theoretic cost: the resulting dynamics are underactuated and lack a passive input/output map. This talk presents a quasi-full actuation equivalence. A coordinate transformation on the motor variables, paired with a matching change of control inputs, maps the underactuated elastic-joint dynamics onto a fully actuated system with a passive input/output map. The transformation preserves the Lagrangian structure and establishes a one-to-one correspondence between original and transformed trajectories. This makes the rigid-robot control toolbox, and its Lyapunov- and passivity-based guarantees, directly applicable to a broad class of compliant robots. On this foundation, elastic structure–preserving (ESP) control follows a single design philosophy: do as little as possible, but as much as necessary. It minimizes dynamics shaping. The premise is that a closed loop mirroring the robot's intrinsic structure is inherently robust and rewards high performance with little control effort. I present experimental results that refute the supposed upper bound on passively renderable stiffness and the assumed softness–accuracy trade-off, and close with a discussion of the intrinsic performance limits of flexible structures, the price of flexibility, and the open hardware/control co-design questions they raise.</p>
      <p><strong>Bio:</strong> Manuel Keppler leads the Elastic Robot Control group at the German Aerospace Center (DLR), Institute of Robotics and Mechatronics, where he also directs the control development of DLR David, a humanoid robot equipped with variable-stiffness actuators. Since May 2026, he is additionally a part-time Assistant Professor (0.2 FTE) in the Department of Mechanical Engineering at Eindhoven University of Technology. He holds B.S. (2012) and M.S. (2014) degrees in mechanical engineering, both with highest distinction, from the Technical University of Vienna, as well as a B.S. in Molecular Biology from the University of Vienna (2009), and earned his Ph.D. in Computer Science (summa cum laude) from the Technical University of Munich in 2023. His research focuses on the compliant design and energy-based control of robots, enabling safe, robust, and dynamic interaction with people and their environment. His contributions have been recognized with several awards, including the Georges Giralt PhD Award (2024), the ICRA 2016 Best Automation Paper Award (Finalist), and an Honorable Mention for the IEEE Robotics and Automation Letters Best Paper Award (2022). He is also co-founder and co-chair of the IEEE RAS Technical Committee on Robot Control.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/kyoungchul.png" alt="Kyoungchul Kong" class="profile-image">
    <div class="profile-info">
      <h3>Kyoungchul Kong</h3>
      <h4>KAIST, South Korea</h4>
      <!-- <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p> -->
    </div>
  </div>
  
  <div class="profile-card">
    <img src="assets/speakers/senior/alessandro-a.jpg" alt="Alessandro Astolfi" class="profile-image">
    <div class="profile-info">
      <h3>Alessandro Astolfi</h3>
      <h4>Imperial College London, UK</h4>
      <p><strong>Title:</strong> Control, Estimation, and Adaptation for Pneumatic Soft Continuum Robots</p>
      <p><strong>Abstract:</strong> 
      Soft continuum robots are increasingly used in engineering applications, including compliant manufacturing, medical procedures, and disaster rescue. However, their highly uncertain and nonlinear material and structural properties, along with time-varying interactions with the environment, pose significant challenges for control and state estimation.
      This talk presents recent advances in control, estimation, and adaptation for pneumatic soft continuum robots. We first discuss passivity-based and immersion-and-invariance adaptive control strategies, together with force estimation methods for manipulation tasks. We then address hysteresis, a common source of dynamical uncertainty in soft continuum robots. Both model-based and learning-based approaches for estimating and compensating hysteretic effects are presented, supported by examples.
      Finally, we introduce adaptive techniques for the locomotion of growing soft continuum robots, including navigation strategies for both planar and three-dimensional environments. 
      <strong>Authors</strong>: A. Astolfi (presenter), and Kaiwen Chen</p>
      <!-- <p><strong>Bio:</strong> [Insert Bio]</p> -->
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/mangini.jpeg" alt="Agostino Mangini" class="profile-image">
    <div class="profile-info">
      <h3>Agostino Mangini</h3>
      <h4>Politecnico di Bari</h4>
      <p><strong>Title:</strong> Artificial Intelligence-based Services for Cooperative, Connected and Automated mobility</p>
      <p><strong>Abstract:</strong> Artificial Intelligence (AI) technologies have the potential to significantly impact automation across a wide range of industries and domains. In urban areas, the number of Cooperative, Connected, and Automated Vehicles (CCAVs) is expected to steadily increase in the near future. As a result, mixed traffic scenarios—comprising both human-driven vehicles and CCAVs—are likely to become the norm in the coming years.
      Connected and automated vehicles can enhance overall traffic efficiency by preventing collisions, optimizing traffic flow, and enabling the development and deployment of innovative mobility services.
      This talk will illustrate how AI techniques—such as Deep Reinforcement Learning (DRL)—can support the full integration of CCAVs into real-world traffic systems, for both passenger and freight transportation. The ultimate goal is to deliver benefits to all citizens and generate positive societal impacts, including: i) safety (e.g., reducing road accidents caused by human error); ii) environmental sustainability (e.g., lowering emissions and congestion by smoothing traffic flow and minimizing unnecessary trips); iii) inclusiveness (e.g., ensuring accessible and equitable mobility for all users).
      The talk will also present recent case studies, implemented both in real-world settings and in simulation environments.</p>
      <!-- <p><strong>Bio:</strong> [Insert Bio]</p> -->
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/melanie.jpg" alt="Melanie Zeilinger" class="profile-image">
    <div class="profile-info">
      <h3>Melanie Zeilinger</h3>
      <h4>ETH, Switzerland</h4>
      <!-- <p><strong>Title:</strong> [Pending Title]</p>
      <p><strong>Abstract:</strong> [Pending Abstract]</p>
      <p><strong>Bio:</strong> [Pending Bio]</p> -->
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/naira.jpg" alt="Naira Hovakimyan" class="profile-image">
    <div class="profile-info">
      <h3>Naira Hovakimyan</h3>
      <h4>UIUC, USA</h4>
      <!-- <p><em>(Attendance: Remote or in-person replacement TBC)</em></p>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p> -->
    </div>
  </div>
</div>

## Program Schedule

| Time | Session |
|------|---------|
| 08:30–08:45 | Opening and workshop framing (Organisers) |
| 08:45–09:15 | Session I, **Manuel Keppler** |
| 09:15–09:45 | Session I, **Chiara Gabellieri** |
| 10:00–10:30 | *Coffee break* |
| 10:30–11:00 | Session II, **Alessandro Astolfi** |
| 11:00–11:30 | Session II, **Laura Ferranti** |
| 11:30–12:00 | Session II, **Melanie Zeilinger** |
| 12:00–13:30 | *Lunch break* |
| 13:30–14:00 | Session III, **Kyoungchul Kong** |
| 14:00–14:30 | Session III, **Naira Hovakimyan** |
| 14:30–15:00 | Session III, **Agostino Marcello Mangini** |
| 15:00–15:30 | *Coffee break* |
| 15:30–16:15 | Session IV, Closing panel moderated by Cosimo Della Santina |
| 16:15–16:25 | Closing remarks |


## Organizers

<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/organizers/cosimo.jpg" alt="Cosimo Della Santina" class="profile-image">
    <div class="profile-info">
      <h3>Cosimo Della Santina</h3>
      <h4>TU Delft, NL - Primary Contact</h4>
      <p>Associate Professor in Robotics and Control. Research on nonlinear control, soft and underactuated robots, and physical interaction. Email: c.dellasantina@tudelft.nl</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/kaoru.jpg" alt="Kaoru Yamamoto" class="profile-image">
    <div class="profile-info">
      <h3>Kaoru Yamamoto</h3>
      <h4>Kyushu University, JP</h4>
      <p>Associate Professor of Control, working on control methodologies that go beyond discrete-time approximations by explicitly accounting for intersample dynamics, alongside research on interconnected dynamical systems.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center - DLR, DE</h4>
      <p>Senior researcher in articulated soft and humanoid robot control, with strong links between theory and large-scale experimental platforms.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/sylvia.jpg" alt="Sylvia Herbert" class="profile-image">
    <div class="profile-info">
      <h3>Sylvia Herbert</h3>
      <h4>University of California San Diego, US</h4>
      <p>Assistant Professor working on scalable safety assurances and control policies based on available models and data about the system and environment.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/fumiya_matsuzaki.jpg" alt="Fumiya Matsuzaki" class="profile-image">
    <div class="profile-info">
      <h3>Fumiya Matsuzaki</h3>
      <h4>Kyushu University, Japan</h4>
      <p>PhD Student.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/yuhe_gong.jpg" alt="Yuhe Gong" class="profile-image">
    <div class="profile-info">
      <h3>Yuhe Gong</h3>
      <h4>University of Nottingham, UK</h4>
      <p>PhD Student.</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/daniele_caradonna.jpg" alt="Daniele Caradonna" class="profile-image">
    <div class="profile-info">
      <h3>Daniele Caradonna</h3>
      <h4>Scuola Superiore Sant'Anna, Italy</h4>
      <p>PhD Student.</p>
    </div>
  </div>
</div>

## Future Outcomes
The organizers aim for the outcomes of this workshop to feed into a joint community effort, such as a position or perspective paper outlining a coherent set of open challenges in robot control. This document would serve as a reference point for future research and discussion within the control and robotics communities.