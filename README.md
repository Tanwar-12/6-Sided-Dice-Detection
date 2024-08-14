# INNOVATIVE IMAGE RECOGNITION FOR GAMING ENHANCEMENTS: ADVANCED SIX DICE DETECTION USING YOLOv5
## OBJECTIVE
**Implement a robust computer vision system using YOLOv5 to accurately detect and recognize dice in images, specifically focusing on scenarios where there are six dice**.

## DATASET INFORMATION : 
1.Total 594 images with 6 class

2.For training 519 Images,testing 26,validation 49

3.Create bounding boxes with the help of labelimg tool and makesense.ai website

## DATA COLLECTION:
**Data Collected from roboflow**
**Link**: https://universe.roboflow.com/dice-7xpee/deice-detect/dataset/3

## TASK: OBJECT DETECTION

# WORKFLOW:
  ## Data Preparation:
  * Total 594 images with 6 class
  * For training 519 Images,testing 26,validation 49
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
  ![train folders](https://github.com/Tanwar-12/Face-Mask-Detection/assets/110081008/69b19a8e-2f81-4d9b-a762-ffa73ac59be1)

## STEPS TO USE YOLOV5: 
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.

   ## STEPS BEFORE TRAINING CUSTOM DATASET :
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## TRAINING YOLOV5 MODEL:
* Set images size 640 with batch of 8.
* Train model around 100 epochs .
* Visualise the training metrics with the help of tensorboard.
  ## RESULT
  ![image](https://github.com/user-attachments/assets/c1303278-3e36-4a69-8770-5e5d3fa43e74)


 ## TESTING IMAGES USING TEST DATA:
 ![image](https://github.com/user-attachments/assets/250ee635-9e99-47d5-b1e0-06580c008ff0)

 ## TESTING VIDEO DEMO :
 
 https://github.com/Tanwar-12/6-Sided-Dice-Detection/blob/main/Dice_Detected.mp4



