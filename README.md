# Air Quality Prediction

A concise repository for exploratory data analysis (EDA) and classification on Indian air quality data. The project compares multiple models (SVM, Random Forest, XGBoost) and reports accuracy, insights, and visualizations.

## Project Overview
- Goal: Evaluate different algorithms to classify/predict air quality indices and compare performance.
- Dataset: Air Quality Data in India from Kaggle.
- Notebook: End‑to‑end EDA, preprocessing, feature engineering, training, evaluation.

## Repository Structure
- [Dataset/](Dataset/README.md) — Source and notes for the dataset.
- [Images/](Images/) — Generated plots used in the report.
- [Model/](Model/README.md) — Detailed description, libraries, plots, and conclusions.
- [Model/air-quality-eda-and-classification.ipynb](Model/air-quality-eda-and-classification.ipynb) — Main notebook for EDA and modeling.


## Data
- Source: https://www.kaggle.com/rohanrao/air-quality-data-in-india
- Place raw files in `Dataset/` or point the notebook to your local dataset path.

## Quick Start
### Prerequisites
- Python 3.9+ recommended
- pip
- VS Code or Jupyter


### Setup (Windows)
```powershell
# (Optional) create a virtual environment
python -m venv .venv
.\.venv\Scripts\Activate.ps1

# Install required packages
pip install numpy pandas scikit-learn xgboost seaborn matplotlib missingno chart_studio cufflinks jupyter

# Launch Jupyter
jupyter notebook
```

### Run the Notebook
- Open [Model/air-quality-eda-and-classification.ipynb](Model/air-quality-eda-and-classification.ipynb).
- Execute cells sequentially; adjust paths if your dataset location differs.

## Methods & Results (High Level)
- Models evaluated: RBF SVM, Random Forest, XGBoost.
- Techniques noted: handling missing values, visualization, and SMOTE to address class imbalance.
- Reported results (from the included analyses):
  - SVM ≈ 96.15%
  - Random Forest ≈ 99.89%
  - XGBoost ≈ 100% (best on test data)

See [Model/README.md](Model/README.md) for details, plots, and conclusions.

## Reproducibility Tips
- Ensure consistent Python and library versions (consider a virtual environment).
- Verify dataset schema/column names match the notebook expectations.
- If using GPU for XGBoost, install the appropriate build; otherwise the CPU build suffices.

## Acknowledgements
- Dataset by Rohan Rao: Air Quality Data in India — Kaggle.

## Contributing
- Issues and PRs are welcome. Please keep changes minimal and focused.

Working on the repository to make it end to end
