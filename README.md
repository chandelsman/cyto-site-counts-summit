# cyto-site-counts-summit
Quarterly report of site counts for NGYN cytology summarized by diagnostic category

## Overview

Summary (counts and frequency) of diagnoses on cytology cases grouped by anatomical site. Data are compiled monthly for UCH South and quarterly for Summit Pathology Laboratories.

## Data

### Summit Pathology (quarterly)

Data are queried from the LigoLab SQL database. The query is in the src subfolder in the Cytology-site-count-summit project folder (in IT Projects). The query is run with VS Code using the SQL Server (mssql) extension. Data are saved as a csv file (site-counts-YYYY-Q#.csv) in the project data folder.

## Ouput

The Rmarkdown script can be "knit with parameters" and prompts for "year", "quarter", and "Input dataset". The output can be opened in a browser and printed to the projects output folder as a PDF (scale to 85%).

## Distribution

The PDF report is sent to the Director of Cytology: Sara Kane (skane@summitpathology.com).