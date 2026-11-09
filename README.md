# MSCS 634 Lab 6: Association Rule Mining with Apriori and FP-Growth

## Student Information
- **Name:** Urusha Budhathoki
- **Course:** MSCS-634-M50– Advanced Big Data and Data Mining
- **Lab:** Association Rule Mining

## Overview
This laboratory experiment discusses association rule mining using the Online Retail database. The two algorithms that are used in this experiment are Apriori and FP-growth.

## Dataset
The Online Retail dataset includes records of transactions performed in an online retail store.

Dataset file: `Online Retail.xlsx`

## Technologies and Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Mlxtend
- OpenPyXL

## Lab Activities
1. Read and study the Online Retail dataset.
2. Preprocess the dataset by removing missing descriptions, canceled transactions, and invalid quantities.
3. Convert transactions to a basket form.
4. Apply the Apriori algorithm.
5. Apply the FP-Growth algorithm.
6. Create association rules with support, confidence, and lift measures.
7. Plot frequent itemsets and association rules.
8. Analyze the efficiency of both algorithms.
## Results

| Measurement | Apriori | FP-Growth |
|---|---:|---:|
| Execution Time | 1.5223 seconds | 4.3566 seconds |
| Frequent Itemsets | 379 | 379 |
| Association Rules | 151 | 151 |

Both algorithms created identical sets of frequent itemsets. Apriori was quicker in this case study.

## Conclusion
This experiment illustrated how association rule mining can uncover connections among items in retail transactions. Both algorithms successfully generated frequent itemsets and association rules. The Apriori algorithm worked faster in this case.

## How to Run
1. Install the required libraries:
   ```bash
   python -m pip install pandas numpy matplotlib seaborn mlxtend openpyxl jupyter
   ```
2. Keep `Online Retail.xlsx` in the same folder as the notebook.
3. Start JupyterLab:
   ```bash
   python -m jupyter lab
   ```
4. Open `MSCS_634_Lab_6_Association_Rule_Mining.ipynb` and run the notebook cells.