# **Healthcare Cost Analysis  for HMO**

## **Overview**:

This project focuses on analyzing healthcare cost information from a Health Management Organization (HMO) to identify key factors influencing healthcare costs. The objective is to provide actionable insights that help reduce costs and accurately predict individuals who may incur high healthcare expenses. The dataset includes information about individuals' demographics, health status, and behaviors.

## **Technologies Used**:

- R Studio: For data analysis, visualization, and modeling.

- CSV: Dataset format used for data acquisition.

- R Libraries: For data cleaning, transformation, and statistical analysis.

## **Features**:

### **Predictive Modeling:**

Developed SVM, KSVM, and Rpart models to predict which individuals are likely to incur high healthcare costs.

### **Descriptive Statistics:**

Conducted statistical analysis to understand key drivers of healthcare costs.

### **Data Visualizations:**

Created bar plots, histograms, box plots, and scatterplots to visualize relationships between healthcare costs and factors like age, BMI, smoking, physical activity, and hypertension.

### **Data Analysis Process**:

- **Data Acquisition:** 

Loaded the dataset of healthcare cost information from an HMO.

- **Data Cleansing:**

Handled missing values and corrected incorrect values using interpolation techniques.

- **Data Transformation:** 

Created new columns for cost status and other key variables to aid in analysis.

- **Modeling Techniques:**

1. SVM Model:

Used to classify individuals based on predicted healthcare costs.

2. KSVM Model: 

An advanced version of SVM used for better accuracy.

3. Rpart Model: 

Implemented for decision tree-based classification.

### **Descriptive Statistics & Visualizations**

- Age vs. Cost: 

Showed trends where healthcare costs rise with age after a decline in young adulthood.

- BMI Distribution:

Observed a normal distribution with most values clustered around the average BMI.

- Cost Distribution: 

Healthcare costs showed a right-skewed distribution with a small proportion of very high costs.

- Scatterplots:

Revealed correlations between healthcare costs and behaviors such as smoking and physical activity.

## **Actionable Insights**:

- Encourage Healthy Habits:

Promote regular exercise to reduce healthcare costs.

- Smoking Cessation: 

Implement programs to help individuals quit smoking, as smokers tend to have higher medical costs.

- Monitor High-Risk Individuals:

Identify and manage individuals with chronic conditions (e.g., hypertension) to prevent costly complications.
