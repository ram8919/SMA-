Introduction
1. Background: Orbital maneuvers are critical in satellite trajectory management. Detecting these maneuvers based on changes in orbital elements like the semi-major axis (SMA) is a common practice. This document presents a heuristic method to automatically detect maneuvers by identifying significant changes in the SMA data.
2. Objective: The objective is to develop a Python-based heuristic algorithm that can detect orbital maneuvers using SMA data. The method will be evaluated against known maneuver reference dates.

Problem statement for this Dataset:
Objective: Develop a method to automatically detect maneuvers in orbital data using either heuristic or machine learning (ML) approaches.
Data: Utilize semi-major axis (SMA) variation over time without explicit maneuver data.
Evaluation: Assess the method’s accuracy using provided reference graphs and a table with known maneuvers.
Implementation: Create Python code for data preprocessing, feature extraction, maneuver detection, and result visualization.

4. Conclusion
1. Summary: The heuristic method is effective for detecting maneuvers in orbital data, especially when relying on the SMA as the key feature. The use of a threshold-based system allowed for the identification of significant changes corresponding to maneuvers.
2. Limitations: Some maneuvers may have been missed due to the fixed threshold or noise in the data. Further work could involve adaptive thresholding or a machine learning approach to improve detection performance.
3. Future Work: Future developments could involve using more features such as velocity or training a machine learning model on labeled maneuver data to improve performance.
