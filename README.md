# ETO5513-Assessment-2-Team-Project

This repository contains the necessary files to produce the ETO5513 Assessment 2 Team Project report analysing the City of Melbourne Pedestrian Counting System (counts per hour) data set. 

## Description

This project explores the pedestrian data collected from multiple sensor locations to explore temporal and spatial patterns between August 2023 and August 2025. Key analysis includes seasonality trends, average monthly pedestrian flows per hour, and spatial mapping of pedestrian activity. The goal is to explore pedestrian trends for urban planning purposes. It is presented as a report using R and Bookdown packages.

## Data

* Dataset: [City of Melbourne Pedestrian Counting System (counts per hour)](https://data.melbourne.vic.gov.au/explore/dataset/pedestrian-counting-system-monthly-counts-per-hour/export/) (stored as an R dataframe)
* Variables include sensor location ID, sensing date, hour of the day, total pedestrian counts, sensor name and sensor coordinates (lat, lon).
* Data sources and citations are provided in the `references.bib` file.

## Dependencies

Please ensure your device complies with the below:

* [R 3.6.0+](https://posit.co/download/rstudio-desktop/) downloaded on local device
* [RStudio Cloud](https://posit.cloud/) account or [RStudio Desktop](https://posit.co/download/rstudio-desktop/) downloaded on local device
* 64-bit operating system
* Packages used: tidyverse, knitr, renv, and others listed in `renv.lock`
* The project uses `renv` for package version control to ensure consistent package versions.

## Use

This project is built using the **Bookdown** package. To compile the report:

1. Clone the repository.
2. Open the R project file or R Markdown file `ETO5513 Assessment 2 Team Project.Rmd`.
3. Restore the R environment using:

   ```r
   renv::restore()

## Authors

Megan O'Rorke 
[moro0003@student.monash.edu](mailto:moro0003@student.monash.edu)

Aldwin Chong
[acho0011@student.monash.edu](mailto:acho0011@student.monash.edu)

## Version History

* See [commit change]() or See [release history]()
