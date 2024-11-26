# Dataset-of-maize-seedlings
  Dataset of maize seedlings taken by UAV

  Download the dataset from:https://universe.roboflow.com/maize-pjuvu/maize-001

  This study captures the image data using a UAV at the Jinan Branch of the National Maize Improvement Center in China, with the specific location and orthophoto image illustrated in figure. To ensure optimal lighting conditions, we set the data collection time between 11 a.m. and 2 p.m. The image resolution is 5280 * 3956 pixels, with a flight altitude of 20 meters above ground, and we capture images every 2 seconds. We utilize RTK technology to achieve centimeter- level positioning accuracy. We set the sideways overlap at 70%, and the forward overlap at 80% to minimize gaps and distortions in image stitching, ensuring data continuity and integrity. The dataset creation process involves three main steps: firstly, we import the drone-captured images into Pix4d software and stitch them into a continuous, seamless image. Secondly, to reduce memory pressure and improve compu- tational efficiency during computer processing, we segment the large stitched image into images of 640 * 640 pixels. Finally, we upload the segmented images to the Roboflow website, where we annotate maize seedlings in each image. We divide the final data into training, testing, and validation sets in a ratio of 7:2:1.

![image](https://github.com/user-attachments/assets/acfafb6c-d2b5-4745-b6cd-ca721ee3fb05)

  Rapid Maize Seedling Detection Based on Receptive-Field and Cross-Dimensional Information Interaction
This dataset has been used in the *Rapid Maize Seedling Detection Based on Receptive-Field and Cross-Dimensional Information Interaction* and has achieved good results. This paper has been accepted by IEEE International Conference on Systems, Man, and Cybernetics (IEEE SMC 2024).
![1006_1](https://github.com/user-attachments/assets/f5c8a8c8-75eb-43b7-b393-946d71fb928c)
