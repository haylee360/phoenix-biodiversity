# Phoenix Biodiversity Intactness 

![BII image](https://staticimage.undpgeohub.org/api/og?url=https%3A%2F%2Fgeohub.data.undp.org%2Fapi%2Fdatasets%2F683138801529c7aa73636710d4b55927%2Fpreview%2Fstyle.json)
Image credits: [GeoHub](https://geohub.data.undp.org/data/683138801529c7aa73636710d4b55927)

This repository explores the changes in biodiversity intactness in the Phoenix metropolitan area. Maricopa county, which Phoenix resides in, was identified as the U.S. county with the most significant increase in developed area since 2001. This rapid urban sprawl has profound implications for biodiversity and the health of surrounding natural ecosystems.

This project will investigate the impacts of urbanization by utilizing a dataset of Biodiversity Intactness Indeces (BII). The step-by-step analysis can be found in the Jupyter Notebook called `phoenix-biodiverstiy.ipynb`

## Repository structure
File map
```
├── data
│   └── tl_2020_04_cousub.shp  # Arizona county boundary data
├── .gitignore
├── README.md
└── phoenix-biodiversity.ipynb # Jupyter notebooks for analysis
```

## Data access
Data in this project were pulled from  
- Biodiversity Intactness Index: [Microsof Planetary Computer data catalog.](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) This data is a STAC collection of raster files representing the change in BII over time. 
- Arizona boundaries: [U.S. Census Bureau.](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions) This data is a shapefile of the city and county boundaries of Arizona. 

The Arizona boundary geospatial data can be found under the `data` folder located in the repository. The BII data is pulled directly form the MPC catalog. 

### Citations
[Biodiversity Intactness Index](https://planetarycomputer.microsoft.com/dataset/io-biodiversity) 

- Microsoft Planetary Computer. Biodiversity Intactness STAC collection available via https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Accesssed December 4 2024.

[Arizona counties data](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions)

- United States Census Bureau. (2022). Arizona County Subdivision 2022 TIGER/Line Shapefiles. [Data File]. U.S. Census Bureau, Geography Division. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions Accessed 4 December 2024.

## References and acknowledgements
All materials were created by [Carmen Galaz-Garcia](https://github.com/carmengg) for [EDS-220: Working with Environmental Data](https://meds-eds-220.github.io/MEDS-eds-220-course/).
