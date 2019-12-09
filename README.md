# BA 505 FAB4 FINAL PROJECT README.md 
## Fall 2019
__This is the README.md document for the FAB4 Project.__

# PROJECT - Analysis of SFO EMS data

# SOURCE OF DATASET

The dataset for our project was sourced from the website Kaggle (see: https://www.kaggle.com/san-francisco/sf-fire-data-incidents-violations-and-more). The dataset gives us insights into the emergency service (EMS) calls made in the city of San Francisco. It gives us information on various parameters like different types of EMS calls received, location, time taken by the department to respond from the time it was reported until the closure time, personnel information etc. The data was downloaded on November 15, 2019.

# CHALLENGES

Volume of the data - The dataset had historical data starting from 2003-2019 with more than 500,000 rows of information. Too much of data could result in inefficient processing and hence the analysis was only performed for the recent years of information.

Pre-process the data - This required to identify if the data set needs to be cleaned. Therefore a health check was performed by identifying the following elements:
    - The attributes of the data types like whether they are continuous, categorical
    - Data that is incomplete/missing
    - Noisy data containing unnecessary information
    
Performing various tasks like analyzing the data, finding a correlation between the different attributes, sorting the data, writing appropriate code to bring the data to life by visualizations through charts and graphs.

The dataset contains mainly categorical variables.

# KEY LINKS TO THE FILES

* [DATASET (CSV FILE)](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/SFO_EMS_FINAL_120619.csv)
* [FINAL NOTEBOOK](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/FINAL_FAB4_-_Project_Notebook_-_120819.ipynb)
* [POWERPOINT FOR PRESENTATION](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/FINAL_FAB4_-_Project_Presentation_-_120819.ppt)
* [SAN FRANCISCO NEIGHBORHOOD YELP MAP](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/sf_yelp_map.png)
* [FIRE STATION LOCATION MAP](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/SFFD_Fire_Station_Locations-PNG.png)
* [SAN FRANCISCO GEOJSON DATA](https://github.com/Fairfield-University-BA505/final-project-fa2019-fab4/blob/master/san-francisco.geojson)
