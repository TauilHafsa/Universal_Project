# Drowsiness-detection-while-driving

We have developed a comprehensive solution to prevent drivers from falling asleep while driving, utilizing the power of deep learning (PyTorch) and OpenCV.

## Model Training
Our approach involves training a Convolutional Neural Network (CNN) using PyTorch and leveraging transfer learning on the MRL Eye Dataset (http://mrl.cs.vsb.cz/eyedataset). This dataset comprises diverse eye data categories, including male, female, open, closed, with sunglasses, and without sunglasses. The model accurately detect whether the eyes are open or closed.

## Real-Time Implementation
We integrate the system with OpenCV to access the camera in real-time, capturing the driver's eyes as input for the model. The model's output is binary, where 0 signifies open eyes, ensuring no intervention is needed. Conversely, a value of 1 indicates closed eyes, if they still close for a period of time, an alarm is activated, minimizing the risk of drowsiness while driving.


<img width="460" alt="Capture d’écran 2023-05-30 200256" src="https://github.com/TauilHafsa/Academic-Projects/assets/150071317/aee9a6a2-ffd6-45a0-8732-f8f8c2d48f5f">
