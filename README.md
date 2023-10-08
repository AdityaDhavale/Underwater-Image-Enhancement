# Underwater-Image-Enhancement
Project Title: Enhancing Underwater Imagery with SwarmGen

Problem Statement:
Underwater images often suffer from poor quality due to the dominance of blue and green wavelengths, as well as scattering. This diminishes their usability, impacting applications like marine research, underwater archaeology, and surveillance.

Use Case:
Our project aimed to improve the quality of underwater images, enhancing their suitability for analysis. This enhancement is crucial for accurate underwater image-based tasks and applications.

Data Collection:
We gathered underwater images from various aquatic environments, including oceans, lakes, and rivers. These images represented diverse underwater scenarios, spanning different visibility and lighting conditions.

Data Preprocessing:
To address underwater imagery challenges, we applied advanced preprocessing techniques. This involved Gaussian blur and histogram equalization to reduce scattering effects and color dominance.

Model Implementation:
To further enhance preprocessed images, we utilized the Particle Swarm Optimization (PSO) algorithm. Inspired by flocking behavior in nature, PSO proved effective for underwater image enhancement.

Results:
We evaluated our approach using image quality metrics:

Entropy: Improved from 6.055 to 7.21
Contrast: Enhanced from 17.78 to 47.51
CCI (Color Contrast Index): Increased from 0.035 to 0.038
IQI (Image Quality Index): Enhanced from 3.0018 to 16.21
Comparing to other methods:

HE (Histogram Equalization): Contrast improved from 7.77 to 73.75
ICM (Iterative Color Management): CCI increased from 0.041 to 0.041
RGHS (Recursive Global Histogram Stretching): Contrast improved from 7.61 to 62.91
UCM (Underwater Color Correction Model): CCI increased from 0.043 to 0.043
Rayleigh Distribution: Contrast improved from 7.55 to 75.26
