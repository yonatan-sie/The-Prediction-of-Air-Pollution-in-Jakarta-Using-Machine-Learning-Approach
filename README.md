# How to Run This Project

This project is implemented entirely using Jupyter Notebook and executed with Python 3.10 via Command Prompt (CMD).

### 1. Clone this repository
To obtain the project, clone this repository to your local machine:
  ```bash
  git clone https://github.com/yonatan-sie/The-Prediction-of-Air-Pollution-in-Jakarta-Using-Machine-Learning-Approach.git
```
### 2. System Requirement
  - Python 3.10+ is installed on your computer.
  - Pip (Python package installer) is installed.
  - Jupyter Notebook installed

### 3. Open Project Directory
Open Command Prompt and navigate to the project directory:
```bash
cd path\to\The-Prediction-of-Air-Pollution-in-Jakarta-Using-Machine-Learning-Approach
```

### 4. Launch Jupyter Notebook
Run Jupyter Notebook using Python 3.10:
```bash
py -3.10 -m notebook
```
This command will open Jupyter Notebook in your web browser.

### 5. Dataset Location
All raw datasets are located in:
```bash
data/raw/
```
The datasets include:
  - Ground station air quality data
  - Satellite-derived data (Sentinel-5P, MODIS, VIIRS)
  - Spatial grid and map-related data 

### 5. Notebook Execution Flow
All analysis is performed throught Jupyter Notebooks located in the notebook directory.
Notebooks should be executed sequentially:
1. Data Cleaning
   - Cleaning and validating raw ground and satellite datasets.
2. Preprocessing
   - Feature engineering, handling missing values, and scaling.
4. Exploratory Data Analysis (EDA)
   - Visualizing data distribution and relationships.
6. Modelling
   - Training and evaluating machine learning models.
8. 
9. Spatial Prediction
10. Mapping

6. Output Files
