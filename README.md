# Diabetes Diagnosis Project

This project performs data cleaning, preprocessing, feature engineering, and exploratory data analysis (EDA) on the **Diabetes Diagnosis** dataset.

---

## 📂 Project Structure

```
your_project_directory/
│
├── diabete_final.ipynb             # Main Jupyter Notebook
├── diabetes_diagnosis.csv          # Raw dataset file
│
└── outputs/                        # Created automatically
    └── diabetes_diagnosis_clean.csv # Cleaned dataset output
```

---

## ⚙️ Requirements

The project uses the following Python libraries (with fixed versions for reproducibility):

```
pandas==2.2.2
numpy==1.26.4
matplotlib==3.8.4
seaborn==0.13.2
jupyterlab==4.2.1
notebook==7.2.0
```

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. **Start Jupyter**  
   ```bash
   jupyter notebook
   ```  
   or  
   ```bash
   jupyter lab
   ```

2. **Open the Notebook**  
   In the Jupyter interface, open `diabete_final.ipynb`.

3. **Run All Cells**  
   Run cells sequentially (`Shift + Enter`) or via the menu:  
   `Cell -> Run All`.

4. **Check Output**  
   After execution, the cleaned dataset will be saved at:  
   `outputs/diabetes_diagnosis_clean.csv`.

---

## 📊 Expected Results

- **CSV File**: Cleaned dataset saved inside the `outputs/` directory.  
- **Visualizations**: Graphs and plots generated inside the Jupyter Notebook.

---

## 📝 Notes

- Always keep `diabete_final.ipynb` and `diabetes_diagnosis.csv` in the same directory.  
- The `outputs/` folder will be created automatically when you run the notebook.  
- To capture your environment versions, run:  
  ```bash
  pip freeze > requirements.txt
  ```

---

✔️ End of README
