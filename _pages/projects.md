---
title: "Projects"
permalink: /projects/
author_profile: true
---
## Sidewalk Sidekick (Mechanical Engineering Capstone)
**Won overall Honorable Mention at Spring 2026 Capstone Expo (out of 230+ teams)**

Navigating complex urban terrain is a challenge for blind and visually impaired people (BVIPs). Common obstacles include uneven sidewalks, curbs, construction zones, and transient barriers. While white canes and guide dogs remain the predominant technologies to assit with obstacle detection and navigation, these technologies fall short with regards to detection of non-ground-based obstacles and navigation to unfamiliar locations.

Sidewalk Sidekick serves as an integrated platform for navigation and contextualized guidance for BVIP. It contains two main components:
1. Robotic guidance platform (8 DOF quadrupedal architecture featuring a LIDAR and RGB depth camera for environmental contextualization and path planning)
2. Ergonomic handle (Bluetooth enabled handle with integrated electronics, allowing the user to manually control the device (a) physically via button press or (b) orally via bone conduction headset)

Highlights of the system include:
1. Wheeled quadruped robotic platform with 8 actuators
2. Electrical architecture for guidance quadruped and user interfacing handle
3. Local costmap for path planning around obstacles
4. Training of obstacle classification model using YOLO dataset

<iframe width="560" height="315" src="https://www.youtube.com/embed/_x3aDHAftAU?si=fcQCIv5cPWDUNzEL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<object data="/files/ExpoPres (1).pdf" type="application/pdf" width="100%" height="100%">
  <p>Your browser can’t display PDFs inline. <a href="/files/ExpoPres (1).pdf">Download the PDF</a>.</p>
</object>

## Flute Musician
'Flute Musician' was the final project for my mechatronics course (ME 4405). The motivation for this project was:
> Can we replicate the embouchure technique and
synchronize with physical key combinations to play a
flute using mechanical design and mechatronics?

There were 4 main subsystems for this robot:​
1. **Mouthpiece & Pneumatics**: provides airflow to the flute via a 3D-printed mouthpiece to produce sound. Also includes a bullet valve to replicate tongue articulation.
2. **Key Articulation**: actuate keys via cable-drive from servos to execute the correct fingerings. The servos are located on linear rails to allow for in-situ adjustment of servo positioning.
3. **Flow Control**: stepper motor adjusts flow for each note depending on pre-set, experimentally-derived steps to produce the best tone.
4. **Sensing & Feedback**: microphone monitors output frequency of the flute and executes tuning sequence.

### System Snapshot
![System Snapshot](/images/Slide3.jpg)

### Mary Had a Little Lamb
<video width="640" controls>
  <source src="/files/Mary_Had_A_Little_Lamb.mp4" type="video/mp4">
</video>

## Skin Lesion Detection Model
'Skin Lesion Detection Model' was the final project for my machine learning course (CS 4641). Skin cancer is one of the most common forms of cancer worldwide, and early detection is crucial for effective treatment. This project developed a model that predicted the type of skin lesion using the HAM 1000 dataset, which includes 10,015 dermatoscopic images of pigmented skin lesions. 

The three ML models implemented for this project are:
1. KMeans - to explore an unsupervised learning approach to classificaation and further understand if the data has any natural groupings.
2. SVM - address imbalances in the dataset and improve performance using  minority class augmentation techniques and dimensionality reduction.
3. CNN - designed to work with image data and capture spatial patterns like color, texture, and shape, which is critical to the problem of differentiating types of skin lesions.

[Final Report](/files/CS_4641_Final_Report.pdf)
