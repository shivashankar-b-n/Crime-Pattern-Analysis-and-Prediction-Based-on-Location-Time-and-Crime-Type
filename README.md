# Crime Pattern Analysis and Prediction Based on Location, Time and Crime Type

## 📌 Project Overview

This project focuses on analysing historical crime data to identify crime patterns based on geographical location, date, time, and crime category using Machine Learning techniques.

The system explores how recorded crime categories vary across different cities and time periods. It applies data preprocessing, exploratory data analysis, statistical analysis, and machine learning classification models to understand crime patterns.

## 🎯 Objectives

- Analyse crime patterns based on geographical location.
- Identify crime trends across dates, days, months, and hours.
- Understand the distribution of different crime categories.
- Perform statistical analysis to identify associations.
- Build machine learning models to classify crime types.
- Compare model performance using evaluation metrics.

## 📂 Dataset

**Dataset:** Indian Crimes Dataset

**Source:** [Kaggle – Indian Crimes Dataset](https://www.kaggle.com/datasets/sudhanvahg/indian-crimes-dataset)

The dataset contains information such as:

- Report Number
- Date Reported
- Date of Occurrence
- Time of Occurrence
- City
- Crime Code
- Crime Description
- Victim Age
- Victim Gender
- Weapon Used
- Crime Domain
- Police Department
- Case Closed
- Date Case Closed

*Note: The dataset is not included in this repository. Download it from Kaggle and upload the CSV file when running the notebook.*

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Machine Learning

## ⚙️ Project Workflow

1. Dataset Collection
2. Data Loading and Inspection
3. Data Preprocessing
4. Exploratory Data Analysis
5. Data Visualization
6. Feature Engineering
7. Statistical Analysis
8. Machine Learning Model Development
9. Model Evaluation
10. Result Analysis and Conclusion

## 🤖 Machine Learning Algorithms

The project compares the following classification algorithms:

- Logistic Regression
- Random Forest Classifier
- Balanced Random Forest Classifier

**Target Variable:** Crime Description

**Main Features:** City, Year, Month, Day, Day of Week, Hour, Day Type, and Time Period.

## 📊 Analysis Performed

- Crime category distribution
- City-wise crime distribution
- Year-wise and month-wise crime trends
- Day-wise and hourly crime patterns
- Location and crime category association
- Chi-Square hypothesis testing
- Cramér's V association measurement
- Model performance comparison
- Confusion matrix and classification report
- Feature importance analysis

## 📁 Repository Structure

```text
crime-pattern-analysis-ml/
│
├── Crime_Pattern_Analysis_SML.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/YOUR_USERNAME/crime-pattern-analysis-ml.git
```

2. Open the project notebook in Google Colab or Jupyter Notebook.

3. Download the dataset from Kaggle.

4. Run the notebook cells in sequence.

5. Upload the dataset CSV file when prompted.

6. Execute the analysis and machine learning models.

## 📈 Expected Outcomes

- Identification of recorded crime patterns across locations.
- Understanding of crime category distributions over time.
- Statistical evidence of associations between selected variables.
- Comparison of machine learning classification performance.
- Insights into the limitations and potential improvements of data-driven crime analysis.

## ⚠️ Limitations

- Results depend on the quality and coverage of the dataset.
- Recorded crime counts are not population-normalised crime rates.
- Statistical associations do not establish causation.
- Classification results do not guarantee accurate future crime prediction.
- Model performance should be validated using independent time-based and location-based datasets.

## 🔮 Future Scope

- Develop an interactive crime analytics dashboard.
- Integrate geographical maps and GIS-based analysis.
- Evaluate models using time-based validation.
- Incorporate reliable population data for rate-based analysis.
- Explore advanced machine learning techniques.

## 👨‍💻 Author

**Shivashankar B N**

Computer Science and Engineering – Data Science  
Vemana Institute of Technology

## 🎓 Academic Project

Student Machine Learning (SML) Project

**Project Title:** Crime Pattern Analysis and Prediction Based on Location, Time and Crime Type

---

⭐ If you find this project useful, consider giving the repository a star.
