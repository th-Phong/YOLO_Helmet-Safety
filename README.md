# YOLO Helmet Safety Detection

## Overview
This project implements a safety helmet detection system using YOLO (You Only Look Once) object detection model. It can detect and classify whether people are wearing safety helmets in images and video streams.

## Features
- Real-time helmet detection
- Support for image and video input
- Detection of multiple classes:
  - Person with helmet
  - Person without helmet
  - Safety helmet

## Requirements
- Python 3.7+
- PyTorch
- OpenCV
- Numpy
- YOLOv5

## Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/YOLO_Helmet-Safety.git
cd YOLO_Helmet-Safety
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage
1. To run detection on images:
```bash
python detect.py --source path/to/image.jpg
```

2. To run detection on video:
```bash
python detect.py --source path/to/video.mp4
```

3. To run detection using webcam:
```bash
python detect.py --source 0
```

## Model Training
The model was trained on a custom dataset of safety helmet images. Training details and parameters can be found in `YOLO_Helmet_Safety.ipynb`.

## Project Structure
- `YOLO_Helmet_Safety.ipynb`: Main notebook containing model training and testing code
- `README.md`: Project documentation
- `models/`: Trained model weights
- `data/`: Training and testing datasets

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.