# Atmospheric Variability Analysis of WASP-121b 🌌

This repository presents my research on simulating and analyzing the atmospheric dynamics of the ultra-hot Jupiter WASP-121b using the **MIT General Circulation Model (MITgcm)**. This work was completed as part of the **GRAD-MAP Summer 2025 Program** at the University of Maryland, Department of Astronomy and Physics, in College Park, Maryland under Dr. Hayley Beltz, a post-doctoral associate at UMD.

---

## Overview

We used a customized version of MITgcm—originally developed for Earth’s climate systems—to investigate temperature variability in WASP-121b’s atmosphere. I developed Python-based post-processing tools to extract, clean, visualize, and analyze multi-dimensional simulation output data, exploring how temperature and wind patterns evolve over time and space.

I will continue this work independently during the academic year under the mentorship of **Dr. Hayley Beltz**.

---

## Objectives

- Simulate atmospheric behavior using MITgcm on ultra-hot Jupiter WASP-121b
- Edit historic MATLAB model code to go over a range of timesteps
- Quantify temperature variability across longitude, latitude, pressure levels, and planetary time
- Build reusable post-processing pipelines in Python for scientific visualization

---

## Key Features

- **Atmospheric Data Extraction**: Converted and built scripts to process model outputs
- **Visualization**: Plots of temperature fields, standard deviation vs. pressure/time/coordinates
- **Automation**: Automated slice extraction across time/space dimensions
- **Planetary Context**: Interpreted results in light of planetary rotation and irradiation dynamics

---

## About WASP-121b

- Orbits extremely close (~0.025 AU) to its host star
- Surface temperatures exceed 2,500K
- Ideal for atmospheric studies due to extreme irradiation and brightness

Source: [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu/overview/WASP-121)

---

## Poster & Web Links

- **Poster PDF**: [View Poster](https://www.umdgradmap.org/assets/poster/CHIMALILO.pdf)
- **Project Abstract**: [Visit Site](https://www.umdgradmap.org/assets/writeup/chimalilo.pdf)

---

## Technologies Used

- MITgcm (General Circulation Model)
- Python (NumPy, Pandas, Xarray, Matplotlib, Seaborn)
- Google Colab (Jupyter)

---

## Acknowledgements

Special thanks to:

- **GRAD-MAP Program** and its sponsors for this opportunity
- **GRAD-MAP Supervisors** - **Mark Ugalino, Yash Gursahani, Shannon Gray**
- **Dr. Hayley Beltz** for her continual brilliant guidance and mentorship
- **GRAD-MAP Summer 2025 Cohort** for their collaboration and support
- **God** for the strength, perseverance, and insight

---

## References

- MITgcm Documentation: [Global Atmosphere Hydrostatic Setup](https://mitgcm.readthedocs.io/en/latest/overview/global_atmos_hs.html)
- NASA Exoplanet Archive – WASP-121b: [Exoplanet Overview](https://exoplanetarchive.ipac.caltech.edu/overview/WASP-121)
