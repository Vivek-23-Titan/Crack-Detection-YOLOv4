# Crack-Detection-YOLOv4
Completed a computer vision assignment based on localizing and classifying different types of damage on vehicles windshield. YOLOv4 has been employed for balancing fast object detection as well as accurate damage classification.
## Dataset
The entire dataset consists of 57 images having 3 different types of damages: crack, bullseye, and scratch. For training the YOLOv4 model, the dataset was divided into a 75:25 ratio i.e., 43 images in training data and remaining 14 images in the test dataset.
## Code
Entire code is available in the [Juypter Notebook](https://github.com/Vivek-23-Titan/Crack-Detection-YOLOv4/blob/master/Crack_Detection_YOLOv4.ipynb) format. For further YOLOv4 details please refer https://github.com/AlexeyAB/darknet repository.
## Results
The training was done for approximately 2600 iterations. The training history graph is shown below.

<img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/Final_History.png" width=500>

The graph shows that the highest map score is 71.30%. After 1700 epochs, although the training loss continues to decrease, the map values start to fluctuate around 69%.
* For detection results, map value of 69.21% with 65.08% IoU was used instead of map of 71.30% with 52.99% IoU for better bounding box detections.
## Damage Detection
All the test images were properly detected and labeled. Few of the detections are displayed below and rest are available in the [images](https://github.com/Vivek-23-Titan/Crack-Detection-YOLOv4/tree/master/images) folder.
### Crack
<img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/57.png" width=400> <img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/scratch1.png" width=400>
### Bullseye
<img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/29.png" width=400> <img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/46.png" width=400>
### Scratch
<img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/52.png" width=400> <img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/55.png" width=400>
## Citation
```
@article{bochkovskiy2020yolov4,
  title={{YOLOv4}: Optimal Speed and Accuracy of Object Detection},
  author={Bochkovskiy, Alexey and Wang, Chien-Yao and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2004.10934},
  year={2020}
}
```
