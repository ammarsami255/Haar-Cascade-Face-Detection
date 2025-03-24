# Face Detection using OpenCV

This is a simple real-time face detection script using OpenCV in Python. It utilizes Haar cascade classifiers to detect faces from a webcam feed and highlights them with a bounding box.

## Requirements

Ensure you have Python installed along with the required dependencies:

```bash
pip install opencv-python
```

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/face-detection-opencv.git
   cd face-detection-opencv
   ```

2. Run the script:
   ```bash
   python face_detection.py
   ```

## How It Works

- Captures video from the default webcam.
- Converts each frame to grayscale.
- Detects faces using Haar cascade classifiers.
- Draws a bounding box around detected faces.
- Press `q` to exit the program.

## Dependencies
- OpenCV
- Python 3.x

## Example Output

When a face is detected, a bounding box appears around it:

![Example Image](https://user-images.githubusercontent.com/example/example.png)

## License
This project is licensed under the MIT License.

---
Feel free to contribute or modify the code to improve detection accuracy!

