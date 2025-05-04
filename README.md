### Gear Teeth Count Using YOLO

This project uses YOLOv11 to detect and count gear teeth in images, implemented in a Google Colab notebook with the Ultralytics YOLO framework and Roboflow for dataset management. The trained model (best.pt) is included for inference.

### Project Overview

The project automates gear teeth counting via object detection. A YOLOv11n model is fine-tuned on a custom Roboflow dataset, achieving mAP50 of 0.99 and mAP50-95 of 0.694 after 20 epochs. The notebook covers dataset downloading, training, inference, and visualization.

### Repository Contents:-
Gear_Teeth_Count_YOLO.ipynb: Colab notebook with all project code.
best.pt: Trained YOLOv11 model weights.

### Setup Instructions

## Clone the Repository:
git clone https://github.com/your-username/gear-teeth-count-yolo.git
cd gear-teeth-count-yolo

### Open in Colab:-
Upload Gear_Teeth_Count_YOLO.ipynb to Google Colab or open it directly from GitHub.

## Install Dependencies
Run in the notebook:
  !pip install roboflow
  !pip install ultralytics

### Upload Model:-

Upload best.pt to Colab (e.g., /content/) for inference, or retrain to generate a new best.pt.


### Dataset

#### Details

Splits: 908 training images, 49 validation images.

The notebook downloads the dataset via the Roboflow API.

