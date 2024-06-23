# Animal Conditions Classification

## Overview

This project aims to leverage data analytics in veterinary medicine by integrating detailed symptom data and comprehensive health records into a predictive model. The objective is to enhance the accuracy and speed of diagnosing health conditions in animals, potentially saving lives and improving animal welfare across various settings.

## Data Analytics Life Cycle

### 1. Data Discovery

- **Project Overview:** 
  The project focuses on using data analytics to improve diagnostic processes in veterinary medicine.
  
- **Learning the Business Domain:** 
  Understanding veterinary care, disease prevalence, progression, and treatment outcomes.
  
- **Resources Available:** 
  Collaboration between data scientists and veterinarians, utilizing advanced data analysis tools and technologies.
  
- **Framing the Problem:** 
  Addressing challenges like species diversity, symptom variability, and disease complexity.
  
- **Identifying Key Stakeholders:** 
  Involves veterinarians, care providers, and researchers.
  
- **Developing Initial Hypothesis:** 
  Formulating hypotheses based on symptom and health condition relationships.
  
- **Identifying Potential Data Sources:** 
  Gathering diverse data sources, including veterinary records and online datasets.

### 2. Data Preparation

- **Analytic Sandbox Establishment:** 
  Controlled environment for data exploration.
  
- **Data Exploration and Preparation:** 
  Conducting data exploration and ETLT (Extract, Transform, Load) processes.
  
- **Data Conditioning:** 
  Handling missing values and duplicates, encoding categorical data.
  
- **Survey and Visualize:** 
  Using descriptive statistics and visualizations to understand data distribution and relationships.
  
- **Tools for Data Preparation:** 
  - `pandas` for data manipulation.
  - `Seaborn` and `Matplotlib` for data visualization.

### 3. Model Planning

- **Data Exploration and Variable Selection:** 
  Splitting data into training and testing sets.
  
- **Model Selection:** 
  Using Support Vector Machine (SVM) for classification.
  
- **Common Tools for Model Planning:** 
  - `train_test_split` for data splitting.
  - `StandardScaler` for feature scaling.
  - Creating an SVM instance with specified parameters.

### 4. Model Building

- **Model Training and Testing:** 
  Splitting dataset, performing feature scaling, training SVM model, and evaluating performance.
  
- **Results:** 
  - Training accuracy: 97%
  - Testing accuracy: 98%
  - Overall accuracy: 97.7%
  
- **Software Used:** 
  - `sklearn` for model selection.
  - `pandas` for data manipulation.
  - `numpy` for array operations.
  - `Seaborn` and `Matplotlib` for visualization.

### 5. Communicate Results

- **Key Findings:**
  - Example 1: Tiger - Dangerous condition.
  - Example 2: Chicken - Not dangerous condition.
  
- **Major Insights:** 
  Achieved objective, statistically significant results, reliable predictions.
  
- **Recommendations:** 
  - Refine feature selection.
  - Regularly evaluate model performance.
  - Expand dataset for better generalization.
  - Develop user-friendly interface.

### 6. Operationalize Results

- **Key Findings:**
  - Model accuracy: 97.7%
  - Importance of training data quality.
  - Identifying contributing factors for classification accuracy.
  
- **Future Recommendations:**
  - Incorporate additional features like behavioral cues and vocalizations.
  - Explore image analysis techniques for better feature identification.

## Conclusion

The Animal Conditions Classification project shows promise in accurately diagnosing critical conditions in animals based on symptom data. By following the recommendations and continuing to refine the model, this tool can provide significant support to veterinarians and animal caretakers, ensuring timely and appropriate care for animals.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: `sklearn`, `pandas`, `numpy`, `seaborn`, `matplotlib`

### Installation

```bash
pip install -r requirements.txt
```

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/username/animal-conditions-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd animal-conditions-classification
   ```
3. Run the main script:
   ```bash
   python main.py
   ```


## Acknowledgments

We would like to thank our professors and peers for their guidance and support throughout this project.
