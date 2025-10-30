# 🛳 Titanic Survival Prediction Exploratory Data Analysis Project
A data analysis and visualization project on the Titanic dataset, exploring passenger survival patterns. This project focuses on summarizing, 
and visualizing data with histograms, boxplots, violin plots, and correlation analysis to uncover trends and insights in survival across age, gender, and class.

## 🖼️ Model Output

Here’s how the Correlation Heatmap looks:

![Confusion Matrix](images/Screenshot%201.png)

Here’s the Survival Rate by Class and Sex:

![Accuracy Score](images/Screenshot%202.png)

Here’s the Survived By AgeGroup:

![Accuracy Score](images/Screenshot%203.png)

And Here’s the Age Distribution By Passenger Class and Survival on the Titanic:

![Accuracy Score](images/Screenshot%204.png)

Dataset[https://www.kaggle.com/datasets/yasserh/titanic-dataset]

## 🛠 Tools & Libraries Used

- **Python 3.x**  
- **Pandas** – Data manipulation and analysis  
- **NumPy** – Numerical operations  
- **Matplotlib** – Plotting and visualization  
- **Seaborn** – Advanced visualizations  

---
The Project Covers:
## 🔍 Features & Analysis

**1. Dataset Overview & Cleaning**  
  -  I started by exploring the Titanic dataset — checking its shape, columns, and data types to understand what kind of data I was working with.
  -  Then I looked for missing values and handled them to make the dataset clean and ready for analysis. 

**2. Summary Statistics**  
   I generated summary statistics for both numerical and categorical features.
  -  For numerical columns, I looked at the mean, median, standard deviation, and range to understand their distribution.
  -  For categorical features, I checked how many unique values they had and which categories were most common. 

**3. Visualization**
   To better understand the data, I created several visualization 
  - **Histograms** to see how numerical features like Age and Fare were distributed.
  - **Boxplots** to detect outliers and compare distributions.
  - **Correlation Heatmap** to find relationships between numerical features.
  - **Pairplots** to visualize how different features related to each other and survival.
  - **Bar plots** showing survival rates across Age Groups, Sex, and Passenger Class.
  - **Violin plots** to see how Age varied by Class and Survival status. 

**4. Feature Engineering**  
  -  I added a new feature called AgeGroup, which divides passengers into categories — Child, Teen, Adult, Middle-aged, and Senior.
  -  This helped me analyze how survival rates differed across age groups.

---

## 📈 Key Insights

- **Gender:** Females had higher survival rates than males.  
- **Class:** First-class passengers survived more often than lower classes.  
- **Age:** Children and younger adults had better survival chances.  
- **Fare:** Right-skewed distribution; some paid very high fares.  
- **Socio-economic impact:** Third-class and older passengers had lowest survival.  
- **Evacuation trends:** Violin plots show children and higher-class passengers were prioritized.  


