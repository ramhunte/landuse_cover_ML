**Applying Supervised Classification Approaches to Landuse Cover**

Machine learning is a powerful tool that can be leveraged to understand complex environmental patterns and make predictions. In this workflow, I use supervised classification (decision tree classifier) to identify landuse cover in Santa Barbara, CA through predictions. Land use cover is classified based off of a training data set containing small parcels of know land use cover type. I then use the spectral resolution data from Landsat 5 to identify spectral patterns from 6 bands associated with these parcels to create a predictive model. This is then applied to the entire region of Santa Barbara to predict whether a plot of land is: `green vegetation`, `dry grass or soil`, `urban` or `water`. This is workflow can fundamentally be applied to a variety of different environmental topics and is an invaluable skill that aid in addressign a variety of environmental issues.


**Note:** the data associated with this analysis is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/drive/u/1/folders/1fy6_9oC4VZ5dbkY-yB5I7Vp_DAMsBvd3). Unzip the folder and all the contents and store in your directory as follows. 


*Project Structure*
```         
houston_blackout
│   README.md
│   Rmd/html/Proj files    
│
└───data
    │   gis_osm_buildings_a_free_1.gpkg
    │   gis_osm_roads_free_1.gpkg
    │
    └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
    |   │   census tract gdb files
    |
    └───VNP46A1
    |   │   VIIRS data files
```

