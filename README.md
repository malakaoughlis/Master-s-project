# African Economic Risk Analysis  
## MSc Data Science Project

This project explores whether short-term economic dynamics in African countries can be explained by internal macroeconomic indicators, rather than only by external factors such as oil or commodity dependence.

The objective is to build a simple machine learning approach to detect early signs of economic slowdown.

---

## Dataset

The analysis uses the *Global Economic Indicators (2010–2025)* dataset based on World Bank data.

It contains yearly macroeconomic variables such as:

- GDP Growth  
- Inflation (CPI)  
- Unemployment Rate  
- GDP per Capita  
- Current Account Balance  

---

## How to Run the Project

To execute the notebook, follow these steps:

1. **Download the notebook file (.ipynb)**  
   Save the notebook on your computer.

2. **Open Google Colab**  
   Go to: https://colab.research.google.com/

3. **Import the notebook**  
   - Click on **"Upload"**  
   - Select the notebook file  

4. **Upload the dataset (CSV file)**  
   - On the left panel, click on the **folder icon**  
   - Upload the CSV file (`world_bank_data_2025.csv`)  
   - Make sure it is placed inside the `/content` folder  

5. **Run the code**  
   - Click **"Runtime" → "Run all"**  
   - Or run cells one by one  

---

## Project Workflow

The notebook follows these steps:

1. Data cleaning and selection  
2. Exploratory data analysis (EDA)  
3. Creation of the economic risk variable  
4. Model training and comparison  
5. Feature engineering  
6. Performance evaluation  

---

## Output

The project provides:

- Model performance metrics (Accuracy, Precision, Recall, F1-score, ROC-AUC)  
- Confusion matrices  
- ROC curves  
- Country-level risk predictions  

---

## Goal

The main goal is to show that simple and available macroeconomic indicators can help detect early signs of economic risk in African countries.
