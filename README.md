# TitanicSmallDA
A Small Data Analysis on the Titanic dataset using Python (Pandas, Seaborn, Matplotlib)

#  Titanic Data Analysis

Exploratory data analysis (EDA) of the Titanic dataset using Python, Pandas**, **Matplotlib**, and **Seaborn**.  
This project investigates survival patterns based on age, gender, ticket class, and fare, visualizing trends through statistical plots and heatmaps.

##  Overview

The Titanic dataset is one of the most well-known datasets in data science, often used for introducing data cleaning, exploration, and visualization techniques.  
This analysis focuses on understanding the correlations between **passenger demographics** and **survival probability**.

##  Technologies Used

 🐍 Python 3  
 📦 Pandas – data manipulation and analysis  
 📈 Matplotlib – 2D and 3D plotting  
 🌈 Seaborn – statistical visualization  
 🧮 NumPy – numerical operations  

##  Key Analysis Steps:

1. **Data Loading and Inspection**
   - Read the dataset directly from GitHub using Pandas.
   - Explored data structure and statistics (`.info()`, `.describe()`).

2. **Feature Engineering**
   - Created categorical groups:
     - `AgeGroup`: Children, Teens, Young Adults, Adults, Seniors
     - `FareGroup`: Extremely Poor → Extremely Rich

3. **Exploratory Data Analysis**
   - Calculated survival percentages by:
     - Gender  
     - Age group  
     - Fare group  

4. **Data Visualization**
   - **Bar charts**: survival rate by gender, age, and fare  
   - **Heatmaps**: multi-dimensional relationships between age, fare, and sex  
   - **3D scatter plots**: age vs fare vs survival
    
##  Example Visuals

- Bar plots showing survival rates by demographic features  
- Heatmaps of survival probability by fare and age  
- 3D visualization of age, fare, and survival  

 ## Results Summary

- **Females** had a significantly higher survival rate.  
- **Younger passengers** (children and teens) had increased survival chances.  
- **Higher fare classes** correlated with better survival probabilities.  

## How to Run

Clone this repository and open the notebook in **Jupyter** or **Google Colab**:

```bash
git clone https://github.com/<evikalpakidou>/TitanicSmallDA.git
cd TitanicSmallDA.git
