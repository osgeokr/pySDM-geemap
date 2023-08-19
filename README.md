# pySDM-geemap

The "pySDM-geemap" repository provides Jupyter Notebook files outlining the implementation of Species Distribution Modeling (SDM) using Google Earth Engine and geemap. The content of this repository presents a conversion and enhancement of JavaScript source code provided by researchers from the Smithsonian Conservation Biology Institute. The original JavaScript code has been translated and refined into Python to achieve the same objectives.

Reference:
Crego, R. D., Stabach, J. A., & Connette, G. (2022). Implementation of species distribution models in Google Earth Engine. Diversity and Distributions, 28, 904–916.<br>
<https://doi.org/10.1111/ddi.13491><br>
<https://smithsonian.github.io/SDMinGEE/>

## Case Study 1: Habitat Suitability and Potential Distribution Modeling of Fairy Pitta (Pitta nympha) Using Presence-Only Data

The aim of this case study is to demonstrate the process of performing Species Distribution Modeling using Google Earth Engine and geemap, a Python library for interactive mapping with Earth Engine. The ipynb files in this repository provide step-by-step tutorials and examples of how to prepare, analyze, visualize, and model species distribution data using these powerful tools.

## Steps in Species Distribution Modeling (SDM)

1. **Add Species Occurrence Data**

2. **Define Area of Interest**

3. **Add Predictive Variables**

4. **Generate Pseudo-Absence Data**
   - 4.1. Generate Random Pseudo-Absence Data in the Entire Area of Interest
   - 4.2. Generate Spatially Constrained Pseudo-Absence Data (Buffer around Occurrences)
   - 4.3. Generate Environmental Pseudo-Absence Data (Environmental Profiling)

5. **Fit SDM Model**

6. **Calculate Variable Importance**

7. **Predict with SDM Model**

8. **Evaluate Accuracy**

9. **Custom Binary Distribution Mapping Based on Optimal Threshold**

10. **Export Results**
