# Titanic Dataset - Exploratory Data Analysis (EDA)

## Task Objective
Perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract insights, identify patterns, trends, and anomalies using statistical and visual methods.

## Tools Used
- **Python 3**  
- **Libraries:** pandas, numpy, matplotlib, seaborn  
- **Environment:** Jupyter Notebook  

## Dataset
The dataset used is the **Titanic dataset**, which contains information about passengers including:
- PassengerId, Name, Sex, Age, Pclass, SibSp, Parch, Ticket, Fare, Cabin, Embarked, Survived

## Steps Performed

1. **Data Overview**
   - Checked the structure, data types, and missing values using `info()` and `describe()`.
   - Counted categorical values using `value_counts()`.

2. **Data Cleaning**
   - Filled missing values for `Age` with median and `Embarked` with mode.
   - Dropped `Cabin` column due to too many missing values.

3. **Univariate Analysis**
   - Plotted histograms for numerical columns (`Age`, `Fare`).
   - Boxplots for `Age` across passenger classes.
   - Countplots for categorical features (`Pclass`, `Sex`) to visualize survival distribution.

4. **Bivariate / Multivariate Analysis**
   - Encoded categorical columns (`Sex` and `Embarked`) for correlation analysis.
   - Plotted correlation heatmap and pairplots for numerical features.
   - Analyzed survival rates by `Pclass`, `Sex`, and `Embarked`.

5. **Insights & Observations**
   - Females had higher survival rates than males.
   - First-class passengers survived more compared to other classes.
   - Passengers paying higher fares tended to survive more.
   - Large families had slightly lower survival probability.
   - Most passengers boarded from 'S' port.

## Deliverables
- **Jupyter Notebook:** Contains all code, visualizations, and observations.  
- **PDF Report:** Exported from the notebook summarizing all findings and visuals.  

## How to Run
1. Clone or download the repository.
2. Open the Jupyter Notebook (`Titanic_EDA.ipynb`) in Jupyter or VS Code.
3. Run all cells to generate visuals and see insights.

## Repository Structure
Task5_Titanic_EDA/
│
├── Titanic_EDA.ipynb # Jupyter Notebook with code and analysis
├── titanic.csv # Titanic dataset 
├── README.md # This README file

## References
- Titanic Dataset from [Kaggle](https://www.kaggle.com/c/titanic)
- Python Libraries: pandas, seaborn, matplotlib, numpy

Note : The python script is attached along with the output screenshots.
