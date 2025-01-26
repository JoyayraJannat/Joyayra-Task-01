# Joyayra-Task-01
Biostatistics and Ecological Statistics Visualization
## Table of contents
- [Introduction](Introduction)
- [Description of the Dataset](Description_of_the_Dataset)
- [Descriptive Statistics](Descriptive_Statistics)
- [Data Visualization](Data_Visualization)
- [Usage](Usage)
- [Correlation Matrix](Correlation_Matrix)
- [Conclusion](Conclusion)

##  Introduction
This project focuses on analyzing and visualizing biostatistical and ecological data to identify key patterns and relationships. The analysis helps understand ecosystem health by examining factors like environmental conditions, pollution levels, and species populations.

## Description of the Dataset
The dataset used in this project contains the following key columns:

•	Temperature (°C): Records environmental temperature values.

•	Pollution Level (ppm): Represents pollution levels in parts per million.

•	Species Population: Tracks population counts of species over time.

•	Region: Geographic locations associated with species populations.

•	Timestamp: Time-series data for population trends.

The dataset is loaded, preprocessed, and analyzed to ensure data integrity and provide meaningful insights.

## Descriptive Statistics
The project computes and presents the following statistics for key columns:
## •	Mean:
Average value of the data.
## •	Median:
Middle value when data is sorted.
## •	Minimum and Maximum: 
Range of values in the dataset.

These statistics offer a comprehensive overview of the data distribution.

## Data Visualization
The project includes the following visualizations:

## Distribution Analysis
## •	Histograms:
o	Visualize the distribution of temperature, pollution levels, and species populations.

o	Include Kernel Density Estimation (KDE) for smooth curve visualization.
## Box Plot
•	Species Population Spread:

o	A box plot illustrates the spread of species population data across different regions.

o	Highlights variations and potential outliers.
## Trend Analysis
## •	Line Plots:
o	Display trends in species population over time.

o	Separate trends are shown for each species, providing a clear view of population dynamics.
## Usage
## a.  Install Dependencies: 
Make sure Python 3.x is installed along with the following libraries:

o	pandas

o	matplotlib

o	seaborn

Install them with

            pip install pandas matplotlib seaborn
            
## b.  Run the Script:
•	 Update the file_path variable in the script to point to your dataset.

•	Execute the script:

      python task_01.py
      
## c.  Interpret Outputs:
•	Visualizations and descriptive statistics will appear in the terminal or as plot outputs.
## Example Outputs
•	Histogram: Distribution of temperature, pollution level, and species population.

•	Box Plot: Spread of species population across regions.

•	Line Plot: Trends of species populations over time for different species.

•	Correlation Heatmap: Relationships between temperature, pollution levels, and species population.

![image](https://github.com/user-attachments/assets/d96fc68b-c268-48b6-bd33-55b018f264c8)
![image](https://github.com/user-attachments/assets/d75c8020-d8a5-4d80-b07f-dcfdb77aa01b)
![image](https://github.com/user-attachments/assets/bbc1a5fe-32ae-4650-9743-13d369155dc8)



## Correlation Matrix
A correlation matrix is computed to examine relationships between the following variables:

•	Temperature (°C)

•	Pollution Level (ppm)

•	Species Population

The correlation matrix is visualized using a heatmap, which highlights:

•	Positive correlations (direct relationships).

•	Negative correlations (inverse relationships).

•	The strength of these relationships (closer to -1 or 1 indicates stronger correlation).


## Conclusion
The project reveals several critical insights:

1.	Distribution Patterns: Histograms and descriptive statistics highlight the range and central tendency of key variables.
	
2.	Species Variability: Box plots show significant differences in species populations across regions, with notable outliers.
	
3.	Population Trends: Time-series plots reveal growth or decline trends in species populations, helping identify seasonal or long-term changes.
	
5.	Inter-variable Relationships: The correlation matrix uncovers dependencies between environmental factors and species populations, shedding light on the impact of pollution and temperature on ecosystems.
	
These findings provide a foundation for further research and decision-making in ecological studies.
