

# Deadlift Pose Analysis

This project is designed to analyze deadlift poses using computer vision techniques. It utilizes the MediaPipe library for pose estimation and OpenCV for video processing. The goal is to track the movement of a person performing deadlifts and provide feedback on their form.

## Features

- Real-time deadlift pose detection and analysis.
- Automatic counting of deadlift repetitions.
- Calculation of total workout time and individual rep times.
- Evaluation of form based on the angle between shoulder and hip joints.
- Saving workout data to an Excel spreadsheet.
- Graphical user interface for displaying workout reports and saving them to Excel.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- NumPy (`pip install numpy`)
- Tkinter (usually comes pre-installed with Python)
- OpenPyXL (`pip install openpyxl`)

## How to Use

1. Run the `main.py` script.
2. Input the number of deadlifts to perform when prompted.
3. Perform deadlifts in front of the webcam.
4. Follow the on-screen instructions for feedback on form and workout progress.
5. Press 'q' to exit the application.

## File Descriptions

- `main.py`: Main script for running the deadlift pose analysis.
- `reports_summary.xlsx`: Excel spreadsheet for storing workout data.
- `README.md`: Documentation file (you're currently reading it).
- Other Python scripts containing utility functions and GUI setup.

## Contributors

- [Sudhanshu]

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- MediaPipe development team for providing the pose estimation model.
- OpenCV development team for the powerful computer vision library.

---
