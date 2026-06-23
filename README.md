# Resume_Screening_Day_2 - Data Preprocessing & EDA

End-to-end data preprocessing and exploratory data analysis pipeline for resume classification dataset. Built as part of Day 2 of the ML learning journey.

## 📋 Project Overview

This notebook performs complete data cleaning, feature engineering, and EDA on a resume dataset with 24 job categories. The processed data is ready for ML model training.

### Key Steps Completed
1. **Data Loading & Cleaning** - Handle duplicates, missing values
2. **Text Preprocessing** - Clean resume text, remove URLs/special chars
3. **Feature Engineering** - Extract resume length, skills count, experience bins
4. **TF-IDF Vectorization** - Convert text to numerical features
5. **EDA & Visualization** - Category distribution, skills frequency, experience analysis

## 📊 Dataset

**Source:** Resume Dataset by Snehaanbhawal  
**Size:** 962 resumes across 24 categories  
**Columns:** `Resume_ID`, `Category`, `Resume_Text` + engineered features

**Categories include:** Data Science, Software Engineer, Web Developer, HR, Sales, etc.

## 🚀 How to Run

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
### Execution
1. Download `resumes.csv` from the source link below
2. Place file in the same directory as notebook
3. Run all cells sequentially in Jupyter Notebook/Colab

*Dataset Link:* [UpdatedResumeDataset.csv](https://github.com/snehaanbhawal/Resume-Parser/blob/master/UpdatedResumeDataset.csv)

## 📁 Output Files

After running the notebook, these files will be generated:
File | Description
`cleaned_resumes.csv` | Cleaned dataset after removing duplicates & missing values
`feature_engineered_resumes.csv` | Final feature matrix with TF-IDF vectors
`category_dist.png` | Bar chart: Resume category distribution
`skills_freq.png` | Bar chart: Top 15 skills frequency
`experience_pie.png` | Pie chart: Experience level distribution
## 📈 Key Insights from EDA

- *Most common category:* Data Science / Software Engineering roles dominate
- *Top skills:* Python, SQL, Java, ML, Django appear most frequently  
- *Experience distribution:* 60%+ resumes fall in 0-5 years experience range

## 🛠️ Tech Stack

- *Libraries:* Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Regex
- *Vectorization:* TF-IDF with 1000 features, English stop words removed
- *Visualization:* Matplotlib + Seaborn for EDA plots

## 📝 Notebook Structure
Cell 1-2:  Libraries + Data Loading
Cell 3-5:  Data Cleaning - Duplicates & Missing Values
Cell 6:    Text Cleaning Function
Cell 7:    Feature Engineering
Cell 8:    TF-IDF Vectorization
Cell 9:    Save Processed Files
Cell 10-12: EDA Visualizations
## 👨‍💻 Author
Warda Ejaz
Created as part of ML/Data Science learning series - Day 2  
Date: 23-June-2026

## 📄 License

This project is for educational purposes only.
