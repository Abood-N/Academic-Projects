# Code Files

This folder contains the Jupyter notebooks used throughout the JPL Football Analytics project.

## Files

### Before_Training.ipynb
Contains data preparation and preprocessing steps performed before model training, including dataset organization, annotation handling, and required setup.

### Best_Results.ipynb
Runs the full football analytics pipeline using the final trained models and produces the best experimental results reported in the project.

### Video_Code.ipynb
Generates the final annotated football video using outputs from the main pipeline. This notebook should be executed after **Best_Results.ipynb**.

---

## Execution Order

To reproduce the project workflow:

1. Run `Before_Training.ipynb` (if dataset preparation is required).
2. Run `Best_Results.ipynb` using the project dataset (not publicly released).
3. Run `Video_Code.ipynb` to generate the final annotated output video.

---

## Notes

- The dataset used in this project is **not publicly available** due to licensing and usage restrictions.
- The notebooks were developed in a Kaggle environment, so file paths follow Kaggle’s directory structure.
- If running locally with a custom dataset, update dataset and output paths accordingly.
- The final report and project documentation are available in the parent project folder.
