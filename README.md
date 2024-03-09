# computer-vision-for-food-quality-assessment
This project utilizes computer vision techniques to monitor banana quality from ripe to rotten.  The core implementation employs the YOLOv8n model to detect and annotate bananas in video footage, classifying them as fresh, ripe, or rotten.

**Project Overview**

Spot the Rot is a computer vision project designed to assess banana quality. It uses a custom-trained YOLOv8n object detection model to analyze video footage, identifying and classifying bananas as fresh, ripe, or rotten. The model was trained on a dataset of 1525 images, resulting in highly efficient and accurate predictions.

**Output**


https://github.com/tech-aakash/computer-vision-for-food-quality-assessment/assets/162134525/cd1afc3b-01cf-47b7-8971-87d3d3fb2566



**Performance**

Inference on video input is remarkably fast, taking a mere 55 seconds. This speed enables near real-time banana quality assessment. The model training process took 2.8 hours, demonstrating a reasonable time investment for achieving such robust results. 
![results](https://github.com/tech-aakash/computer-vision-for-food-quality-assessment/assets/162134525/fb8df725-e90f-4f59-88e9-a2aca04fca76)

**Technical Details**

The YOLOv8n architecture was leveraged for its efficiency and suitability for real-time applications. To tailor the model for optimal banana detection, a custom dataset of 1525 images was utilized during the training process.
![confusion_matrix](https://github.com/tech-aakash/computer-vision-for-food-quality-assessment/assets/162134525/21a2f67f-8887-485d-a589-d7a0e049ae3b)

**Potential Applications**

Spot the Rot has potential applications in the food industry, including:

* Quality control in banana production facilities
* Automated inventory management in supermarkets
* Optimization of food waste reduction efforts 

 
