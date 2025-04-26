
# YOLO RoadNet

- Developed a real-time object detection system using YOLOv8 to accurately detect pedestrians and vehicles (cars, buses motorcycles, etc.) with high precision.
- Implemented spatial logic to automatically filter out persons seated inside vehicles, isolating only walking pedestrians for focused analysis.
- Automated frame-wise image extraction and YOLO-format label generation for scalable and structured dataset creation.

## Requirements

- OpenCV (pip install opencv-python)
- Ultralyitcs YOLO (pip install ultralytics and pip install YOLO)
- tqdm (pip install tqdm)

## How to run 

 - Execute the Filtering_human_in_vehicle.ipynb script to process the video and generate the dataset.
-  View the Results
-  Open the new_dataset folder to see the results:
    - Processed frames: new_dataset/images
    - Label files: new_dataset/labels
- Visualized images (with bounding boxes): new_dataset/visualizations

### Sample Images

![0029](https://github.com/raktimyoddha07/YOLO_RoadNet/raw/main/sample-1.jpg)

![0823](https://github.com/raktimyoddha07/YOLO_RoadNet/raw/main/sample-2.jpg)
