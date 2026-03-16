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
- The top 10 most frequent words in news article titles are: student, uva, committee, university, council, board, discus, honor, new, archive
- The top 10 most frequent words in opinion article titles are: editorial, uva, student, parting, shot, virginia, must, letter, university, kurtzweil
- A two column chart containing the numeric frequency counts of the 26 most common words in the News and Opinion articles.
- Below are our statistics:
   - Chi-square statistic: 438.90
   - Degrees of freedom: 24
   - P-value: 0.000000


## References
[1] Rob J. Hyndman and George Athanasopoulos, “STL Decomposition,” Forecasting: Principles and
Practice, OTexts, https://otexts.com/fpp2/stl.html

