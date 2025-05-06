# Neuromorphic Audio Analysis

This repository implements neuromorphic auditory processing inspired by the biological cochlea. It includes a homeostatic thresholding mechanism to improve spike-rate uniformity across channels in a spike-encoded audio pipeline.

## Features
- Converts raw audio to Mel-spectrograms
- Poisson spike encoding of Mel features
- Homeostatic threshold adaptation for improved firing rate consistency
- CV (coefficient of variation) analysis to measure uniformity improvements
- Plots for spike rasters and comparison bar charts

## Structure
- `encode_spikes.py` – Converts audio to Poisson spikes
- `homeostatic_model.ipynb` – Colab notebook demonstrating homeostatic improvements


## Results
The homeostatic model reduces inter-channel spike-rate variability by **53.7%**, improving signal representation consistency and biological plausibility.


```bash
git clone https://github.com/mohitraosatya/neuromorphic_Audio_Analysis.git
cd neuromorphic_Audio_Analysis

