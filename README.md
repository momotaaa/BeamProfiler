# Detection of Noisy Laser Spot Based on Multi-scale Neighborhood Search(2024 ICCV)  ![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)  
> Devoted by Danile Zhu  
# Detecting Method
A multi-scale neighborhood search method for the analysis of laser beam images.A quick and efficient method for calculating beam sizes from a single monochrome image using the ISO 11146 variance method. The algorithm has been refined to be less sensitive to background offset and noise.  
The ISO 11146 method for laser beam under natural backlight (with intensity equal to 30-40):  
![Image](https://github.com/momotaaa/BeamProfiler/blob/main/ISO_Method.png)  
Our method for laser beam detection:  
![Image](https://github.com/momotaaa/BeamProfiler/blob/main/Our_result.png)  
We fit the laser beam center and size perfectly even in the presence of high noise intensity and rotation.  
The code will be available soon after the paper is published.
