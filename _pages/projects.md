---
title: "Projects"
permalink: /projects/
author_profile: true
---

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
