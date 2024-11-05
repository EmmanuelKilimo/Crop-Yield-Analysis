# Crop-Yield-Analysis
The project focuses on analyzing agricultural  survey data to identify and understand various issues faced by farmers across different districts. While doing this, enumerator performance is  assessed to through data quality checks.

# Key Tasks and Findings

Ascertained standard box dimensions & non-null yield output.
Ascertained true weights of harvested crops (Dry weight < Wet weight).
Implemented compliance checks.


Represented the spatial distribution of data points on a map using latitude and longitude columns.
Assessed enumerator performance using accuracy scores.
Implemented a Density-Based Spatial Clustering of Applications with Noise (DBSCAN) to dentify cluster points and outliers based on enumerator density.


Computed average yield for each observation (farm) in mt/ha.
Flagged outlier yields.

Identified and counted challenges facing farmers per district.

Drafted a short report to share with the supervisor.

Tools and Libraries Used
Pandas: For data manipulation and analysis.
SQL: For data querying and integrity checks.
Folium: For creating interactive maps to visualize spatial data.
Scikit-learn: For applying clustering techniques (e.g., DBSCAN) to identify outliers.



