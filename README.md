# Chess-Pieces-Detection

In this project I created a Chess Pieces Detection model. I captured 150 images and then anotated them using Roboflow. 
Here are the outputs of the model.

![Screenshot 2023-03-09 224717 (2)](https://user-images.githubusercontent.com/83948976/224113531-87f01c68-abf9-456b-86c9-d9db607508c4.png)

In the model creation proecss I used,
          
          1. YOLO V8 
          2. Roboflow website
          
YOLO, in words ‘You Only Look Once’ is a popular object detection algorithm. It is popular for its speed and efficiency. In this implementation I used YOLO V8, it is the latest virsion of YOLO.
• It is faster and more precise than previous versions.
• It supports both CPU and GPU with PyTorch.
• It can detect objects across multiple scales and aspect ratios.
• It can segment images into semantic regions with different labels.
• It can classify images into categories with confidence scores  

Roboflow is a platform that helps you create computer vision applications by managing, preprocessing, augmenting and versioning datasets. It also allows you to train and deploy models with various frameworks and tools. Roboflow can be used for various purposes such as face detection, object tracking, image classification, etc. In the Roboflow site there are various types of datasets which already annotated. No need to download the dataset, API key did the all work in the implementation stage, making it easy to use. 

You can try this by yourself. All the code that you need included in the above notebook. but you have to copy the API key from the Roboflow website. 

Dataset Link - https://universe.roboflow.com/models-mc3oh/chess-pieces-detection-v4fl1 

Log into the link, click download dataset and follow the steps. it is easy, you can find. 


