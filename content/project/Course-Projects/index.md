---
active : true
headless : true
design:
    columns : "1"
    spacing:
            padding : ["10px", "0", "10px", "0"]

summary: Projects formulated, developed, and demonstrated by students in various courses taught by Dr. Hassan.  
authors: [EPSL]
date: 2022-01-13T23:58:23-08:00
title: Course Projects
---
<!-- 
The format of each project listing follows 

SN. **Project Name** by *Student names*

    Summary or Abstract
    
    | [Demo](link) | [Report](Link) |
-->

This is a comprehensive record of projects formulated, developed, and demonstrated by student in various courses taught by Dr. Hassan Ghasemzadeh.

# Spring 2022

## Embedded Machine Learning

1. **Detect User Falling Over and Abnormal Gait Using Arduino Nano 33** by *Chia-Cheng Kuo*

    It is crucial to provide emergency treatment for elderly or patients
    when they fall over. It is also important to provide warnings if
    the elderly or patients have high risk of falling due to abnormal
    gait. Although my system does not have high accuracy in real-time
    performance and will sometimes misestimate a kind of abnormal
    gait as another kind of abnormal gait, it still has good accuracy
    on distinguishing normal and abnormal gait. Future works for the
    project may include: 1) analyzing the recorded walking motion
    and give warnings if the user have too much abnormal gaits de-
    tected and have high risk of falling. 2) collect more data, try more
    model architectures and training parameters to improve real-time
    performance accuracy.

    | [Demo](https://www.youtube.com/watch?v=YJ0TwOIkwBo) | [Report](https://bit.ly/39f0FuA) |

2. **Activity Detection using Embedded Machine Learning** by *Emily Glagolev, Mihir Kotas, and Ahmed Musani*

    Physical Activity has can effect a persons physical and mental
    health. Because of this, it is important to be able to accurately monitor the activities a person does daily. We created an activity detection device using embedded machine learning using and Arduino Nano 33 BLE sense. This device can detect if a person is walking, jogging, using stairs or standing still, along with the duration of time they are doing the activity. Data was collected for each activity using the Arduino BLE connection and cleaned. A model was trained using Tensorflow. This trained model was used for real time testing with the Arduino BLE connected to a central. The central used bleak to detect the activity and record the duration of the activity.

    | [Demo](https://www.youtube.com/watch?v=97o2-8fS7Ms) | [Report](https://bit.ly/3PpIvqW) |

3. **Breating Pattern Identification** by  *Abdullah Mamun and Asiful Arefeen*

    | [Demo](https://youtu.be/RBKVR6dvekI) |

4. **Low Power Microgrid Disturbance Classification with Phasor Measurement Unit** by *Zachary Lythgoe*

    <!-- <p align="center">
    <img width="300" height="300" src="featured.png">
    </p> -->

    In comparison to the primary grid, microgrids are significantly more
    sensitive to local changes due to reduced local reserve generation
    and the switching of loads that make up a comparatively larger
    percentage of the total load. Given this sensitivity, it is critical for
    grid controllers to monitor local disruptions (i.e., sudden increase
    or decrease in load or generation) that the grid is experiencing.
    This work proposes a low power phasor measurement unit (PMU)
    paired with an Arduino Nano BLE 33 Sense to classify a variety of
    disturbances on a simulated microgrid. The low power, low cost
    solution makes such a system easier to implement in existing and
    future microgrids. 

    | [Demo](https://www.youtube.com/watch?v=QFYur2osd0w) | [Report](https://bit.ly/3M5n7oQ) |


