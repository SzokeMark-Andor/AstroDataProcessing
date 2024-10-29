# Analysis of NGC 628 Galaxy from EMPIRE Survey

## Overview
This repository hosts a project focused on analyzing and visualizing data from the NGC 628 galaxy, part of the EMPIRE survey. Using data processing and 3D visualization techniques, the project explores galaxy morphology and intensity maps derived from astronomical FITS files, offering insights into structural characteristics of the galaxy.

## Table of Contents
- [Overview](#overview)
- [Libraries Used](#libraries-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Citation](#citation)

## Libraries Used
- **Astropy**: Core astronomical data processing tools.
- **xarray**: Flexible data handling for multidimensional arrays.
- **PyVista**: 3D plotting and visualization.
- **astrofix**: Tools for correcting bad pixels in FITS images.

## Project Structure
- **Introduction**: Overview of the galaxy’s properties and dataset goals.
- **Data Preprocessing**: Steps for loading and preparing FITS files.
- **Visualization**: 3D visualization of galaxy data cubes and moment maps.
- **Image Enhancement**: Incorporating simulated maps for enhanced analysis.
- **Conclusion**: Summary of galaxy characteristics and visualization insights.

## Installation
To set up the environment, install required libraries:
```bash
pip install astropy xarray pyvista astrofix
```

## Execute the Analysis Pipeline
1. Load FITS data files.
2. Preprocess the data to address any pixel anomalies and enhance image quality.
3. Generate and visualize 3D galaxy maps and moment maps.
4. Analyze the integrated intensity maps to gain insights into galaxy morphology and structure.
5. Implement gravitational lensing analysis to explore the effects on light from distant galaxies.

# Features
- **3D Data Cube Visualization**: Leverages PyVista for detailed exploration of galaxy data cubes, providing an interactive view of the NGC 628 structure.
- **Simulated Integrated Intensity Maps**: Adds simulated maps to the visualization pipeline, allowing for enhanced analysis of moment maps.
- **Bad Pixel Correction**: Utilizes astrofix to improve data quality by correcting bad pixels, ensuring reliable visual and quantitative analysis.
- **FITS File-Based Analysis**: Supports a variety of FITS files following specific naming conventions, with automated handling of integrated intensity, uncertainty, and velocity maps.
- **Gravitational Lensing Analysis**: Incorporates gravitational lensing techniques for in-depth analysis of light bending from distant objects, enhancing the understanding of galaxy structure and dynamics.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Citation
If you use this project in your research, please cite it as follows:

## Harvard Style
Szoke, M.-A. (2024) Analysis of NGC 628 Galaxy from EMPIRE Survey, GitHub. Available at: [https://github.com/username/ngc628-galaxy-analysis](https://github.com/username/ngc628-galaxy-analysis).

## IEEE Format
M.-A. Szoke, “Analysis of NGC 628 Galaxy from EMPIRE Survey,” GitHub, 2024. [Online]. Available: [https://github.com/username/ngc628-galaxy-analysis](https://github.com/username/ngc628-galaxy-analysis). [Accessed: Day Month Year].
