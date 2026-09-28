# AI and Data Analytics Approach for Pharmaceutical Quality and Safety Assessment

## Project Overview

This project applies **data analytics and artificial intelligence/machine learning (AI/ML)** techniques to pharmaceutical quality and safety-related data.

The workflow covers:

1. Dataset collection and understanding
2. Data quality assessment
3. Data cleaning and preprocessing
4. Exploratory Data Analysis (EDA)
5. Statistical analysis
6. Data visualization
7. Identification of important patterns and relationships
8. AI/ML-based classification or prediction, where appropriate
9. Model evaluation
10. Interpretation of results and pharmaceutical-quality insights

> **Academic-use note:** This project is intended for educational and analytical purposes. It is not a validated pharmaceutical quality-control or regulatory decision-making system.

---

## Project Description

Pharmaceutical quality datasets can contain multiple analytical and quality-related variables. Manually examining these variables can make it difficult to identify patterns, unusual observations, and relationships that may be useful for quality assessment.

This project uses Python-based data analytics to clean and explore pharmaceutical quality data and uses visualization techniques to communicate important findings. An appropriate machine-learning model is also applied, depending on the structure of the dataset, to explore the potential of AI for pharmaceutical quality assessment.

The final project demonstrates an end-to-end workflow:

**Raw/Source Data → Cleaning → EDA → Visualization → AI/ML → Evaluation → Findings**

---

## Dataset

### Dataset used

**Drug QA Cleaned Dataset**

The project uses the cleaned pharmaceutical quality/QA dataset prepared for this analysis.

### Dataset link

If the dataset was created or cleaned specifically for this project and is not publicly hosted, the local project file should be used rather than an invented public URL.

**Dataset file:** `drug QA cleaned 2.xlsx`

If a public/original dataset was used to create this cleaned dataset, add its verified source URL here:

`[ADD VERIFIED ORIGINAL DATASET URL HERE]`

> Do not claim a public dataset link unless it is the actual source of the dataset used in the project.

### Dataset contents

The exact number of rows, columns, variables, and data types should be taken from the final dataset used in Google Colab.

The project analyzes pharmaceutical quality-related variables and investigates their distributions, relationships, possible outliers, and association with quality-related outcomes where such variables are available.

---

## Technologies Used

### Software and platforms

- Google Colab
- Microsoft Excel
- Python

### Python libraries

- **Pandas** – data loading, cleaning, manipulation, and analysis
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Scikit-learn** – machine learning and model evaluation
- **OpenPyXL** – Excel file handling

### Analytical techniques

- Data cleaning
- Missing-value analysis
- Duplicate detection
- Descriptive statistics
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation analysis
- Outlier analysis
- Data visualization
- Machine-learning classification/prediction
- Model evaluation
- Feature-importance analysis, where applicable

---

## Project Structure

```text
Project/
│
├── Veeresh_AI_and_Data_Analytics_Project.ipynb
│   └── Complete Python/Colab analysis
│
├── drug QA cleaned 2.xlsx
│   └── Cleaned pharmaceutical QA dataset
│
├── requirements.txt
│   └── Required Python libraries
│
├── README.md
│   └── Project documentation and instructions
│
└── Veeresh__AI and Data Analytics Approach for Pharmaceutical Quality
    and Safety Assessment ProjectReport.docx
    └── Complete project report
```

---

## Setup and Run Instructions

### Option 1: Run using Google Colab

1. Open Google Colab:
   https://colab.research.google.com/

2. Open the project `.ipynb` notebook.

3. Upload the dataset:
   - Open the **Files** panel in Colab.
   - Upload `drug QA cleaned 2.xlsx`.

4. Install/import the required libraries.

5. Run the notebook cells from top to bottom.

6. Check the outputs after each major section:
   - Dataset loading
   - Data inspection
   - Data cleaning
   - EDA
   - Visualizations
   - AI/ML
   - Model evaluation

7. Save/download the completed notebook as `.ipynb`.

### Install required libraries

If necessary, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

In Google Colab, many of these libraries are already installed.

---

## EDA Workflow

The notebook should perform EDA in the following order:

```text
Load Dataset
     ↓
Check Shape
     ↓
Check Columns
     ↓
Check Data Types
     ↓
Check Missing Values
     ↓
Check Duplicates
     ↓
Descriptive Statistics
     ↓
Univariate Analysis
     ↓
Bivariate Analysis
     ↓
Correlation Analysis
     ↓
Outlier Analysis
     ↓
Visualizations
     ↓
EDA Findings
```

---

## AI/ML Workflow

Where the dataset contains an appropriate target variable, the AI/ML section follows:

```text
Select Features
      ↓
Define Target
      ↓
Prepare Data
      ↓
Train/Test Split
      ↓
Train Model
      ↓
Generate Predictions
      ↓
Evaluate Model
      ↓
Interpret Results
```

Possible algorithms include:

- Logistic Regression
- Decision Tree
- Random Forest

The final algorithm should be selected based on the actual dataset and project objective.

---

## Key Information

### Project title

**AI and Data Analytics Approach for Pharmaceutical Quality and Safety Assessment**

### Main goal

To demonstrate how data analytics and AI/ML can be used to analyze pharmaceutical quality-related data and generate useful analytical insights.

### Main analytical stages

- Data preprocessing
- Data cleaning
- EDA
- Visualization
- Statistical analysis
- AI/ML
- Model evaluation
- Interpretation

### Important interpretation rule

EDA can identify associations and patterns, but an observed relationship does **not automatically establish causation**.

Similarly, an academic machine-learning model should not be treated as a validated pharmaceutical quality-control or regulatory system without appropriate validation, external testing, and regulatory consideration.

---

## Expected Outputs

The completed project should produce:

- Cleaned dataset
- Descriptive statistics
- EDA results
- Graphs and visualizations
- Correlation analysis
- Outlier analysis
- AI/ML model results, where applicable
- Model-performance metrics
- Key findings
- Final project report

---

## Final Submission Files

The final submission should contain the four required files:

```text
1. Project_Code.ipynb
2. requirements.txt
3. ProjectReport.docx
4. README.md
```

The filenames should follow the naming instructions provided by the institution.

---

## References

1. International Council for Harmonisation (ICH). **ICH Q9(R1): Quality Risk Management.**
2. International Council for Harmonisation (ICH). **ICH Q10: Pharmaceutical Quality System.**
3. U.S. Food and Drug Administration (FDA). **Process Validation: General Principles and Practices — Guidance for Industry.**
4. U.S. Food and Drug Administration (FDA). **Data Integrity and Compliance With Drug CGMP: Questions and Answers — Guidance for Industry.**
5. U.S. Food and Drug Administration (FDA). **Considerations for the Use of Artificial Intelligence to Support Regulatory Decision-Making for Drug and Biological Products.**
