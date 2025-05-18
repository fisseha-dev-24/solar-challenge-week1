# Solar Challenge Week 1

Welcome to the Solar Challenge Week 1 repository! This project is focused on the exploration, cleaning, and preliminary analysis of solar data from three countries: Benin, Sierra Leone, and Togo. The work here forms the foundation for deeper insights and future solar energy modeling.

---

## 📁 Repository Structure

```
├── .github/
│   └── workflows/
│       └── ci.yml
├── .vscode/
│   └── settings.json
├── notebooks/
│   ├── benin_eda.ipynb
│   ├── sierraleone_eda.ipynb
│   ├── togo_eda.ipynb
│   └── README.md
├── scripts/
│   └── README.md
├── tests/
├── data/                # (Ignored: see .gitignore)
├── requirements.txt
├── .gitignore
└── README.md            # (this file)
```

---

## 🚀 Project Overview

This repository includes:
- **Python Jupyter notebooks** for exploratory data analysis (EDA) of solar datasets from Benin, Sierra Leone, and Togo.
- Automated continuous integration using GitHub Actions for reproducible environments.
- Documentation and scripts to help you reproduce and understand the analysis.

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/fisseha-dev-24/solar-challenge-week1.git
cd solar-challenge-week1
```

### 2. Set up Python Environment

We recommend using a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Or use `conda`:

```bash
conda create -n solar-challenge python=3.8
conda activate solar-challenge
pip install -r requirements.txt
```

### 3. Running the Notebooks

All EDA notebooks are in the `notebooks/` directory. Use Jupyter to open and explore:

```bash
jupyter notebook notebooks/
```
or
```bash
jupyter lab notebooks/
```

---

## 📓 Notebooks

- `benin_eda.ipynb` - EDA for Benin solar data
- `sierraleone_eda.ipynb` - EDA for Sierra Leone solar data
- `togo_eda.ipynb` - EDA for Togo solar data

Each notebook:
- Loads, profiles, and cleans its respective country's dataset
- Performs outlier and missing value analysis
- Visualizes data trends and relationships
- Exports cleaned data (not committed to repo)

---

## 🔒 Data Privacy

Raw and cleaned data files are **not included** in this repository. They are stored in the `data/` directory, which is excluded via `.gitignore` for privacy and storage reasons.

---

## 🧪 Continuous Integration

Every push triggers a GitHub Actions workflow (`ci.yml`) that ensures the project dependencies install correctly and Python is set up.

---

## 🤝 Contributions

Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request. For questions, open an issue.

---

## 👤 Author

- [Fisseha2424](https://github.com/fisseha-dev-24)

---

## 📚 References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)