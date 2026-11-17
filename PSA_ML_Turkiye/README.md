# Machine Learning-Based Prediction of Pseudo-Spectral Acceleration (PSA) in Türkiye

**Research companion repository | MATLAB GUI | Model access on request**

This repository accompanies our published research on machine-learning-based prediction of pseudo-spectral acceleration (PSA) using strong-motion data from Türkiye.

Link: https://link.springer.com/article/10.1007/s10950-026-10374-8 

## Overview

The study evaluates machine learning methods for predicting PSA at different periods using earthquake magnitude, site conditions (Vs30), and epicentral source distance.

**Model inputs:** Earthquake magnitude (M), Vs30, epicentral distance (Repi), and oscillator period (T).  
**Model output:** Pseudo-spectral acceleration (PSA).
Three period-specific trained models were selected.

## MATLAB graphical user interface (GUI)

A MATLAB-based GUI was developed to facilitate PSA predictions for user-defined earthquake and site parameters.

## Availability of trained models

> **The trained MATLAB models are not publicly distributed in this repository.**
>
> Researchers interested in accessing the models for academic or non-commercial research may contact the corresponding author. Requests will be considered individually, subject to applicable data, intellectual property and institutional requirements.
>
> **To request model access**, please email **[h.coban@ktu.edu.tr]** with your name, institution, intended research use, and the model/period range(s) requested.

The model files referred to in the research workflow are not included in the public repository.

## Repository contents

- `gui/` — public MATLAB GUI source (to be added following review)
- `screenshots/` — GUI images (to be added)
- `examples/` — documentation and non-sensitive examples
- `models/` — availability notice only; no trained model binaries
- `MODEL_REQUEST.md` — instructions for requesting the models
- `CITATION.cff` — citation metadata template; complete before publication

## Citation

If you use this work, please cite the peer-reviewed article:

**[Machine learning–based modelling of pseudo spectral acceleration (PSA) using strong-motion data from Türkiye]**. *Journal of Seismology*. **[https://link.springer.com/article/10.1007/s10950-026-10374-8]**.

Please cite the publication rather than this repository alone. Complete article metadata will be inserted before release.

## Important notes

- This is a research implementation, not an operational seismic hazard product.
- Predictions should not be used as the sole basis for engineering design or safety-critical decisions.
- The public availability of the GUI does not imply public availability of trained models or underlying restricted datasets.

## Contact

**Kaan Hakan Çoban**  
Department of Geophysical Engineering, Karadeniz Technical University, Türkiye  
Email: **[h.coban@ktu.edu.tr]**
