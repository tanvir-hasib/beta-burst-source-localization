
EEG-Based Localization of Transient Beta Bursts in Parkinson's Disease

This repository contains the source code for the source reconstruction and localization pipeline of transient beta bursts using scalp EEG data from individuals with Parkinson's Disease (PD) and healthy controls (HC).
The pipeline is implemented in Python, leveraging MNE-Python for EEG processing/source modeling and Nilearn for structural MRI mapping.

📌 Main Finding

Pathological beta bursts (13–30 Hz) in the Parkinsonian resting state drive a measurable evoked-like cortical response predominantly generated or amplified at the cortical level within the contralateral primary motor cortex (hand/arm representation in the left precentral gyrus) and adjacent premotor regions, rather than solely propagating upward from subcortical structures.


📊 Dataset Focus

This code is built to run on the publicly available UC San Diego Resting State EEG Data from Patients with Parkinson’s Disease available on OpenNeuro.
• Cohort: 15 PD Patients (recorded in both Medication-OFF and Medication-ON states) + 16 Healthy Controls.
• Hardware: 32-channel BioSemi ActiveTwo system sampled at 512 Hz.


📈 Key Visualizations Produced

The Jupyter notebooks yield several high-fidelity diagnostic assets:
• Sensor-Space Envelopes: Real-time burst verification over primary central channels (e.g., C3/C4).
• Cortical Surface Maps: Distributed dSPM source maps overlaid on inflated template brains.
• ECD Dipole Overlays: 3D orthographic structural projections pinpointing coordinates within MNI space.
• Source Activation Curves & Boxplots: Time-courses and statistical distributions comparing peak metrics across groups (PD OFF, PD ON, HC).
