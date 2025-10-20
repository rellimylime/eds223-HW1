# Environmental Justice Mapping in Yolo County, California
## About
This repository contains code for creating bivariate maps that examine environmental justice patterns in Yolo County, California. The analysis visualizes the relationship between demographic characteristics (People of Color populations) and environmental burdens (PM2.5 pollution and traffic proximity) at the census block group level.

### HW1: Map Making Practice:
- build effective, responsible, accessible and aesthetically-pleasing maps
- practice manipulating vector and raster data to build multi-layer maps
- practice making maps in R, specifically using tmap

## Repository Structure:
```
EDS223-HW1
|   .gitignore
│   README.md
|   eds223-HW1.Rproj
│   ej_screen.pdf
|   ej_screen.qmd
└───data
     └───ejscreen
```

*Note:** The `data/` folder is included in `.gitignore` and is not tracked by version control due to file size. See below for data access instructions.

## Data

### Access
1. Download the data folder from [this Google Drive link](https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing)
2. Unzip the downloaded folder
3. Place the unzipped `data/` folder in the **root directory** of this repository
4. Verify the folder structure matches the Repository Structure shown above

### Data Sources
**EJScreen (2023)** - Environmental justice screening data from the U.S. EPA

Contains census block group level environmental and demographic indicators for the entire United States
Technical documentation: ejscreen-tech-doc-version-2-2.pdf (included in download)
Column descriptions: EJSCREEN_2023_BG_Columns.xlsx (included in download)


## Author
**Emily Miller**

[Github](https://github.com/rellimylime)

## Course Information
This analysis was completed for EDS 223: Geospatial Analysis and Remote Sensing at the Bren School of Environmental Science & Management, UC Santa Barbara.

- **Instructor:** Annie Adams
- **Assignment:** [Homework 1 - Mapping Inequality](https://eds-223-geospatial.github.io/assignments/HW2.html)

### References
- [Assignment source link](https://github.com/EDS-223-Geospatial/EDS-223-Geospatial.github.io/blob/main/assignments/HW1.qmd)
- [EPA EJScreen Site](https://19january2021snapshot.epa.gov/ejscreen_.html)
> **United States Environmental Protection Agency. 2023. EJSCREEN 2023. Retrieved: October 6, 2025, from www.epa.gov/ejscreen**
