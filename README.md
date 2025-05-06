# COVID-19 Global Data Tracker

## Project Description
The COVID-19 Global Data Tracker is a data analysis project that explores global COVID-19 trends using the Our World in Data dataset. The project focuses on analyzing cases, deaths, and vaccination progress for Kenya, Tanzania, and India. Through data cleaning, exploratory data analysis (EDA), and visualizations, it uncovers trends, compares metrics across countries and communicates findings in a well-documented Jupyter Notebook.

## Objectives
- Import and clean the COVID-19 dataset, handling missing values and formatting dates.
- Analyze time trends for cases, deaths and vaccinations in selected countries.
- Compare metrics (cases, deaths, vaccination rates) across Kenya, Tanzania, and India.
- Create line charts, bar charts, a correlation heatmap and a pie chart to illustrate trends.
- Present insights in a Jupyter Notebook using Markdown cells for narrative explanations.

## Tools and Libraries
- **VS Code with Jupyter Extension**: Environment for developing and running the Jupyter Notebook.
- **Python Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `matplotlib`: Plotting visualizations (line and bar charts).
  - `seaborn`: Enhanced visualizations (bar charts, heatmap) with a `viridis` palette.
  - `datetime`: Date parsing and manipulation.
- **Dataset**: `owid-covid-data.csv` from Our World in Data.

## How to Run/View the Project
1. **Prerequisites**:
   - Install Python 3.x and VS Code with the Jupyter extension.
   - Install required libraries:
     ```bash
     pip install pandas matplotlib seaborn nbformat
     ```
   - Search and download `owid-covid-data.csv` from [Our World in Data](https://www.kaggle.com/datasets) and place it in your working directory.
   - Ensure `nbformat>=4.2.0` is installed:
     ```bash
     pip install --upgrade nbformat
     ```

2. **Running the Notebook**:
   - Open VS Code and create a `.ipynb` or `.py` file with Jupyter cell delimiters.
   - Copy the project code into VS Code.
   - Run all cells to generate visualizations and render the Markdown narrative.
   - Visualizations will be saved as PNG files (e.g., `total_cases_over_time.png`).

3. **Viewing Outputs**:
   - The notebook displays line charts, bar charts, a correlation heatmap, and a pie chart.
   - The Markdown cell presents key insights.
   - Export options:
     - **PDF**: Use VS Code’s “File > Export > PDF” (requires `nbconvert` and LaTeX).
     - **PowerPoint**: Insert PNG files and a screenshot of the Markdown insights.

4. **Notes**:
   - Tanzania’s vaccination data may be limited, resulting in zero values in some plots.
   - Restart the Jupyter kernel after installing dependencies.

## Insights and Reflections
### Key Insights
- **India’s High Case Burden**: India exhibits significantly higher total cases and deaths compared to Kenya and Tanzania, reflecting its large population and early exposure.
- **Tanzania’s Limited Vaccination Data**: Tanzania’s vaccination rate is notably lower, possibly due to limited data or slower rollout, as seen in the pie chart.
- **Kenya’s Moderate Position**: Kenya’s case and death counts are moderate, with a vaccination rate between India and Tanzania.
- **Strong Case-Death Correlation**: The correlation heatmap shows a strong positive relationship between total cases and deaths.
- **Vaccination Disparities**: Vaccination progress varies widely, with India leading and Tanzania lagging.

### Reflections
- **Data Challenges**: Missing data, especially for Tanzania, required robust error handling.
- **Visualization Impact**: Charts and the heatmap effectively communicated trends, despite data limitations.
- **Learning Experience**: Strengthened skills in data analysis and visualization using pandas and seaborn.
- **Future Improvements**: User input or an interactive dashboard could enhance the project.
