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
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/chiara.png" alt="Chiara Gabellieri" class="profile-image">
    <div class="profile-info">
      <h3>Chiara Gabellieri</h3>
      <h4>University of Twente, Netherlands</h4>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center (DLR), Germany</h4>
      <p><strong>Title:</strong> [Pending Title]</p>
      <p><strong>Abstract:</strong> [Pending Abstract]</p>
      <p><strong>Bio:</strong> [Pending Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/early_mid/kyoungchul.png" alt="Kyoungchul Kong" class="profile-image">
    <div class="profile-info">
      <h3>Kyoungchul Kong</h3>
      <h4>KAIST, South Korea</h4>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>
  
  <div class="profile-card">
    <img src="assets/speakers/senior/alessandro-a.jpg" alt="Alessandro Astolfi" class="profile-image">
    <div class="profile-info">
      <h3>Alessandro Astolfi</h3>
      <h4>Imperial College London, UK</h4>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/mangini.jpg" alt="Mangini" class="profile-image">
    <div class="profile-info">
      <h3>Mangini</h3>
      <h4>[Affiliation TBC]</h4>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/melanie.jpg" alt="Melanie Zeilinger" class="profile-image">
    <div class="profile-info">
      <h3>Melanie Zeilinger</h3>
      <h4>ETH, Switzerland</h4>
      <p><strong>Title:</strong> [Pending Title]</p>
      <p><strong>Abstract:</strong> [Pending Abstract]</p>
      <p><strong>Bio:</strong> [Pending Bio]</p>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/speakers/senior/naira.jpg" alt="Naira Hovakimyan" class="profile-image">
    <div class="profile-info">
      <h3>Naira Hovakimyan</h3>
      <h4>UIUC, USA</h4>
      <p><em>(Attendance: Remote or in-person replacement TBC)</em></p>
      <p><strong>Title:</strong> [Insert Title]</p>
      <p><strong>Abstract:</strong> [Insert Abstract]</p>
      <p><strong>Bio:</strong> [Insert Bio]</p>
    </div>
  </div>
</div>

## Program Schedule

| Time | Session |
|------|---------|
| 08:30–08:45 | Opening and workshop framing (Organisers) |
| 08:45–09:15 | Session I, Manuel Keppler |
| 09:15–09:45 | Session I, Chiara Gabellieri |
| 10:00–10:30 | Coffee break |
| 10:30–11:00 | Session II, Alessandro Astolfi |
| 11:00–11:30 | Session II, Laura Ferranti |
| 11:30–12:00 | Session II, Melanie Zeilinger |
| 12:00–13:30 | Lunch break |
| 13:30–14:00 | Session III, Kyoungchul Kong |
| 14:00–14:30 | Session III, Naira Hovakimyan (remote, or in-person replacement TBC) |
| 14:30–15:00 | Session III, Mangini (handover from Fanti) |
| 15:00–15:30 | Coffee break |
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