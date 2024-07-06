# Helmet Detection With YOLOv10n

Before diving into a full-fledged helmet detecstion project, this repository provides a dedicated space for rigorously testing YOLOv10n in file (object_dectection_with_YOLOv10n.ipynb). Explore different test cases, fine-tune model parameters and gain valuablke insights into the strengths and limitations of YOLOv10n for helmet detection tasks.

## Key Features

- Testing YOLOv10n
- Fine-tuning YOLOv10n for helmet detection

## Installation

Firstly, we need to clone my source in your local computer
"""
git clone git@github.com:NiranVu/helmet-detection-yolo-v10n.git
"""
Then, running file "helmet_detection_yolo_v10.ipynb" in order to download all necessary libs and packages for fine-tuning
Finally, we can use this model for predicting people, having helmet or not by writing:
"""
TRAINED_MODEL_PATH ="runs/detection/train/weights/best.pt"
model = YOLOv10(TRAINED_MODEL_PATH)
result = model(***)
"""
In *** we can fill with image, video, link path for model to predict
