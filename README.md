# DS4002-Project2
UVA DS 4002 Group 4 - Project 2 (time-series data)

## Software and Platform
Type(s) of software used: GitHub, STL decomposition [1] 

Necessary add-on packages: pandas, matplotlib, seaborn, statsmodels.tsa, scipy, re, 

The platform: Windows/ Mac

## Map of Documentation

```
UVA_DS_4002_Group_4_Project_1_text_data/
│
├── DATA/
│   ├── Air_Quality.csv
│   └── Air_Quality_Cleaned.csv
│
├── OUTPUT/
│   ├── STL_Fine_Particles_Comparison.png
│   ├── STL_Statistical_Results.csv
│   ├── pm25_trend.png
│   └── top5_pm25.png
│
├── SCRIPTS/
│   ├── data_cleaning_visualizations.ipynb
│   └── performed_analysis.ipynb
├── LICENSE
├── README.md
└── requirements.txt

```

## Instructions for Reproducing Results
Clone the GitHub repository and download the csv files containing the dataset. Run the data_cleaning_visualizations.ipynb and performed_analysis.ipynb and jupyter notebook scripts found within the SCRIPTS folder. Compare the generated results with the results within the OUTPUT folder. Our results (in the form of bar charts) reveal…
- The top 5 CDs with the highest average PM2.5 are Midtwon, Stuyvesant Town and Turtle Bay, Clinton and Chelsea, Greenwhich Village and Soho, and the Financial District. 
- The average PM2.5 concentration in the environment seems to be decreasing over time (years)
- Below are our statistics for the STL decomposition and Mann-Whitney Test:
   - Trend Slope for High Population: -0.0433 Low Population: -0.0571 p-value: 0.9296
   - Seasonal Amplitude: High Population: 3.1578 Low Population: 2.8952 p-value: 0.7239	
   - Residual RMSE: High Population: 0.8910 Low Population: 0.7011 p-value: 0.2164

## References
[1] Rob J. Hyndman and George Athanasopoulos, “STL Decomposition,” Forecasting: Principles and
Practice, OTexts, https://otexts.com/fpp2/stl.html

