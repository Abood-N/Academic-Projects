# 💻 Code Files

This folder contains the Jupyter notebooks used throughout the JPL Football Analytics project.

## Files

### Before_Training.ipynb
Contains the data preparation and preprocessing steps performed before model training, including dataset organization, annotation handling, and any required setup.

### Best_Results.ipynb
Runs the complete football analytics pipeline using the final trained models and produces the best experimental results reported in the project.

### Video_Code.ipynb
Generates the final annotated football video using the outputs produced by the main pipeline. This notebook should be executed after running **Best_Results.ipynb**.

---

## Execution Order

To reproduce the project results:

1. Run **Before_Training.ipynb** (if dataset preparation is required).
2. Run **Best_Results.ipynb** using the dataset stored in **Our_Split_Best_Results**.
3. After the pipeline finishes, run **Video_Code.ipynb** to generate the final annotated output video.

---

## Notes

- The notebooks were developed in the Kaggle environment, so the dataset paths follow Kaggle's directory structure.
- If running the project locally, update the dataset and output paths accordingly.
- The final report and project documentation are available in the parent project folder.
