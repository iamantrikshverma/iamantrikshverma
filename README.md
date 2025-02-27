# Data Preprocessing Projects

## Overview
This repository contains two Jupyter Notebook files that showcase data preprocessing techniques using Python, Pandas, and Matplotlib. These projects were developed as part of a 25-day learning journey in Python, focusing on preparing datasets for analysis and visualization. The notebooks demonstrate data cleaning, outlier detection, missing value handling, and exploratory data analysis (EDA).

## Projects
### `datapreprocessing0.ipynb`
- **Description**: Preprocesses a car price dataset, checking for missing values (none found), identifying outliers using the Interquartile Range (IQR) method (no outliers detected), and preparing the data for further analysis.
- **Dataset**: Car price dataset (loaded via CSV).

### `datapreprocessing1.ipynb`
- **Description**: Preprocesses a diabetes dataset with missing values, removes outliers, drops columns with over 30% missing data, and visualizes relationships between features (e.g., Pregnancies, Glucose, BMI) and the target variable (Class—diabetes or not). Key insights include lower pregnancy counts correlating with lower diabetes risk.
- **Dataset**: Diabetes dataset with missing data (loaded from a GitHub URL).

## Purpose
These notebooks are part of my journey to master Python for data science, specifically focusing on data preprocessing, a critical step in machine learning pipelines. They serve as both learning tools and practical examples for others to understand data cleaning and visualization techniques.

## Getting Started
### Prerequisites
- Python 3.8+
- Jupyter Notebook (or Google Colab for running `.ipynb` files online)
- Required libraries:
  - `pandas`
  - `matplotlib`

### Installation
1. Clone or download this repository:
   ```bash
   git clone https://github.com/iamantrikshverma/iamantrikshverma.git
   cd iamantrikshverma
   ```
2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib
   ```
3. Optionally, install Jupyter Notebook locally:
   ```bash
   pip install jupyter
   ```
   Or use Google Colab by uploading the `.ipynb` files directly to Colab.

### Running the Notebooks
#### Locally:
1. Navigate to the repository folder.
2. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `datapreprocessing0.ipynb` or `datapreprocessing1.ipynb` in the browser.

#### Google Colab:
1. Upload `datapreprocessing0.ipynb` and `datapreprocessing1.ipynb` to Google Colab.
2. Run the cells directly in Colab (libraries are pre-installed).

## Usage
- `datapreprocessing0.ipynb`: Run to explore the car price dataset, check for missing values, and identify outliers using the IQR method.
- `datapreprocessing1.ipynb`: Run to preprocess the diabetes dataset, handle missing values, remove outliers, and visualize feature distributions against the Class variable.

## Insights
- **Car Price Dataset**: No missing values or outliers, making it ready for modeling or deeper analysis.
- **Diabetes Dataset**: Key finding—lower pregnancy counts are associated with a reduced likelihood of diabetes, visualized through bar plots and histograms.

## Contributing
This repository is primarily for my personal learning and sharing. However, if you’d like to contribute (e.g., suggest improvements, fix bugs, or add visualizations), feel free to fork the repository, make changes, and submit a pull request. Please include a description of your changes.

## License
This project is open-source and available under the MIT License. See the `LICENSE` file for details (create one if not present).

## Acknowledgments
- Thanks to the Python, Pandas, and Matplotlib communities for their incredible tools.
- Inspiration from online tutorials and datasets available on GitHub.

## Contact
- **Author**: Antriksh Verma
- **GitHub**: [iamantrikshverma](https://github.com/iamantrikshverma)
- **Email**: [iamantrikshverma@gmail.com]


