# Titanic Dataset – Exploratory Data Analysis (EDA)

#Objective
To explore and understand the Titanic dataset using statistical methods and visualizations. This helps identify important features, patterns, correlations, and anomalies before building machine learning models.

#Tools & Libraries Used
- Google Colab – Environment
- Python – Programming language
- Pandas – Data handling
- NumPy – Numerical operations
- Seaborn – Data visualization
- Matplotlib – Plotting
- Scikit-learn – Preprocessing 

#Steps Performed

1. Data Loading
- Loaded the pre-cleaned dataset from Task 1 using Pandas.

2. Summary Statistics
- Used `.describe()` to view:
  - Mean, median, standard deviation
  - Min/max ranges
  - Counts of values for each numeric column

 3. Visualizations
- Histograms: To check the distribution of `Age` and other features
- Boxplots: To detect outliers visually
- Pairplot: To observe interactions between multiple features
- Heatmap: To understand correlations between numerical features

  4. Correlation Analysis
- Found that `Pclass` and `Fare` are highly correlated
- Positive correlation between `Fare` and `Survived`
- Negative correlation between `Pclass` and `Survived`

 5. Inference & Patterns
- 1st class passengers had higher chances of survival
- Passengers who paid higher fares were more likely to survive
- Majority of passengers were from 3rd class and had lower survival rates
- Age distribution is close to normal with minor right skew

# Key Visuals
- Distribution plot of Age
- Boxplot showing Age outliers
- Correlation heatmap
- Pairplot showing feature relationship
# Conclusion
This EDA helped uncover key insights in the Titanic dataset, such as the importance of `Pclass`, `Fare`, and `Age`. These will guide better feature selection for modeling in future tasks.

