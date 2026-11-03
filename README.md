# FBSS: Fourier-Bessel Spherical-Harmonic Splatting

My entry to the iMED-NVS 2026 challenge (MICCAI 2026, EndoVis): rendering a surgical scene from a second endoscope, using only the recording of the first one.

Competition page: https://www.synapse.org/Synapse:syn74277461

Final rank on the hidden test set: 6th of 15 teams.

![Final leaderboard](results.png)

FBSS is a splatting renderer where each primitive is a small 3D field written in a spectral basis instead of a Gaussian, with its own CUDA rasteriser, a motion model for the tissue and a training pipeline built for this challenge. The code, the full results and the technical report are private.

If you are interested in the complete repository, the results, or in continuing this research together, contact me at sultanfrikha2019@gmail.com.
