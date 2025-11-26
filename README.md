
# California Wildfire Analysis – Palisades & Eaton Fires, February 2025

##### Author: Henry Oliver

## About
The purpose of this assignment is to utilize **false-color satellite imagery** to investigate the extent of wildfires in California in January 2025. This analysis walks through the steps necessary to display **Landsat 8 satellite imagery** overlaid with estimated perimeters of the **2025 LA County Palisades and Eaton Fires**.

### Background
The **Palisades** and **Eaton** fires burned across parts of Los Angeles County, leaving visible scars on the landscape. Using Landsat satellite imagery, we can highlight burned areas, compare pre- and post-fire conditions, and better understand the extent and distribution of damage. **Remote sensing** provides an objective, large-scale view that complements on-the-ground assessments and supports recovery planning and ecological monitoring.

## Repository Structure
```
.
├── hwk4-task2-false-color-oliver.ipynb      # Jupyter Notebook with analysis workflow
├── .gitignore          # Git ignore file
├── README.md           # Project overview and instructions
└── data/               # Folder to store datasets (currently empty)
```

- **analysis.ipynb**: Contains all code and visualizations for the Landsat imagery and fire perimeter overlay analysis.  
- **data/**: Should be populated with the datasets referenced below before running the notebook.  

## Data Sources
- **Eaton Fire Perimeter (Shapefile)**  
  County of Los Angeles. (2025). *Eaton fire perimeter (Version 2025-02-21) [Shapefile]*. Los Angeles County GIS Hub. [Link](https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=0)

- **Palisades Fire Perimeter (Shapefile)**  
  County of Los Angeles. (2025). *Palisades fire perimeter (Version 2025-02-21) [Shapefile]*. Los Angeles County GIS Hub. [Link](https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=1&location=34.133066%2C-118.349606%2C9.60)

- **Landsat 8 Imagery of Los Angeles County (NetCDF)**  
  Microsoft Planetary Computer. (2025). *Landsat 8 imagery of Los Angeles County (February 23, 2025) [NetCDF]*. [Link](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)

## Notes
- Before running the notebook, download the data from the links above and place them in the `data/` folder.  
- The analysis produces a **false-color map** showing burned areas (red) and the outlined fire perimeters, providing a visual assessment of fire impact.

## References
County of Los Angeles. (2025). Eaton fire perimeter (Version 2025-02-21) [Shapefile]. Los Angeles County GIS Hub. https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=0

County of Los Angeles. (2025). Palisades fire perimeter (Version 2025-02-21) [Shapefile]. Los Angeles County GIS Hub. https://egis-lacounty.hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=1&location=34.133066%2C-118.349606%2C9.60

Microsoft Planetary Computer. (2025). Landsat 8 imagery of Los Angeles County (February 23, 2025) [NetCDF]. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2
