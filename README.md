# BeamProfiler
A multi-scale neighborhood search method for the analysis of laser beam images.

# Detecting Method
by Daniel Zhu
A quick and efficient method for calculating beam sizes from a single monochrome image using the ISO 11146 variance method. The algorithm has been refined to be less sensitive to background offset and noise.

ISO 11146 method for laser beam under natural backlight (with intensity equal to 30-40):
<img src="https://github.com/momotaaa/BeamProfiler/blob/main/ISO_Method.png" width="300">

Our method for laser beam detection:
<img src="https://github.com/momotaaa/BeamProfiler/blob/main/Our_result.png" width="300">

We fit the laser beam center and size perfectly even in the presence of high noise intensity.
The code will be available soon after the paper is published.
