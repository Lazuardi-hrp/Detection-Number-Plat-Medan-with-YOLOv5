# Detection Number Plat Medan with YOLOv5

<div align="center">
  <img width="75%" src="https://github.com/Lazuardi-hrp/Detection-Number-Plat-Medan-with-YOLOv5/blob/main/Data/Roboflow%20%2B%20YOLOv5.png"></a>
</div>
</br>
This project aims to identify vehicle license plates using the YOLO (You Only Look Once) method with the YOLOv5 model and a custom dataset prepared through the Roboflow platform. With this approach, the system can quickly and accurately detect vehicle license plates in images, contributing to the development of an efficient automatic identification solution.

Dataset detect-vehicle-number-plate: [Download Dataset]( https://app.roboflow.com/universitas-negeri-medan/detect-vehicle-number-plate/deploy/2)

## <h4>Steps Covered in this Tutorial</h4>
In this tutorial, we will walk through the steps required to train YOLOv5 on your custom objects. We use a public blood cell detection dataset, which is open source and free to use. You can also use this notebook on your own data.

To train our detector we take the following steps:
- Install YOLOv5 dependencies
- Download custom YOLOv5 object detection data
- Write our YOLOv5 Training configuration
- Run YOLOv5 training
- Evaluate YOLOv5 performance
- Visualize YOLOv5 training data
- Run YOLOv5 inference on test images
- Export saved YOLOv5 weights for future inference


## <div align="center">Result</div>

<div align="center">
  <img width="30%" src="https://github.com/Lazuardi-hrp/Detection-Number-Plat-Medan-with-YOLOv5/blob/main/Data/Hasil.png"></a>
</div>
</br>
<p>The image you've uploaded displays results from testing a YOLOv5 (You Only Look Once, version 5) object detection model. The model is trained to detect and localize number plates in various scenes.</p> 
</br>

<div align="center">
  <img width="50%" src="https://github.com/Lazuardi-hrp/Detection-Number-Plat-Medan-with-YOLOv5/blob/main/Data/visualize%20Tensorboard%20-%20matriks.png"></a>
</div>
</br>
The TensorBoard visualization presents the training progress of a machine learning model, specifically in object detection, over approximately 50 epochs. Here's a summarized interpretation:


- The mAP at IoU=0.5, a metric for object detection, shows the model's accuracy with a 50% overlap threshold. The upward trend suggests improved accuracy.
- mAP at IoU ranging from 0.5 to 0.95: This is a more comprehensive performance metric, averaging precision across multiple IoU thresholds. 
- Precision: The precision plot measures the ratio of true positive predictions to the total number of positive predictions (true and false positives).  
- Recall: Recall assesses the model's ability to find all the relevant cases (true positives) within the data.  
- Box Loss: This represents the error in the bounding box predictions. The decreasing trend in this loss plot shows that the model is consistently improving at localizing objects accurately. 
- Class Loss: This loss relates to the error in predicting the correct class labels for the detected objects.   
- Object Loss: This loss measures the model's performance in detecting the presence of an object.
