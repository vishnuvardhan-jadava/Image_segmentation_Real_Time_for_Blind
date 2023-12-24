# Image_segmentation_Real_Time_for_Blind

The objective of this project is to enhance the safety and independence of visually impaired individuals navigating public spaces.

Our approach employs the YOLO object detection and segmentation model to identify potential obstacles within the camera’s field of view. Upon detection, the system promptly alerts the user, enabling them to respond appropriately and navigate their surroundings with increased confidence and security. This innovative application of technology aims to significantly improve the quality of life for those with visual impairments.

For object detection, we are using the YOLO pre-trained model: yolov8l.pt by Ultralytics. This model is trained in the famous COCO dataset. However, they can also be trained on custom datasets. For our project, a model trained on COCO is enough. So, we did not go for training the model on other datasets.


For segmentation, we use the YOLO pre-trained model: yolov8l-seg.pt by Ultralytics. This model is trained in the famous COCO dataset. It is designed for instance segmentation tasks.
