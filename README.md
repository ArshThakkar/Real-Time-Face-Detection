
# Real-Time Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV, a popular computer vision library in Python.

## Installation

Ensure you have Python and OpenCV installed on your system.

```bash
pip install opencv-python
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/ArshThakkar/Real-Time-Face-Detection.git
cd Real-Time-Face-Detection
```

2. Download the `haarcascade_frontalface_default.xml` file and place it in the project directory. This file contains pre-trained classifiers for face detection.

3. Run the script:

```bash
python face_detection.py
```

4. The webcam will activate, and you'll see real-time face detection boxes overlaid on detected faces.

## How it Works

This script captures video from the default webcam using OpenCV's `VideoCapture` class. It then applies face detection using the Haar cascade classifier (`haarcascade_frontalface_default.xml`). Detected faces are outlined with rectangles.

## Contribution

Contributions are welcome! Feel free to open issues or pull requests for any improvements or features you'd like to add.

