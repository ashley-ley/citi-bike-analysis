# Citibike Rentals Analysis (January, April, & July 2023)

## Project Overview
This project delves into the analysis of Citibike rentals for the months of January, April, and July in 2023. The primary aim of this analysis is to extract essential insights that can contribute to optimizing Citibike operations. The target audience for this project includes Citibike renters, encompassing both members and casual users.

## About Citibike
Citibike stands as the nation's largest bikeshare program, boasting a fleet of 25,000 bikes distributed across more than 1,500 locations throughout Manhattan, Brooklyn, Queens, the Bronx, Jersey City, and Hoboken. This bikeshare program offers an efficient means for individuals to reduce their commute expenses by participating in a bike-sharing initiative that provides access to bikes across the entire city. With Citibike, your next ride is never more than a few steps away.

## Tableau Workbook
My comprehensive analysis and visualizations are accessible via the follow [Tableau workbook](https://public.tableau.com/app/profile/ashley.ley/viz/CitiBike2023Analysis/Story1?publish=yes).

## Data Source
The data utilized for this analysis is sourced from CitibikeNYC's website. Specifically, we worked with the following zip files:
+ 202307-citibike-tripdata.csv.zip
+ 202304-citibike-tripdata.csv.zip
+ 202301-citibike-tripdata.csv.zip

Each zip file contains comprehensive data, encompassing details on the stations used to commence and conclude rides, the latitude and longitude coordinates of each station, and valuable information about each bike ride. The selection of data files was determined by a combination of timeliness and practicality. We aimed to ensure that our analysis reflects current data to provide meaningful insights. Moreover, we opted for months with an equal distribution throughout the year, choosing January, April, and July.

## Key Objective
The primary objective of this analysis is to identify discernible trends in Citibike rentals, with the ultimate goal of optimizing operations in areas of high demand.

## Data Wrangling
With the expert guidance of Data Analyst Shannon Lloyd, the data was successfully consolidated into a single CSV file. This process involved partitioning all stations into their respective tables, significantly enhancing the depth of our analysis. This data wrangling process is documented in a Jupyter notebook called citibike_cleansing.ipynb.

## Key Findings
Our analysis yielded two key findings:

+ Top and Bottom Stations: The top ten stations with the highest rental activity were all situated in Lower Manhattan, while the bottom ten stations with the lowest rental activity were located in Brooklyn. We attribute this discrepancy to the heightened walkability and accessibility of Lower Manhattan, in addition to the higher bike availability in that area.
  
     ![image](https://github.com/ashley-ley/citi-bike-analysis/assets/132225987/d22d633e-2799-4cd9-aca6-091236b9fe6c)

+ Rental Counts: During April and July, we observed a significant drop in rentals for both members and casual users on specific days. On April 29th, the decline coincided with a significant increase in rainstorms, while on July 16th, two violent crimes were reported. However, it's crucial to note that these findings are not definitive, and any potential connections between these occurrences remain unconfirmed. Further research indicates a potential correlation.

     ![image](https://github.com/ashley-ley/citi-bike-analysis/assets/132225987/58d51cc8-b0c6-4b1c-bd27-00305677cddd)

## Conclusion

In the ever-evolving landscape of urban transportation, Citibike stands as a beacon of accessibility, convenience, and sustainable mobility. Through the analysis of Citibike rentals in the months of January, April, and July 2023, we've aimed to find the busiest and slowest stations for renting Citbikes to better improve the rentals throughout NYC. While our findings shed light on the top-performing stations and the occasional fluctuations in rental counts, our journey is far from over. As we continue to explore the intricate web of factors that influence bike usage, we invite you to delve deeper into the wealth of insights we've uncovered through our Tableau workbook. 

Our mission remains rooted in the ongoing quest to enhance Citibike's operations and to provide both members and casual riders with a seamless, enjoyable experience. We're on the path to optimizing every "ride," making your next journey just a few steps away from excellence. Thank you for your curiosity and interest in our Citibike rentals analysis. Your enthusiasm and exploration further fuel the evolution of urban mobility, one pedal stroke at a time.

## Contact

If you have any questions or concerns regarding privacy or data handling in this project, please do not hesitate to reach out to either Lead Analyst on this project. 
+ Ashley Ley [LinkedIn](https://www.linkedin.com/in/ashley-ley1/) | [GitHub](https://github.com/ashley-ley) | [Email](yakopeca@gmail.com)
