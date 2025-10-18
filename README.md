# STA 5703 – Project 2: Genomic Prediction of Maize Flowering Time

This repository contains the code, dataset, and outputs for **Project 2 (STA 5703 Data Mining)**.  
The project benchmarks regression and feature selection methods for predicting **Days to Anthesis (DtoA)** in maize from genome-wide SNP markers.

---

## 📂 Files Included

- **5703_Project2.ipynb** – Jupyter Notebook with full analysis (step by step).  
- **project2_pipeline.py** – End-to-end Python script (runs the full pipeline).  
- **maize_data.csv** – Input dataset (genotypes + phenotype DtoA).  

**Results Folder (Outputs):**
- **results_table.csv** – Comparison of models (RMSE, MAE, runtime, #features).  
- **rmse_bar.png** – Bar chart of RMSE(Test) across models.  
- **rmse_vs_time.png** – Scatter plot: RMSE vs runtime.  
- **residuals_plot.png** – Residual diagnostics for the best model.  
- **lasso_stability_top10.txt** – Top SNPs selected by Lasso (stability).  
- **enet_stability_top10.txt** – Top SNPs selected by Elastic Net (stability).  
- **Results.zip** – Zipped archive of all outputs.  

---

## ⚙️ Methods Implemented

- Ridge Regression  
- Lasso Regression  
- Elastic Net  
- Sequential Forward Selection (SFS)  
- Principal Component Regression (PCR)  
- Partial Least Squares (PLS)  

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/panitakanaguduru/5703_Project2.git
   cd 5703_Project2
