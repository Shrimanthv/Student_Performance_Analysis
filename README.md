

# Student Performance Analysis

## Table of Contents
* [Demo](#demo)
* [Overview](#overview)
* [Motivation](#motivation)
* [Features](#features)
* [Installation](#installation)
* [Tech Stack](#tech-stack)
* [Deployment on Streamlit](#deployment-on-streamlit)
* [Project Structure](#project-structure)
* [Bug / Feature Request](#bug--feature-request)
* [Technology Used](#technology-used)
* [Author](#author)

## Demo

!["C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125735.png"](https://github.com/Shrimanthv/Student_Performance_Analysis/blob/main/Screenshot%202025-03-22%20125637.png?raw=true)
!["C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125735.png"](https://github.com/Shrimanthv/Student_Performance_Analysis/blob/main/Screenshot%202025-03-22%20125735.png?raw=true)


## Motivation
This project was inspired by the need to understand key factors affecting student performance.
By analyzing data, we aim to uncover insights that can help improve academic outcomes.
Our goal is to support data-driven decisions in education for better student success.

## Features
Data preprocessing and cleaning for accurate analysis
Statistical analysis to identify key performance factors
Visualizations to clearly present trends and insights
Predictive modeling to forecast student outcomes
Actionable recommendations for improving student performance

## Installation

To set up the project locally, follow these steps:

 **1. Clone the repository:**

   ```bash
   git clone https://github.com/Shrimanthv/Student_Performance_Analysis.git
   ```

**2.Navigate to the project directory:**
```bash
   cd Student_Performance_Analysis
   ```
**3.Create a virtual environment:**
```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
**4.Install the required dependencies:**
```bash
   pip install -r requirements.txt
   ```


## Tech Stack
Python — main programming language

Pandas, NumPy — data manipulation and analysis

Matplotlib, Seaborn — data visualization

Scikit-learn — machine learning and predictive modeling

Jupyter Notebook — interactive development and analysis environment

## Deployment

To deploy this project run command in the command prompt

```bash
 python app.py
```
Open Your browser and enter
```bash
 127.0.0.1:5000/predictdata

```

## Project Structure
``` bash
Student_Performance_Analysis/  
├── data/                     # Directory containing datasets  
│   └── student_performance.csv  
├── notebooks/                # Jupyter notebooks for data analysis and visualization  
│   ├── data_cleaning.ipynb  
│   ├── exploratory_analysis.ipynb  
│   └── model_training.ipynb  
├── scripts/                  # Python scripts for data processing and model building  
│   ├── preprocess_data.py  
│   ├── train_model.py  
│   ├── evaluate_model.py  
│   └── visualize_results.py  
├── models/                   # Saved machine learning models  
│   └── student_performance_model.pkl  
├── results/                  # Results and outputs (e.g., plots, model performance)  
│   ├── accuracy_report.txt  
│   └── performance_plots/  
├── requirements.txt          # List of required Python packages  
├── README.md                 # Project documentation  
└── LICENSE    
```

## Bug / Feature Request
If you encounter any bugs or have suggestions for new features, please feel free to open an issue on the GitHub repository.

To report a bug:
Provide a clear description of the problem, steps to reproduce it, and any relevant screenshots or error messages.

To request a feature:
Describe the new functionality you'd like to see and explain how it would improve the project.

Your feedback helps improve AeroFare — thank you for contributing!

## Technology Used
<img src="https://streamlit.io/images/brand/streamlit-logo-secondary-colormark-darktext.svg" width="180" alt="Streamlit Logo" /> Streamlit – for building interactive web applications <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width="200" alt="Scikit-learn Logo" /> Scikit-learn – for machine learning and predictive modeling <img src="https://pandas.pydata.org/static/img/pandas_mark.svg" width="150" alt="Pandas Logo" /> Pandas – for data manipulation and analysis <img src="https://numpy.org/images/logo.svg" width="150" alt="NumPy Logo" /> NumPy – for numerical computations and array handling<img src="https://matplotlib.org/_static/images/logo2.svg" width="180" alt="Matplotlib Logo" /> Matplotlib – for creating static, animated, and interactive visualizations  
<img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="200" alt="Seaborn Logo" /> Seaborn – for statistical data visualization built on top of Matplotlib  


## Authors

- **Shrimanth V** - Project Creator

**GitHub:** Shrimanthv

**Email:** [shrimanthv99@gmail.com]
=======

# Student Performance Analysis

The Student Performance Analysis project on GitHub aims to analyze and visualize student performance data to identify key factors affecting academic outcomes. It uses data processing, statistical analysis, and visualization techniques to gain insights into students' performance patterns.

**Who It's For:**

**Educators:** To understand which factors impact student performance and make data-driven decisions to improve teaching strategies.

**School Administrators:** To monitor and enhance overall student performance.

**Data Analysts:** To explore educational data and develop models for academic performance prediction.

**Researchers:** To analyze patterns and correlations within student data.


## Demo

"C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125735.png"

"C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125637.png"


## Installation

To set up the project locally, follow these steps:

 **1. Clone the repository:**

   ```bash
   git clone https://github.com/Shrimanthv/Student_Performance_Analysis.git
   ```

**2.Navigate to the project directory:**
```bash
   cd Student_Performance_Analysis
   ```
**3.Create a virtual environment:**
```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
**4.Install the required dependencies:**
```bash
   pip install -r requirements.txt
   ```




    
## Usage
**1.Prepare the dataset:** Ensure you have the dataset in the appropriate format. If using a specific dataset, place it in the designated directory or update the data path in the scripts.

**2.Run the data preprocessing script:**
```bash
python preprocess_data.py
```
**3.Perform exploratory data analysis:**

```bash
python eda.py
```
**4.Train the predictive model:**
```bash
python train_model.py
```

**5.Evaluate the model:**
```bash
python evaluate_model.py
```

**6.Visualize the results:**
```bash
python visualize_results.py
```
## Deployment

To deploy this project run command in the command prompt

```bash
 python app.py
```
Open Your browser and enter
```bash
 127.0.0.1:5000/predictdata
```


## 🚀 About Me
I am **Shrimanth V**, a passionate and motivated **Computer Science and Engineering** student with a strong interest in **data science, machine learning, and software development.** 


## Acknowledgements

 We would like to express our gratitude to the following resources and individuals who contributed to the success of this project:

  **1. Dataset Providers:** Thanks to the organizations and individuals who made the student performance datasets publicly available.

 **2.Python and Data Science Community:** For the countless tutorials, documentation, and support that made this project possible.

**3.GitHub Community:** For providing a platform to collaborate and share projects.

**4.Contributors:** Special thanks to everyone who contributed to improving this project through suggestions, bug reports, and feature enhancements.

**5.Mentors and Educators:** For guidance and encouragement throughout the development process.

**6.Open-Source Libraries:** Such as Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn, which greatly facilitated data analysis and visualization.



## Authors

- **Shrimanth V** - Project Creator

**GitHub:** Shrimanthv

**Email:** [shrimanthv99@gmail.com]


## Optimizations

Throughout the development of this project, several optimizations were made to enhance performance, maintainability, and accessibility:

**Code Refactoring:**
- Improved code readability and maintainability by breaking down large functions into smaller, modular functions.

- Removed redundant code and optimized loops to reduce time complexity.

**Performance Improvements:**
- Utilized vectorized operations with NumPy and Pandas instead of traditional loops to speed up data processing.

- Implemented caching mechanisms where possible to avoid redundant computations.

- Applied efficient data loading and preprocessing techniques to minimize memory usage.

**Model Optimization:**

- Tuned hyperparameters of machine learning models to improve accuracy and reduce overfitting.

- Applied feature selection techniques to reduce the dimensionality and improve model performance.

- Used cross-validation to ensure robustness and generalizability of the models.

## Screenshots
"C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125735.png"
"C:\Users\Shrimanth\OneDrive\Pictures\Screenshots\Screenshot 2025-03-22 125637.png"



## Directory tree
``` bash
Student_Performance_Analysis/  
├── data/                     # Directory containing datasets  
│   └── student_performance.csv  
├── notebooks/                # Jupyter notebooks for data analysis and visualization  
│   ├── data_cleaning.ipynb  
│   ├── exploratory_analysis.ipynb  
│   └── model_training.ipynb  
├── scripts/                  # Python scripts for data processing and model building  
│   ├── preprocess_data.py  
│   ├── train_model.py  
│   ├── evaluate_model.py  
│   └── visualize_results.py  
├── models/                   # Saved machine learning models  
│   └── student_performance_model.pkl  
├── results/                  # Results and outputs (e.g., plots, model performance)  
│   ├── accuracy_report.txt  
│   └── performance_plots/  
├── requirements.txt          # List of required Python packages  
├── README.md                 # Project documentation  
└── LICENSE    
```
## Technology used
**Programming Languages**
- Python - Core programming language for data analysis and machine learning.

**Libraries and Frameworks**
- Pandas - Data manipulation and analysis.

- NumPy - Efficient numerical computations.

- Scikit-learn - Machine learning algorithms and model evaluation.

- Matplotlib - Data visualization and plotting.

- Seaborn - Enhanced statistical data visualization.

- Jupyter Notebook - Interactive development and data analysis.

**Development Environment**
- Jupyter Notebook - For exploratory data analysis and model building.

- Virtualenv - To create isolated Python environments.

- Git - Version control and collaboration.

- GitHub - Hosting and project management.

**Tools and Platforms**
- Anaconda - Package management and environment setup.

- VS Code - Code editing and debugging.
>>>>>>> 993557a9f06bfa7d3fa77c403a1d7aeb3f8abfa5
