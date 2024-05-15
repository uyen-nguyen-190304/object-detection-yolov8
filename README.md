# **AI VIETNAM: Object Detection with YOLOv8**

## **I. Project Description**
Object Detection is a problem in the field of Computer Vision. Our task is to build a program that returns the coordinates of the bounding box and the class name of objects in the picture that we want to detect. In this project, we will learn about and practice implementing a Python program for Human Detection in an image using an algorithm called YOLOv8.

## **II. Introduction**
Object Detection involves identifying objects within an image and providing the coordinates of bounding boxes along with the class names of the detected objects. In this project, we focus on implementing YOLOv8 for object detection.

## **III. Project Implementation**

### **1. Download YOLOv8 Source Code from GitHub**
To use YOLOv8, we need to download the source code from the [YOLOv8 GitHub repository](https://github.com/ultralytics/ultralytics). Clone the code to your environment and install the required libraries using the pip command.

### **2. Download Pretrained Model**
Download the pretrained model file from YOLOv8 from [here](https://github.com/ultralytics/assets/releases/download/v0.0.0/yolov8s.pt) using the curl command, wget command, or by downloading directly from the GitHub and placing it into the corresponding folder.

### **3. Prepare the Data**
To train YOLOv8 on any dataset, prepare a directory containing the training and testing images, with corresponding labels. Ensure the dataset is structured correctly and create a `data.yaml` file to specify the dataset paths and classes.

### **4. Training the Model**
Set the training parameters including image size, batch size, epochs, dataset information, and pretrained weights. Train the model using the appropriate command and evaluate its performance to find the best model.

### **5. Labeling the Data**
For supervised learning, ensure that each sample in the training dataset has corresponding labels. To add more data or create a new dataset, label the data manually using tools like `labelImg`.

## **IV. Conclusion**
In this notebook, we explored the process of setting up and using YOLOv8 for object detection. We began with an introduction to object detection, followed by downloading the YOLOv8 source code and installing the necessary libraries. We then prepared the dataset by organizing the directory structure and creating a `data.yaml` file. The training process was discussed, including important parameters such as image size, batch size, epochs, dataset paths, and pretrained weights. We also covered model evaluation to optimize performance. Lastly, we emphasized the importance of labeled data and introduced `labelImg` for manual data labeling. By following these steps, we can effectively utilize YOLOv8 for various object detection tasks.

## **V. Usage**
1. Clone the YOLOv8 source code from GitHub.
2. Install the required libraries using pip.
3. Download the pretrained model file and place it in the appropriate directory.
4. Prepare the dataset by organizing the directory structure and creating a `data.yaml` file.
5. Train the model using the provided commands and evaluate its performance.

## **VI. Dependencies**
- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Ultralytics library
- LabelImg (for manual data labeling)

## **V. Contact**
For any questions or issues, please contact Uyen Nguyen via [nguyen_u1@denison.edu](mailto:nguyen_u1@denison.edu).