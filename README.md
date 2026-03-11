# YOLO-Object-Detection

YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images.
darknet prints out the objects it detected, its confidence, and how long it took to find them. We didn't compile Darknet with OpenCV so it can't display the detections directly. Instead, it saves them in predictions.png. You can open it to see the detected objects. Since we are using Darknet on the CPU it takes around 6-12 seconds per image. If we use the GPU version it would be much faster.

## Prerequisites

1. Clone the repository and navigate into the project directory.
2. It is highly recommended to create a virtual environment to install the dependencies.

### Linux and macOS
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### Windows
```cmd
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## How to run:

1. Activate your virtual environment (if you created one).
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `accident_detector.ipynb` in your browser.
4. Run the cells in the notebook!

