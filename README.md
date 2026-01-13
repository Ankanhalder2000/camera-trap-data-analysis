# Camera Trap Data Analysis (Python)

## Project Overview
This project demonstrates end-to-end ecological data analysis using camera trap data.
It focuses on summarizing species observations, sex ratios, and spatial patterns using Python.

The workflow includes data cleaning, exploratory analysis, species-wise summaries,
sex-based analysis, data visualization, and preparation of GIS-ready datasets.

## Skills Demonstrated
- Python (pandas, matplotlib, seaborn)
- Data cleaning and wrangling
- Ecological data analysis
- Summary statistics
- Data visualization
- Preparing spatial data for GIS workflows

## Data Source
Camera trap dataset sourced from an open-access Mendeley Data repository.
The data is used strictly for academic and skill demonstration purposes.

## Project Structure
- data/raw → Original datasets
- data/cleaned → Cleaned and processed datasets
- notebooks → Jupyter notebook containing the full analysis
- outputs → Figures generated from the analysis

## Key Outputs
- Species-wise abundance summaries
- Species × Sex count and percentage analysis
- Bar plots and density heatmaps
- GIS-ready camera trap point dataset

## Repository Status
This repository represents a completed end-to-end analysis pipeline.
Data cleaning, analysis, visualization, and GIS-ready exports are finalized.

## Next Steps
- Spatial visualization in QGIS
- Camera trap distribution mapping
- Habitat suitability and corridor analysis

## Future Use
This project feeds directly into GIS-based spatial analysis and ecological modelling workflows.

## How to Run This Project
1. Clone the repository
2. Create a virtual environment
3. Install dependencies:
   pip install -r requirements.txt
4. Open the Jupyter notebook:
   notebooks/CameraTrap_Analysis.ipynb

## 📌 **Download the final release of the Camera Trap Analysis project:** [v1.0 – Camera Trap Analysis](https://github.com/Ankanhalder2000/camera-trap-data-analysis/releases/tag/v1.0)

> Note: The Jupyter Notebook contains a code cell that generates a heatmap showing the density of camera trap observations based on longitude and latitude. The PNG figure has been removed from the repository to reduce clutter, but the code and output remain in the notebook. Running the notebook will generate the heatmap interactively.Python-based heatmaps are exploratory.
Final spatial interpretation is intended for GIS platforms.

Follow-up GIS Project:
Camera Trap Spatial Distribution Mapping (QGIS):
https://github.com/Ankanhalder2000/GIS-Camera-Trap-Spatial-Distribution

## Author
Ankan Halder

