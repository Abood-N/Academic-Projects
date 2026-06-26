# ⚽ JPL Football Analytics

This project presents an AI-based football analytics pipeline developed for automated player and ball analysis from football match videos. The system performs object detection, multi-object tracking, team assignment, ball possession estimation, pass visualization, and tactical analysis.

The project was developed as part of an academic research project focusing on computer vision and sports analytics.

---

## Features

- Player, goalkeeper, referee, and ball detection
- Multi-object tracking across video frames
- Team assignment using jersey color clustering
- Ball possession estimation
- Pass visualization
- Tactical event analysis
- Annotated output video generation

---

## Project Structure

```
JPL Football Analytics/
│
├── Codes/                     # Source code and notebooks
├── Football_Analytics.pdf     # Full project report
├── poster.jpeg                # Project poster
└── README.md
```

---

## Technologies Used

- Python
- YOLO
- ByteTrack
- OpenCV
- NumPy
- Scikit-learn
- Google Colab / Kaggle

---

## Running the Project

The notebooks were developed using the Kaggle notebook environment. Therefore, the dataset paths are already configured for the Kaggle directory structure.

If you run the project locally, you will need to modify the dataset and output paths accordingly.

To reproduce the final results:

1. Upload the dataset stored in **Our_Split_Best_Results**.
2. Run the notebook that generates the detection and tracking results.
3. After processing is complete, run the video generation notebook to create the final annotated output video.

---

## Project Report

The complete methodology, experiments, and evaluation can be found in:

**Football_Analytics.pdf**

---

## Project Poster

The project poster summarizing the work is included as:

**poster.jpeg**

---

## Result Video

You can watch the final output video here:

**Google Drive**

https://drive.google.com/file/d/1-IVI5Kd5JhLfvRBvsuBy2dkkV4TTSYaD/view?usp=sharing

---

## Author

**Abdelrahman Abu Naser**

Bachelor's Degree in Artificial Intelligence

Jordan University of Science and Technology
