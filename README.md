# EDA-with-Epicurious-Dataset
In my project, I performed comprehensive data cleaning and exploratory data analysis (EDA) using the EpiRecipes dataset from Kaggle. This involved handling missing, duplicate, and incorrect data, followed by visualizing key trends and insights. The project showcased my ability to derive actionable findings from data, enhancing decision-making.

# Exploratory Data Analysis
## Data Acquisition:
 1) Accessed the EpiRecipes dataset from Kaggle, which contains comprehensive recipe information such as ingredients, cuisine types, preparation times, and ratings.
 2) Downloaded the dataset in CSV format and loaded it into the Python environment using Pandas for further analysis.
 3) Ensured the dataset was properly structured for analysis by checking for issues such as encoding errors or missing data during the initial data loading process.

## Data Cleaning:

 1) Missing Data Handling: Identified columns and rows with missing values using Pandas functions and applied various imputation techniques, such as replacing missing values with the mean/median for numerical data.
 2) Duplicate Data Removal: Detected and removed duplicate entries to avoid skewed analysis and ensure data integrity.
 
 ## Data Preprocessing:

 1) Outlier Detection: Applied statistical methods to detect and handle outliers in variables like preparation time and ingredient quantities that could distort analysis results, method which I have used in this       analysis is Z_Score.
 2) To address the absence of preparation times in the dataset, I created a new column, 'Prep-Time,' based on the calorie content of each recipe. Recipes with fewer than 200 calories have a prep time of 5 to 10       minutes. Those with 200 to 500 calories take 15 to 30 minutes, while recipes with 500 to 800 calories require 30 to 60 minutes. Lastly, recipes exceeding 800 calories typically take 60 to 120 minutes. This        approach fills a significant gap in the dataset and enhances its usability.


## Exploratory Data Analysis (EDA):

1) Explored the relationships between key variables, such as preparation time and recipe rating, using correlation matrices.
2) Applied group-by operations to assess how cuisine types differ in terms of ingredient usage, preparation time, and popularity.
3) Checking the Skewness of the data witht the help of Probabilty ploting or graphs


## Data Visualization:

 1) Created interactive and static visualizations using Matplotlib, Seaborn, and Plotly to illustrate trends and distributions within the dataset.
 2) Visualized relationships between variables using scatter plots, bar charts, and box plots to uncover insights such as the top-rated Recipes or the recipes with the shortest preparation time.
 3) Used heatmaps to visualize correlations between recipe features and ratings, making it easier to detect patterns in the data.
 4) Created the Interactive Dashboard with the help of Panel library.


# Results :-

Create a 3D scatter plot for recipe clips/images, where the x-axis represents Calories, the y-axis represents Sodium, and the z-axis represents prepration Time. This plot will help visualize how preparation time influences the nutritional value (calories and protein) of the recipes.

![image](https://github.com/user-attachments/assets/611f11ab-6da2-46b0-9cfa-6e964322a33a)



![image](https://github.com/user-attachments/assets/cec9f483-b5ad-4c91-a80f-7400c62e0c0e)




### The Dashboard Images:-

![image](https://github.com/user-attachments/assets/82f57860-cdcb-4d02-a756-904f8ea3db95)



![image](https://github.com/user-attachments/assets/ae85f5fd-bc5d-452c-ab1f-6c6be938b23d)




![image](https://github.com/user-attachments/assets/02edc125-1f05-4d7a-9bcb-c6f1f1f57368)



# Conclusion

## Key Insight
1) Conclusion: The Top 10 Ingredients in Higly Rated Recipes are :-
  Pastry Dough
  Turkey Stock
  Simple Syrup
  Salsa Verde
  Turkey Giblet Stock
  Pizza Dough
  Root Vegetable Gratin
  Vegetable Stock
  Chicken Stock
  Horseradish Cream

2) As according to my analysis Overall, the correlation of 0.95 suggests a negligible relationship between preparation time and recipe ratings. This means that changes in preparation time are unlikely to predict       or influence the ratings given by users for the recipes. we can also use scatter plot, regression, hypothesis(person) to show these correlation between the preparation Time and rating.


Exploratory Data Analysis (EDA) has been successfully completed, utilizing various techniques to uncover patterns, trends, and insights within the data.


# Thank You for Visiting
