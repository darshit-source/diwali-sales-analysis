Diwali Sales Analysis | Python

An exploratory data analysis project examining Diwali sales patterns across customer demographics, geography, occupation, product categories, and products. The analysis uses Python in a Jupyter Notebook and visualizes results with Pandas, Matplotlib, and Seaborn.

> **Portfolio project** · Python · Exploratory data analysis · Data visualization

<!-- To add a preview, save a clear chart or notebook screenshot in the repository (for example, assets/diwali-sales-preview.png), then uncomment and update this line:
![Diwali sales analysis preview](assets/diwali-sales-preview.png)
-->

## Project overview

The notebook explores the supplied sales dataset to answer questions such as:

- How does purchase amount vary by gender and age group?
- Which states contribute the most orders and sales amount?
- How do marital status and occupation relate to purchasing patterns?
- Which product categories and products appear most often in sales?

The dataset contains **11,251 rows** and fields for customer demographics, location, occupation, product, order count, and amount. The notebook removes two blank/unrelated columns, drops rows with missing values, converts `Amount` to an integer, and uses grouped summaries and charts for exploration.

## Key observations

The notebook's analysis highlights these patterns in the supplied data:

- Customers in the **26–35** age group contribute strongly to purchases.
- **Uttar Pradesh, Maharashtra, and Karnataka** lead the state comparisons shown in the notebook.
- **Food, Clothing, and Electronics** are among the leading product categories by amount.
- The notebook also compares purchasing patterns by gender, marital status, and occupation; its written conclusion calls out married women and customers in IT, Healthcare, and Aviation.

These are descriptive patterns in this dataset. They should not be interpreted as causal findings or as a forecast of future customer behavior.

## Files to include in this repository

| File | Description |
| --- | --- |
| `Diwali_Sales_Analysis.ipynb` | Main Jupyter Notebook containing the data preparation, analysis, charts, and conclusions. |
| `Diwali Sales Data.csv` | Dataset used by the notebook. |
| `README.md` | Project overview and instructions. |

## Tools and skills

- Python
- Jupyter Notebook
- Pandas and NumPy for data handling
- Matplotlib and Seaborn for visualization
- Data cleaning, missing-value handling, grouping, descriptive analysis, and exploratory data visualization

## Run the notebook

1. Download or clone this repository.
2. Install Python and Jupyter Notebook, then install the libraries used by the notebook:

   ```bash
   pip install jupyter pandas numpy matplotlib seaborn
   ```

3. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Keep `Diwali Sales Data.csv` in the same folder as the notebook.
5. Run the notebook cells from top to bottom.

The notebook reads the CSV using `encoding='unicode_escape'`. If you change the data file or its encoding, update the read step accordingly.

## Repository cleanup

Use the root-level `Diwali_Sales_Analysis.ipynb` as the single notebook in the public project. Do not upload duplicate checkpoint or editor copies from `.ipynb_checkpoints` or `.virtual_documents`. Do not upload `anaconda_projects/db/project_filebrowser.db`; it is local project-browser metadata and is not needed to run the analysis.

## Data sharing

The dataset contains customer names and user IDs. Before publishing the CSV in a public repository, confirm that its source permits redistribution and that those fields are appropriate to share. If not, remove the CSV and replace it with an anonymized or synthetic dataset, then revise the run instructions and project description.

## About

Created as a portfolio project to demonstrate a Python-based exploratory data analysis workflow. Add your name and links to your portfolio or LinkedIn profile here if you want to connect the project to your resume.

