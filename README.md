# Study Data Analysis - Adam Marley 
  
## Overview

This project analyzes my study data from July 30, 2023, to August 6, 2024. The analysis was performed using R within an R Notebook environment. The data was initially stored in a modified Microsoft Excel sheet and later saved as a CSV file named `studydata_aug.csv`. This project explores the total minutes and hours spent studying, evaluates time spent across different study programs, and visualizes the data to uncover trends and distributions over time.

## Project Structure 

The project is organized into the following sections:

1. **Importing Data:**
   - The CSV file `studydata_aug.csv` is loaded, and the initial rows are inspected to understand the data structure.
   
2. **Calculating Total Study Time:**
   - The total minutes studied across all days is calculated.
   - Total study hours are derived from the total minutes, and a summary of daily study hours is provided.

3. **Data Visualization:**
   - A boxplot is generated to visualize the distribution of hours studied each day.
   - The time spent on different study programs (CS50, Py Dev/RealPy, SpringBoard, Pre Masters, Masters Program) is evaluated and visualized using a bar chart.

4. **Timeline Analysis:**
   - The evolution of study minutes per day is visualized over time using a timeline plot.
   - The dataset is cleaned to remove study data for Sundays, and a new timeline plot is generated to reflect this change.

5. **Distribution Analysis:**
   - A histogram is created to analyze the distribution of daily study minutes, excluding Sundays. The plot reveals a bimodal distribution, which is interpreted in the context of the study programs.

## Key Skills Demonstrated

- **Data Manipulation:** 
  - Effective handling and processing of data using R, including filtering, aggregating, and cleaning the dataset.
  
- **Data Visualization:**
  - Creation of informative and visually appealing plots using `ggplot2`, including boxplots, bar charts, line plots, and histograms.

- **Statistical Summary and Interpretation:**
  - Summarizing key statistics and interpreting the results to derive meaningful insights from the data.

- **Data Cleaning:**
  - Identification and removal of outliers (e.g., low study times on Sundays) to improve the accuracy of the analysis.

## Tools and Libraries Used

- **R Programming Language:** The project is entirely written in R, showcasing the power of R for data analysis and visualization.
- **ggplot2:** A powerful data visualization package in R used to create a variety of plots for the project.
- **Base R Functions:** Utilized for data manipulation, summary statistics, and file handling.
- **R Notebook:** The project is structured within an R Notebook, allowing for interactive analysis and easy integration of code, results, and commentary.

## Key Insights

- **Study Consistency:** 
  - The analysis revealed that even with a full-time unrelated job, I was able to consistently study approximately 3 to 4 hours per day on most days.

- **Program-Specific Analysis:**
  - The time spent across different study programs was quantified, helping to identify which programs received the most attention.

- **Data Cleaning Impact:**
  - Removing Sunday study data (which primarily consisted of low values from reviewing Anki Flash Cards) significantly improved the clarity of the trend analysis.

## Conclusion

This project not only showcases my ability to analyze and visualize data using R but also demonstrates my commitment to consistent study habits over an extended period. The skills demonstrated in this project are directly applicable to data science roles that require data manipulation, analysis, and visualization. 

## Acknowledgments

- **AI Assistants (ChatGPT, Claude):** Consulted for learning about inputs, parameters, and error handling.
- **Stack Overflow & GeeksforGeeks:** Used for research and problem-solving.
- **Grammarly:** Utilized for editing and refining the textual content of the project.
