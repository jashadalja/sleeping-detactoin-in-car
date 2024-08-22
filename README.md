# sleeping detaction in car

This project is a Python application that detects drowsiness and estimates the sleep individuals from live camera feed, video files, or images. It uses computer vision techniques and deep learning models to achieve these tasks.

- **Live Camera Feed**: Detects drowsiness in real-time.
- **Upload Video/Image**: Processes uploaded videos or images to detect drowsinesse.
- **Cancel and Stop**: Options to stop the live camera feed or cancel the processing of uploaded files.

## Setup and Installation

### Prerequisites

- Python 3.x
- Required Python packages:
  - `opencv-python`
  - `dlib`
  - `numpy`
  - `tensorflow`
  - `Pillow`
  - `tkinter`

### Installing Dependencies

Install the required packages using pip:

```sh
pip install opencv-python dlib numpy tensorflow Pillow
```

### Model Files

1. **Face Landmarks Predictor**: Download the `shape_predictor_68_face_landmarks.dat` from [this Google Drive link](https://drive.google.com/file/d/1N3lJNmN44SbyEC6w_siu39t3JTBRXmXH/view?usp=sharing) and place the file in the project directory.

2. **Age Prediction Model**: Ensure you have the `age_model.h5` file in the project directory.(or run this age_model.py)
   DataSet:https://www.kaggle.com/datasets/jangedoo/utkface-new

## Download the pre-trained models from the provided links and place them in the appropriate directories:

## Usage

### Running the Application

1. Clone this repository:

2. Navigate to the project directory:

3. Run the application:

```sh
python your_script_name.py
```
