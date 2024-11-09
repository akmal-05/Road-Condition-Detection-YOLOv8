# Road Condition Detection Using YOLOv8

## Project Overview
This project uses the YOLOv8 object detection framework to identify various road conditions in Gilgit, Baltistan. The model is trained to detect right turns, left turns, straight roads, and landslide areas.

## Steps in the Project
1. **Data Collection**: Captured 337 images from roads in Gilgit, categorized into classes: `Landslide`, `Left Turn`, `Right Turn`, `Straight Road`, and `Other`.
2. **Data Labeling**: Labeled images using Roboflow for consistent annotations.
3. **Model Training**: Trained using YOLOv8 over 50 epochs with a batch size of 16 and image size of 224x224.
4. **Evaluation**: Model evaluated on precision, recall, and mAP metrics.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/akmal-05/Road-Condition-Detection-YOLOv8.git

2. Install dependencies:
bash
 
pip install -r requirements.txt
requirements.txt

```text
ultralytics
roboflow
ipython
pillow
