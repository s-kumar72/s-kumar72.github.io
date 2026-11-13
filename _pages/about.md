---
permalink: /
title: "Robotics Portfolio"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

{% include site-style.html %}

<style>
  /* The intro below replaces the default page title on the homepage only */
  .page__title, #page-title { display: none; }
</style>

<section class="intro" aria-label="Introduction">
<img class="intro__photo" src="/images/sadhana-headshot.jpg" alt="Sadhana Kumar" onerror="this.style.display='none'">
<div>
<h1>Sadhana Kumar</h1>
<p>Robotics master's student (MRSD) at Carnegie Mellon, graduating May 2028. I work on perception and autonomy for robots in hard real-world settings: smoke-filled buildings, city sidewalks, lunar terrain.</p>
<p>Before CMU: BS in Mechanical Engineering with a minor in Robotics from Georgia Tech, where I did research in the Aerospace Robotics Lab.</p>
<p class="links"><a href="mailto:sadhanak@andrew.cmu.edu">Email</a><a href="https://github.com/s-kumar72">GitHub</a><a href="https://www.linkedin.com/in/sadhana--kumar">LinkedIn</a></p>
</div>
</section>

<h2 class="section-title" id="projects">Projects</h2>

<div class="projects">

<div class="project">
<a href="/projects/#sidewalk-sidekick"><img src="https://img.youtube.com/vi/_x3aDHAftAU/hqdefault.jpg" alt="Sidewalk Sidekick wheeled quadruped robot" loading="lazy"></a>
<h3><a href="/projects/#sidewalk-sidekick">Sidewalk Sidekick</a></h3>
<p class="when">Georgia Tech capstone · Spring 2026</p>
<p>A wheeled quadruped with LIDAR, RGB-D perception, and a shared-control handle that guides blind and visually impaired people around sidewalk obstacles.</p>
<p class="note">Overall Honorable Mention out of 230+ teams</p>
<p class="links"><a href="/projects/#sidewalk-sidekick">Details</a><a href="https://youtu.be/_x3aDHAftAU">Video</a></p>
</div>

<div class="project">
<img src="/images/uav-radar.jpg" alt="Top-down radar intensity map from the UAV's sensor, showing returns from walls and objects around the radar" loading="lazy">
<h3>Autonomous UAV for fire reconnaissance</h3>
<p class="when">CMU MRSD capstone · Fall 2026 to present</p>
<p>A drone that scouts smoke-filled, GPS-denied buildings before firefighters go in, using thermal and radar perception, collaborative SLAM, and a map-based GUI for fire command.</p>
</div>

<div class="project">
<a href="/research/#nova"><img src="/images/Slide4.jpg" alt="NOVA rover platform overview" loading="lazy"></a>
<h3><a href="/research/#nova">NOVA rover</a></h3>
<p class="when">Aerospace Robotics Lab, Georgia Tech · 2025 to 2026</p>
<p>A low-cost rover for multi-agent autonomy research. I led the build and designed the electrical system and chassis integration.</p>
<p class="note">Released as open-source hardware</p>
<p class="links"><a href="/research/#nova">Details</a><a href="https://github.com/AstroX-OpenRover/NOVA2">GitHub</a></p>
</div>

<div class="project">
<a href="https://github.com/s-kumar72/multimodal-transparent-object-manipulation"><img src="/images/fig_sensors-1.png" alt="Simulation sensor setup for multimodal transparent object manipulation" loading="lazy"></a>
<h3><a href="https://github.com/s-kumar72/multimodal-transparent-object-manipulation">Seeing transparent objects</a></h3>
<p class="when">CMU Deep Learning (11-785) · Fall 2026 to present</p>
<p>Fusing RGB-D and thermal data so a robot can perceive and grasp glass cups and other transparent objects.</p>
<p class="links"><a href="https://github.com/s-kumar72/multimodal-transparent-object-manipulation">GitHub</a></p>
</div>

</div>

<p class="more">Also: <a href="/projects/#flute-musician">a flute-playing robot</a>, <a href="/projects/#skin-lesion-detection-model">a skin lesion classifier</a>, and <a href="/research/#advanced-manufacturing-pilot-facility-ampf">Schlieren flow imaging</a>.</p>

<h2 class="section-title" id="experience">Experience</h2>

<ul class="rows">
<li><span>Undergraduate Researcher <span class="org">· Aerospace Robotics Lab, Georgia Tech</span></span><span class="date">2025 – 2026</span></li>
<li><span>CAD Applications Engineering Intern <span class="org">· Apple</span></span><span class="date">Summer 2024</span></li>
<li><span>Undergraduate Research Assistant <span class="org">· Advanced Manufacturing Pilot Facility, Georgia Tech</span></span><span class="date">2023 – 2026</span></li>
<li><span>Process Design &amp; Development Intern <span class="org">· The Timken Company</span></span><span class="date">Summer 2023</span></li>
<li><span>Software Engineering Intern <span class="org">· WP Engine</span></span><span class="date">Summer 2022</span></li>
</ul>

<h2 class="section-title" id="education">Education</h2>

<ul class="rows">
<li><span>MS, Robotic Systems Development <span class="org">· Carnegie Mellon University</span></span><span class="date">2026 – 2028</span></li>
<li><span>BS, Mechanical Engineering, minor in Robotics <span class="org">· Georgia Tech · Stamps President's Scholar</span></span><span class="date">2022 – 2026</span></li>
</ul>

<h2 class="section-title" id="skills">Skills</h2>

<dl class="skills">
<dt>Programming</dt>
<dd>Python, C++, ROS 2, MATLAB, Java, Arduino</dd>
<dt>Perception &amp; learning</dt>
<dd>PyTorch, computer vision, RGB-D, LiDAR, multimodal perception</dd>
<dt>Simulation</dt>
<dd>NVIDIA Isaac Sim / Omniverse, MuJoCo</dd>
<dt>CAD &amp; fabrication</dt>
<dd>SOLIDWORKS, Siemens NX / NX Open, Inventor, Teamcenter, 3D printing, waterjet, laser cutting</dd>
<dt>Embedded</dt>
<dd>STM32, I2C / UART, motor control</dd>
</dl>
