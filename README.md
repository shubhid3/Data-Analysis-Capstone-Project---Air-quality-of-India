# Air Quality of Indian States (Simulated Dataset)

## Project Title
Air Quality of Indian States 

## Overview
This project analyzes a simulated air quality dataset across 19 Indian states, exploring pollutant levels, regional patterns, and their relationship with industrial activity and green cover.

## Note on Data
This dataset is fictional/simulated, created for analysis practice. It does not represent real air quality measurements.

## Tools Used
- Python (pandas, numpy)
- Matplotlib and Seaborn for charts

## Project Structure
1. Created and loaded the dataset
2. Explored it with head(), info(), describe()
3. Checked any missing values and fixed data types
4. Analysed it with groupby, sorting, and correlation
5. Visualised it with bar, grouped bar, scatter, and box charts
6. Summarised the findings in a storytelling panel

## Key Findings
- PM2.5 and PM10 show the strongest correlation with Average AQI (0.82 and 0.79), making particulate matter the primary driver of poor air quality in this dataset.
- Green cover shows a strong negative correlation with AQI (-0.74), stronger than the positive correlation between industrial units and AQI (0.54).
- North India has the highest average AQI among all regions.
- No extreme outlier states — AQI varies smoothly across states with a mild right skew. Average AQI level across the country hovers between 90 to 140.


## Future Improvements
- Bring in real government data to validate the patterns.
- South, East, and West regions are represented by only 2-3 states each, so regional averages should be read as indicative rather than fully representative.

## How to Run
1. Clone this repo
2. Install requirements: pip install -r requirements.txt
3. Open the notebook in notebooks/ and run all cells
