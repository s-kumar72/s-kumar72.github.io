---
title: "Projects"
permalink: /projects/
author_profile: false
---

{% include site-style.html %}

<ul class="jump">
<li><a href="#sidewalk-sidekick">Sidewalk Sidekick</a></li>
<li><a href="#flute-musician">Flute Musician</a></li>
<li><a href="#skin-lesion-detection-model">Skin Lesion Detection Model</a></li>
</ul>

## Sidewalk Sidekick {#sidewalk-sidekick}

<p class="proj-meta">Georgia Tech Mechanical Engineering Capstone, Spring 2026</p>

<p><span class="award">Overall Honorable Mention at the Spring 2026 Capstone Expo, out of 230+ teams</span></p>

Navigating complex urban terrain is a challenge for blind and visually impaired people (BVIPs). Common obstacles include uneven sidewalks, curbs, construction zones, and transient barriers. White canes and guide dogs remain the main aids for obstacle detection and navigation, but they fall short at detecting non-ground-based obstacles and at guiding users to unfamiliar locations.

Sidewalk Sidekick is an integrated platform for navigation and contextual guidance. It has two main components:

1. **Robotic guidance platform:** an 8-DOF wheeled quadruped with a LIDAR and an RGB-D camera for environmental awareness and path planning.
2. **Ergonomic handle:** a Bluetooth-enabled handle with integrated electronics that lets the user control the device physically (button press) or by voice (bone conduction headset).

**Highlights**

- Wheeled quadruped platform with 8 actuators
- Electrical architecture for both the quadruped and the user-facing handle
- Local costmap for path planning around obstacles
- Obstacle classification model trained on a YOLO dataset

<div class="video-wrap">
<iframe src="https://www.youtube.com/embed/_x3aDHAftAU?si=fcQCIv5cPWDUNzEL" title="Sidewalk Sidekick demo video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen loading="lazy"></iframe>
</div>

<p><a class="btn-link" href="/files/ExpoPres%20(1).pdf">Expo presentation (PDF)</a></p>

---

## Flute Musician {#flute-musician}

<p class="proj-meta">Mechatronics course final project (ME 4405), Georgia Tech</p>

The question behind this project:

> Can we replicate the embouchure technique and synchronize with physical key combinations to play a flute using mechanical design and mechatronics?

The robot has four subsystems:

1. **Mouthpiece and pneumatics:** supply airflow through a 3D-printed mouthpiece to produce sound. A bullet valve replicates tongue articulation.
2. **Key articulation:** servos actuate the keys through a cable drive to execute the correct fingerings. The servos sit on linear rails so their positions can be adjusted in place.
3. **Flow control:** a stepper motor adjusts airflow for each note using experimentally derived steps that give the best tone.
4. **Sensing and feedback:** a microphone monitors the flute's output frequency and triggers a tuning sequence.

<figure>
<img src="/images/Slide3.jpg" alt="Flute Musician system snapshot" loading="lazy">
<figcaption>System snapshot</figcaption>
</figure>

<figure>
<video controls preload="metadata" playsinline>
<source src="/files/Mary_Had_A_Little_Lamb.mp4" type="video/mp4">
</video>
<figcaption>The robot playing "Mary Had a Little Lamb"</figcaption>
</figure>

---

## Skin Lesion Detection Model {#skin-lesion-detection-model}

<p class="proj-meta">Machine learning course final project (CS 4641), Georgia Tech</p>

Skin cancer is one of the most common cancers worldwide, and early detection is crucial for effective treatment. This project predicts the type of skin lesion using the HAM10000 dataset, which has 10,015 dermatoscopic images of pigmented skin lesions.

I implemented three models:

1. **K-Means:** an unsupervised approach to see whether the data has natural groupings.
2. **SVM:** addressed class imbalance with minority-class augmentation and dimensionality reduction.
3. **CNN:** built to capture spatial patterns like color, texture, and shape, which are critical for telling lesion types apart.

<p><a class="btn-link" href="/files/CS_4641_Final_Report.pdf">Final report (PDF)</a></p>
