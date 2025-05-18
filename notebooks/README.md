# Notebooks Directory

This folder contains all Jupyter notebooks related to Exploratory Data Analysis (EDA) for the Solar Challenge Week 1 project.

---

## 📓 Included Notebooks

- **benin_eda.ipynb**  
  Exploratory data analysis for the Benin solar dataset: summary statistics, cleaning, visualizations, and insights.
- **sierraleone_eda.ipynb**  
  EDA for the Sierra Leone solar dataset: data profiling, outlier detection, trends, and visualizations.
- **togo_eda.ipynb**  
  EDA for the Togo solar dataset: full workflow from raw data to clean, visualized insights.

---

## 📝 How to Use

1. **Ensure you have Python and Jupyter installed.**
   - See the main [README.md](../README.md) for setup instructions.

2. **Place the relevant raw data files** (e.g., `benin.csvbenin-malanville.csv`, `sierraleone-bumbuna.csv`, `togo-dapaong_qc.csv`) in the `data/` directory at the root of the repository.

3. **Open notebooks in Jupyter:**
    ```bash
    jupyter notebook
    ```
    or
    ```bash
    jupyter lab
    ```

4. **Run all cells** for a full data exploration workflow, including:
   - Data loading and overview
   - Summary statistics and missing value checks
   - Outlier detection and basic cleaning
   - Visualizations: time series, correlations, scatter plots, wind rose, histograms, bubble charts
   - Export of cleaned data (to `../data/COUNTRY_clean.csv` – not committed)

---

## 📂 Notes

- **No data files are included** in this directory or the repository. All data should be kept in the `data/` folder, which is gitignored.
- Each notebook is self-contained for its country's analysis, but follows a consistent methodology for easy comparison.

---

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scipy Stats](https://docs.scipy.org/doc/scipy/reference/stats.html)

---