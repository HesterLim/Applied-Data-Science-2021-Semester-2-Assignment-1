# Applied-Data-Science-2021-Semester-2-Assignment-1

- Student Name: Hester Lim 
- Student ID: 1044793
- Due Date: Friday 16th of August 11:59:00 am (AEST).
- Report Link: https://www.overleaf.com/8652289343cfnqwdbjqscc

# Dependencies
- Language: Python 3.8.3
- Packages / Libraries: pandas, numpy, matplotlib.pyplot, seaborn, warnings, bokeh, sklearn, statsmodels, folium. 

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- NYC Collision Dataset : https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95 

# Directory
- `raw_data`: Store all the raw data files. The raw data file can be downloaded by opening the terminal and changing the depository to the raw_data file and using wget to download the datasets used. The steps involved could be summarised as below in the terminal:
    - From the main file : cd raw_data
    - To Download the file : wget -i datafile.txt
- `preprocessed_data`: Contains all the preprocessed data files. The script in data-preprocessing-nb.ipynb automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Output and save all the figures generated in analysis-and-geospatial-visualization.ipynb here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
    - data-preprocessing-nb.ipynb for "Preprocessing" and/or "Exploratory Data Analysis".
    - analysis-and-geospatial-visualization.ipynb for "Analysis and Geospatial Visualisation".
    - statistical_model_nb.ipynb for "Statistical Modelling".
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.

# Recommended steps to run the notebooks
1. Download the datasets into raw_data using the wget. More information in the section above
2. Run data-preprocessing-nb.ipynb
3. Run analysis-and-geospatial-visualization.ipynb
4. Run statistical_model_nb.ipynb
