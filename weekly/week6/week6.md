diagram of what i did

<img width="549" alt="image" src="https://github.com/user-attachments/assets/a34232dc-0e4f-4bdc-be1c-40cbb9af0910">


I started my team project!



Project Title
Roommate Conflict Calming System

Team Members
Subin Lee
Jeongmin Lee
Hannah Park

Introduction + Objective
Introduction:
Our system is designed to help mitigate conflicts between roommates by creating a calming atmosphere. It utilizes machine learning to detect the sounds of fighting or conflict and responds by playing dance music. In addition, the system monitors the user’s heart rate using a pulse sensor. Based on the detected pulse rate, the system adjusts the color of an LED, ranging from red to green, to reflect stress levels visually.
The components used in this project include a Particle Photon2, machine learning for sound recognition, a pulse sensor, and LED light strips. The system leverages cloud-based processing for sound classification, alongside local sensor data for real-time feedback.

Objective
The goal is to create a system that can autonomously recognize conflict situations (via sound detection) and provide both auditory (music) and visual (LED color) feedback to help calm the situation and the individuals involved.

Draft System Architecture Diagram
■ Provide a diagram illustrating the physical and logical connections between all components, such as the Particle Photon2

Particle Photon2: The central processing unit handles inputs from the sensors and controlling outputs.
Sound Detection Module: A microphone connected to the Photon2, capturing sounds for ML-based classification in the cloud.
Pulse Sensor: Attached to the user to detect pulse rate, with data transmitted to the Photon2.
LED Light Strip: Controlled by the Photon2, changes color based on pulse rate.
Cloud Service: Processes sound data for ML classification to determine if fighting sounds are present.

○ Draft Process or Sequence Diagram
Step 1: Sound is captured by the microphone and sent to the cloud for analysis.
Step 2: Machine learning model determines whether the sound indicates conflict or fighting.
Step 3: If fighting sounds are detected, dance music is played through a speaker.
Step 4: Simultaneously, the pulse sensor monitors the user’s heart rate.
Step 5: Based on the pulse rate, the LED color adjusts from red (high pulse) to green (calm pulse).

■ Include a diagram representing how the system operates, detailing data flow and the sequence of operations, from data sensing
to cue generation and output.

Experimentation Plan
■ Provide a list of planned experiments with the following components for each:
● Scope Title: Sound Recognition and Pulse Monitoring Integration
● Objectives
Test the accuracy of the ML model in distinguishing conflict sounds.
Calibrate the pulse sensor to trigger appropriate LED color changes.

● Focus Areas
	Sound data collection and training of the ML model.
LED and pulse sensor integration to ensure real-time response.


Team Member Roles

Subin: Responsible for developing the ML sound detection model and integrating the system with cloud services. (03-Axolotl)
Hannah: Responsible for 3D printing the tangible components (03-Axolotl)
Jeongmin: Responsible for visualizing the concept and creating a video for presentation. (03-Axolotl)



Expected Outcomes and Initial Feasibility Metrics
Expected Outcomes:
Successfully recognizing fighting sounds and triggering music output.
Real-time pulse monitoring and LED color adjustments based on heart rate.
Feasibility Metrics:
Accuracy of sound classification (target > 85%).
Response time between sound detection and music playback (target < 2 seconds).
Power consumption and integration complexity for continuous monitoring.


Summary
This project aims to reduce roommate conflicts by creating a responsive system that detects fighting and provides soothing audio-visual feedback. Progress so far includes the initial setup of the Photon2 with the pulse sensor and early-stage sound detection model training. Key challenges involve fine-tuning the sound classification and ensuring seamless integration of the pulse monitoring system.
