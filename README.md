# Phoenix Biodiversity Intactness 

![BII image](https://www.google.com/url?sa=i&url=https%3A%2F%2Fgeohub.data.undp.org%2Fdata%2F683138801529c7aa73636710d4b55927&psig=AOvVaw1yXXxs9bBgD9sAmJJvaKjw&ust=1733545336886000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCOjnwuKlkooDFQAAAAAdAAAAABAJ)
Image credits: [GeoHub](https://geohub.data.undp.org/data/683138801529c7aa73636710d4b55927)

This repository explores the effects of the 2017 Thomas Fire in California by using open access Landsat data and fire perimeter geospatial data. The Thomas Fire, which burned over 280,000 acres in Ventura and Santa Barbara counties in December 2017, was one of California’s largest wildfires at the time. It caused widespread ecological damage, displaced communities, and left lasting environmental impacts. This repository houses a Jupyter Notebook (`hwk4-task2-fire-perimeter-oyler.ipynb`) constructing a fire boundary for the Thomas Fire and a Jupyter Notebook (`hwk4-task2-false-color-oyler.ipynb`) visualizing a false color image of the Thomas Fire in combination with the fire's boundary. 

## Description
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
- Landsat: [Microsof Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)
- Fire Perimeter: [CalFire](https://www.fire.ca.gov/what-we-do/fire-resource-assessment-program/fire-perimeters)

The data necessary for this project can be found under the `data` folder located in the repository. 

## References and Acknowledgements
All materials were created by [Carmen Galaz-Garcia](https://github.com/carmengg) for [EDS-220: Working with Environmental Data](https://meds-eds-220.github.io/MEDS-eds-220-course/).

### Citations

Landsat data:
- Earth Resources Observation and Science (EROS) Center. (2020). Landsat 4-5 Thematic Mapper Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9IAXOVV
- Earth Resources Observation and Science (EROS) Center. (2020). Landsat 7 Enhanced Thematic Mapper Plus Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9C7I13B
- Earth Resources Observation and Science (EROS) Center. (2020). Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2 [dataset]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6 

Fire Perimeter data:
- California Department of Forestry and Fire Protection (CAL FIRE), [calfire_all.gdb], [2024-11-17], retrieved from [CAL FIRE data portal](https://www.fire.ca.gov/what-we-do/fire-resource-assessment-program/fire-perimeters).