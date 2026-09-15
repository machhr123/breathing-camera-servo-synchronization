## Experiment Overview

This experiment focuses on studying the **flow of a liquid solution through a capillary-based prototype**, along with the formation and characteristics of the particles generated during the process. The experiment is intended to support research into particle characteristics and their potential suitability for pulmonary delivery applications.

A controlled airflow of approximately **30 L/min** is generated to replicate the required airflow conditions. A **servo-controlled mechanism** regulates the airflow according to a predefined **human breathing profile**, simulating the inhalation and exhalation cycle.

At precise points in the simulated breathing cycle, a **Photron high-speed camera** captures the flow and particle formation process. The camera is connected to a monitoring system to provide a **live view of the experimental process on a monitor**. **Photron FASTCAM Viewer (PFV4)** is used to configure and monitor the camera, view the live feed, control recording, and **record and store the captured high-speed image sequences** for subsequent analysis.

An **Arduino UNO** provides the trigger signal to the camera, allowing image acquisition to be synchronized with the servo-controlled breathing profile. This synchronization ensures that images are captured at the required phase of the simulated breathing cycle.

The setup also incorporates a **volumetric flow meter/control system** to monitor and maintain the required airflow throughout the experiment.

### Key Components

* Capillary-based liquid-flow prototype
* ~30 L/min controlled airflow system
* Servo-based human breathing-profile simulation
* Arduino UNO for camera triggering
* Photron high-speed camera
* **Photron FASTCAM Viewer (PFV4)** for live monitoring, recording, and data storage
* Volumetric flow meter/control system
* Image-based analysis of particle formation and characteristics

### Experimental Workflow

**Controlled Airflow → Breathing-Profile Servo Control → Capillary-Based Liquid Flow → Particle Formation → Synchronized Camera Trigger → High-Speed Image Acquisition → PFV4 Recording & Storage → Image Analysis**

### Research Objective

The synchronized setup provides a controlled platform for studying **particle formation, particle size, and flow behavior under simulated human breathing conditions**. The recorded high-speed images can be analyzed to characterize the generated particles and support further research into their potential transport and deposition within the respiratory system.
