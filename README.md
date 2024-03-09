# Parametric-Survival-Analysis-Exponential-Distribution-Procedure
## Exponential Distribution Survival Analysis

This project demonstrates the implementation of the Exponential Distribution for survival analysis, a parametric statistical technique used to model the time until an event occurs. The Exponential Distribution is employed to analyze the duration of unemployment spells and estimate key metrics such as median survival time and survival probabilities.

Project Description
The project involves loading a dataset containing information about unemployment spells, including the duration and censoring status. It performs data preprocessing steps and then proceeds to fit the Exponential Distribution using the lifelines library in Python. The median survival time and survival probability at a specific time point are calculated and printed. Additionally, the Exponential Survival Curve is plotted for visual analysis.

Getting Started
To run this project, you'll need Python 3 and the following libraries installed:

pandas
numpy
matplotlib
lifelines
You can install the required libraries using pip:


Copy code
pip install pandas numpy matplotlib lifelines
Usage
Clone the repository or download the project files.
Navigate to the project directory.
Run the Python script containing the code.
The script will load the dataset, preprocess the data, fit the Exponential Distribution, and display the median survival time, survival probability at a specific time point, and the Exponential Survival Curve plot.

Dataset
The dataset used in this project is available at the following URL: https://raw.githubusercontent.com/KenDaupsey/Semi-Parametric-Survival-Analysis-Cox-Proportional-Hazards-Model-for-Unemployment-Duration-Analysis/main/Survival%7EUnemployment%7EDuration.csv

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
The lifelines library for survival analysis in Python.
The dataset used in this project.
