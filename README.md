# Multi-Linear Regression on Insurance Dataset

This project performs a multi-linear regression analysis on an insurance dataset. The goal is to predict insurance charges based on various factors such as age, sex, BMI, children, smoker status, and region.

## Project Structure

- `Multi_Linear_Regression_on_Insurance_Dataset.ipynb`: Jupyter notebook containing the multi-linear regression analysis.
- `insurance.csv`: Dataset used for the analysis (ensure this file is in the same directory as the notebook).

## Installation

To run this project, you need to have Python and Jupyter Notebook installed. You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Usage
1. Clone the repository:

``` bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```
2. Open the Jupyter notebook:

```bash
jupyter notebook Multi_Linear_Regression_on_Insurance_Dataset.ipynb
```
3. Run the cells in the notebook to see the analysis.

## Dataset
The insurance.csv file contains the following columns:

- **age**: Age of primary beneficiary.
- **sex**: Insurance contractor gender, female or male.
- **bmi**: Body mass index, providing an understanding of body weight relative to height.
- **children**: Number of children covered by health insurance / number of dependents.
- **smoker**: Smoking status of the insurance contractor.
- **region**: Residential area in the US, northeast, southeast, southwest, northwest.
- **charges**: Individual medical costs billed by health insurance.
## Analysis
The multi-linear regression analysis includes:

- **Data Cleaning**: Handling missing values and correcting data types.
- **Exploratory Data Analysis**: Visualizing distributions, correlations, and trends.
- **Model Building**: Creating and evaluating a multi-linear regression model.
- **Statistical Analysis**: Examining relationships between variables and their impact on insurance charges.
## Results
The key insights from the analysis are:

- The impact of age, BMI, and smoking status on insurance charges.
- How gender and region influence the cost of insurance.
- The overall predictive power of the multi-linear regression model.
