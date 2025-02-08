
# YOLO License Plate Detection

## Overview
This project implements a license plate detection system using YOLOv8 and Streamlit. The application allows users to upload images or videos and detects license plates in them.

## Features
- Upload images and videos for processing.
- Uses YOLOv8 for object detection.
- Displays detected license plates with confidence scores.
- Supports multiple image and video formats.

## Installation

### Prerequisites
Ensure you have Python installed (>=3.7). Install the required dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

### Running the Application
Run the Streamlit application using:
```bash
streamlit run yolo_application.py
```

### Uploading Files
- Select an image or video file.
- The application will process the file and display results.

## File Structure
```
.
├── yolo_application.py  # Main Streamlit app
├── requirements.txt     # Required dependencies
├── models/              # Folder for trained YOLO models
└── temp/                # Temporary storage for uploaded files
```

## Dependencies
The application requires the following Python packages:
- pandas
- matplotlib
- streamlit
- opencv-python
- ultralytics

## Model
The YOLO model is pre-trained and should be placed in the appropriate directory.
Modify the model path in `yolo_application.py`:
```python
model = YOLO('/path/to/your/trained/model/best.pt')
```

## Author
Chitra Jain



