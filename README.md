# Crack-Detection-YOLOv4
Completed a computer vision assignment based on localizing and classifying different types of damage on vehicles windshield. YOLOv4 has been employed for balancing fast object detection as well as accurate damage classification.
# Dataset
The entire dataset consists of 3 different types of damages: crack, bullseye, and scratch. For training the YOLOv4 model, the dataset was divided into a 75:25 ratio i.e., 43 images in training data and remaining 14 images in the test dataset.
# Results
The training was done for approximately 2600 epochs. The training history graph is shown below.
<img src="https://raw.githubusercontent.com/Vivek-23-Titan/Crack-Detection-YOLOv4/master/images/Final_History.png" width=400>

The graph shows that the highest map score is 71.30%. After 1700 epochs, although the training loss continues to decrease, the map values start to fluctuate around 69%.
* For detection results, map value of 69.21% with 65.08% IoU was used instead of map of 71.30% with 52.99% IoU for better bounding box detections.
