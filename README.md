# eds220-hwk4
# Visualizing The 2017 Thomas Fire Through False Color Imagery


**Author:** Nicole Pepper

**Link to github repo:** https://github.com/nicolelpepper/eds220-hwk4

 ![ Image](https://media.cnn.com/api/v1/images/stellar/prod/171215183408-california-fire-1213-restricted.jpg?q=w_2931,h_1649,x_0,y_0,c_fill/h_447)

Image Source: CNN

### About:

The Thomas Fire, which burned over 280,000 acres in Ventura and Santa Barbara counties in December 2017, was one of California’s largest wildfires at the time. It caused widespread ecological damage, displaced communities, and left lasting environmental impacts.

False color imagery, created using satellite data from instruments like Landsat, is a useful tool for monitoring wildfire impacts. By assigning infrared bands to visible colors, these images highlight vegetation health, burn severity, and the extent of fire scars. This approach helps researchers and land managers assess recovery efforts, identify high-risk areas, and plan restoration strategies.

In this task, you will create a false color image of the Thomas Fire using remote sensing data, highlighting the fire scar and exploring how coding and data visualization support environmental monitoring.

### About this repo:

This repository contains a notebook `hwk4-task2-fire-perimeter-PEPPER.ipynb` that subsets the historic california fire boundary dataset to the Thomas Fire Boundary and a notebook `hwk4-task2-false-color-PEPPER.ipynb` exploring the burn scar for the 2017 Thomas Fire in Santa Barbara and Ventura Counties in California. For the assignment, I visualize a satellite image over the burn area in false color to highlight the burn scar and overlay it with the outline of the Thomas Fire burn perimeter.

### Datasets descriptions:

- The `thomas_fire.shp` is a shapefile containing the fire perimeter for the Thomas Fire in 2017. It is subset of a CAL FIRE dataset with historical boundaries for fires (including both natural and prescribed fires) in the state of California. The dataset has a good record of past large fires but is not complete and may be missing some fires. The thomas_fire.shp data is stored in `/data/thomas_fire` folder in the repo, I did not push the original dataset to GitHub. (Access Date: 11/20/24, [Link to original CAL FIRE data](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436/resource/6955eaf7-6452-4922-bc7d-bdac9091c538?inner_span=True))
  
- The `landsat.nc` dataset is an image from Landsat Collection 2 Level-2, from the Microsof Planetary Computer data catalogue. Landsat Collection 2 Level-2 Science Products consist of atmospherically corrected surface reflectance and surface temperature image data. Collection 2 Level-2 Science Products are available from August 22, 1982 to present. It is accessed through UCSB Workbench 1 `/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc`. (Access Date: 11/20/24, [Link to data](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2))


### Repo structure:

```
eds220-hwk4
│   README.md
|   hwk4-task2-fire-perimeter-YOURLASTNAME.ipynb
│   hwk4-task2-false-color-YOURLASTNAME.ipynb
|   .gitignore
│
└───data
    │   thomas-fire-boundary-file
```

### Acknowledgments:

This assignment was created by Carmen Galaz García, EDS 220 - Fall 2024 Instructor; shout out to our teaching assistant Annie Adams!
