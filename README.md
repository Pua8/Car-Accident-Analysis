# **Car Accident Analysis**
### **Goal of this project:**
Develop predictive models for assessing the severity of car accidents while gaining a comprehensive understanding of the factors contributing to their occurrence. This endeavor serves multiple purposes, including enhancing road safety, optimizing traffic management, and mitigating the societal impact of accidents. By accurately predicting accident severity and identifying causative factors, the project enables targeted safety interventions, more efficient traffic management, and evidence-based policymaking. It also empowers stakeholders to allocate resources effectively, reduce economic burdens, and continuously improve safety measures while upholding ethical considerations related to fairness and privacy in accident data analysis.

### **About Dataset:**
The dataset used was the Car Accident 2020 dataset. The information acquired on all car accidents reported in Brazil in the year 2020 in this database, which was made available by the Detran (Department of Transit). It contains a lot of information, allowing useful studies to be conducted. The main study here was to determine whether the accident was fatal or not. There are 22644 accident data and 18 columns in this base, 14 of which were categorical variables.

A number of key decisions to improve the data understanding early on in the data research was made. First, by renaming the columns in English, to make sure they were readable and understandable. The 'Age' variable was then visually examined using a histogram and a box plot to acquire an understanding of its distribution and probable outliers. Using instructive bar charts, how "Severity Code" and "Gender" were distributed were also looked at, giving more important insights on the frequency and balance of these categories.

The association between "Severity Code" and "Seatbelt Used" was also explored, with a stacked bar chart with percentages used to illustrate the relationship. This gave the opportunity to evaluate the effect of seatbelt use on accident severity. By converting the "Date and Time of Registration" column to datetime, obtaining year and month data, and charting accident trends over time, a temporal analysis was also conducted.

Additionally, the prevalence of drunk driving among drivers presented the findings in a pie chart with translated labels. The distribution of "License Categories" through analyst using a horizontal bar chart. These data comprehension processes laid the groundwork for the data science process's informed data-driven analysis and decision-making.

### **Models:**
The models, including Random Forest, Decision Tree, Support Vector Machine (SVM), Logistic Regression, and K-Nearest Neighbors (KNN), undergo hyperparameter tuning using GridSearchCV with 5-fold cross-validation to optimize performance.
The models are evaluated based on accuracy, precision, recall, F1-score, and AUC value. 

Below is a table showing performance of each model:
![image](https://github.com/user-attachments/assets/89bd022b-2820-4f90-84f2-5a04cb34615e)

Below is a the ROC curve showing AUC value of each model:
![image](https://github.com/user-attachments/assets/a7b81be3-2a73-4b6b-a3c8-328b6ea33ecb)

### **In conclusion:**
Random Forest emerges as the best model with the highest accuracy, F1-score and AUC value making it the most suitable for predicting car accident severity.

