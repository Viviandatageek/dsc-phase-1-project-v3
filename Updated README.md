# Aviation Data Analysis

## Overview
This project analyzes aviation incident data to identify trends, detect outliers, and extract meaningful insights that can help improve aviation safety.

## Business Understanding
### Stakeholder
- **Aviation safety regulators (FAA, NTSB)**
- **Airlines and airport authorities**
- **Pilots and aviation professionals**

### Key Business Questions
1. What are the most common causes of aviation incidents?
2. How do fatal and non-fatal incidents vary across different aircraft types?
3. Are there any outliers or trends in injury counts?

## Data Understanding and Analysis
### Source of Data
The dataset is obtained from an open aviation safety database containing records of incidents and their severity.

### Description of Data
The dataset includes numerical and categorical variables such as:
- **Number of Engines**
- **Total Fatal Injuries**
- **Total Serious Injuries**
- **Total Minor Injuries**
- **Total Uninjured**
- **Aircraft Type**
- **Weather Conditions** (IFR/VFR)

### Visualizations
#### 1. Injury Severity Distribution
![Injury Severity](r"C:\Users\Vivian\Documents\New folder\AviationData.csv\visualization1.png")

#### 2. Number of Fatalities vs Make
![Fatalities by Aircraft](r"C:\Users\Vivian\Documents\New folder\AviationData.csv\visualization2.png")

#### 3. Outlier Detection in Injury Data
![Outlier Analysis](r"C:\Users\Vivian\Documents\New folder\AviationData.csv\visualization3.png")

## Conclusion
### Key Findings
1. **Most incidents involve small aircraft rather than commercial airliners.**
2. **Weather conditions significantly impact accident severity.**
3. **Outlier detection revealed inconsistencies in reported injuries, requiring data cleaning.**

## Organization
- **Structured folders for data, notebooks, images, and presentations**
- **Easily locatable final notebook and report**
- **Linked visualizations within README**

## .gitignore
```txt
# Ignore unnecessary files
*.csv
__pycache__/
.DS_Store
.ipynb_checkpoints/
