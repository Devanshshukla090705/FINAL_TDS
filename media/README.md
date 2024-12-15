# Data Analysis Report

## Dataset Overview
The dataset contains 2652 rows and 8 columns. Here is a brief overview of the data:
        date language   type  ... overall quality  repeatability
0  15-Nov-24    Tamil  movie  ...       4       5            1.0
1  10-Nov-24    Tamil  movie  ...       2       2            1.0
2  09-Nov-24    Tamil  movie  ...       4       4            1.0
3  11-Oct-24   Telugu  movie  ...       3       3            1.0
4  05-Oct-24    Tamil  movie  ...       3       3            1.0

[5 rows x 8 columns]

## Summary Statistics
{'overall': {'count': 2652.0, 'mean': 3.0475113122171944, 'std': 0.7621797580962717, 'min': 1.0, '25%': 3.0, '50%': 3.0, '75%': 3.0, 'max': 5.0}, 'quality': {'count': 2652.0, 'mean': 3.208898944193062, 'std': 0.797078308950042, 'min': 1.0, '25%': 3.0, '50%': 3.0, '75%': 4.0, 'max': 5.0}, 'repeatability': {'count': 2651.0, 'mean': 1.4945303658996605, 'std': 0.5983217693999956, 'min': 1.0, '25%': 1.0, '50%': 1.0, '75%': 2.0, 'max': 3.0}}

## Missing Values
{'date': 99, 'language': 0, 'type': 0, 'title': 0, 'by': 261, 'overall': 0, 'quality': 0, 'repeatability': 1}

## Correlation Matrix
{'overall': {'overall': 1.0, 'quality': 0.8256169368376611, 'repeatability': 0.5126892501045454}, 'quality': {'overall': 0.8256169368376611, 'quality': 1.0, 'repeatability': 0.3122563101138881}, 'repeatability': {'overall': 0.5126892501045454, 'quality': 0.3122563101138881, 'repeatability': 1.0}}

## Data Visualizations
![media\correlation_heatmap.png](media\correlation_heatmap.png)
![media\outlier_detection.png](media\outlier_detection.png)
![media\histogram_overall.png](media\histogram_overall.png)
![media\histogram_quality.png](media\histogram_quality.png)
![media\histogram_repeatability.png](media\histogram_repeatability.png)
Error getting insights: Failed to communicate with AI Proxy: {
  "message": "Invalid path: /openai/chat/completions"
}