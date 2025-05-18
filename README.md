# Solar Data Discovery: Week 0 Challenge

## Setup Instructions

1. **Clone the repository**
   ```sh
   git clone https://github.com/Fisseha2424/solar-challenge-week1.git
   cd solar-challenge-week1
   ```

2. **Create and activate a Python virtual environment**
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install the dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Development and CI**
   - All dependencies are tracked in `requirements.txt`.
   - GitHub Actions automatically installs dependencies and checks the Python version on push and PRs.

## Folder Structure

```
solar-challenge-week1/
├── .vscode/
├── .github/
│   └── workflows/
├── src/
├── notebooks/
├── tests/
├── scripts/
├── data/           # ignored in git
├── requirements.txt
├── .gitignore
└── README.md
```

## Contributions

- Use feature branches and open Pull Requests for changes.
- Keep data/ and local CSVs out of git.