# OpenCSS

OpenCSS is an open-source tool that allows users to perform ground motion selection based on Conditional Scenario Spectral (CSS), as described by Arteta and Abrahamson (2019). The tool also enables users to calculate Conditional Mean Spectra (CMS) and Uniform Hazard Spectra (UHS).

Currently, OpenCSS (v1.0) supports input data from two seismic hazard databases, the **Servicio Geológico Colombiano (SGC)** and the **United States Geological Survey (USGS)**, providing flexibility for different regions and applications.


## Features 🚀

- **Ground Motion Selection using CSS** (Arteta & Abrahamson, 2019).
- **Calculation of CMS** using multiple GMPEs and correlation models.
- **Hazard Curve and Disaggregation Analysis**.

## Installation 📦

Ensure you have Python installed (recommended **Python 3.8+**). Clone the repository and install dependencies:

```bash
git clone https://github.com/ArtetaResearchGroup/OpenCSS.git
cd OpenCSS
conda env create -f environment_OQ_env.yml
```
## Usage ▶️
```bash
python main.py
```
## Contributors 👨‍💻
* [Jesús D. Caballero] (caballerojd@uninorte.edu.co) (Universidad del Norte, Colombia) 
* [César A. Pájaro] (cesar.pajaromiranda@canterbury.ac.nz) (University of Canterbury, New Zealand)
* [Carlos A. Arteta] (carteta@uninorte.edu.co) (Universidad del Norte, Colombia)

## References
* Arteta, C. A., & Abrahamson, N. A. (2019). Conditional scenario spectra (CSS) for hazard-consistent analysis of engineering systems. Earthquake Spectra, 35(2), 737-757.
* Baker, J. W., & Jayaram, N. (2008). Correlation of spectral acceleration values from NGA ground motion models. Earthquake Spectra, 24(1), 299-317.
* Macedo, J., & Liu, C. (2021). Ground‐motion intensity measure correlations on interface and intraslab subduction zone earthquakes using the NGA‐sub database. Bulletin of the Seismological Society of America, 111(3), 1529-1541.
