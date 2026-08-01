# Notebook Setup and Usage

This folder contains the project notebooks for dataset understanding, cleaning, exploratory analysis, feature engineering, baseline modeling, and AI trust score evaluation.

## Necessary steps before running notebooks

1. Open the project in VS Code and select the project Python interpreter.
   - Recommended interpreter: `/home/codespace/.python/current/bin/python`

2. Install the required Python libraries in that interpreter:

   ```bash
   /home/codespace/.python/current/bin/python -m pip install pandas numpy matplotlib opencv-python Pillow jupyter
   ```

3. If OpenCV fails with an error such as:

   ```text
   ImportError: libGL.so.1: cannot open shared object file
   ```

   install the missing system package:

   ```bash
   sudo apt-get update
   sudo apt-get install -y libgl1
   ```

4. Restart the notebook kernel if needed, then run the cells again.

5. Store data files in the project `data/raw/` folder before running analysis notebooks.

## Recommended project structure

```text
notebooks/
├── 01_dataset_understanding.ipynb
├── 02_data_cleaning.ipynb
├── 03_eda.ipynb
├── 04_feature_engineering.ipynb
├── 05_baseline_models.ipynb
├── 06_ai_trust_score.ipynb
└── README.md
```

## Notes

- If a package is missing, install it using the same Python interpreter selected for the notebook.
- Keep notebook outputs in the project `outputs/` folders for reproducibility.
