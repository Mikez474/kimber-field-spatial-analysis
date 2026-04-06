# kimber-field-spatial-analysis
Spatial analysis and reservoir property mapping of the Kimber Field using Python

# Kimber Field: Spatial Analysis & Reservoir Property Mapping

**GC Africa | Python for Geoscience | Capstone Project**

## Overview
Spatial analysis and reservoir quality mapping of the Kimber Field using a 2,500-well synthetic subsurface dataset. The project produces 
interactive reservoir property maps and answer key geological questions about field-wide reservoir quality distribution.

## Key Findings
- The central-north blocks (B03-05, B02-05, B03-04) consistently show the best reservoir quality across all metrics
- Reservoir quality is strongly variable, with permeability ranging over 20× between the best and worst zones
- Cumulative oil production (155 MMbbl) is highest precisely where RQI is highest, validating the spatial model

## Tools & Libraries
- Python, pandas, geopandas, matplotlib, seaborn, scipy
- Jupyter Notebook / Google Colab

## Files
| File | Description |
|------|-------------|
| `Spatial_analysis_task.ipynb` | Main analysis notebook |
| `wells_master.csv` | 2,500 well dataset with reservoir properties |
| `field_boundary.geojson` | Field boundary polygon |
| `faults.geojson` | 7 mapped fault lines |

## How to Run
1. Clone or download this repository
2. Upload all files to Google Colab or Jupyter
3. Run `Spatial_analysis_task.ipynb` from top to bottom
