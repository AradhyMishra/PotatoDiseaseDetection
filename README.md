# PotatoDiseaseDetection
Object Detection Algorithm used for detecting disease in plant leaves.


This code demonstrates real-time object detection using the YOLOv8 model from the Ultralytics library. The YOLO (You Only Look Once) algorithm is a popular real-time object detection algorithm. In this implementation, the script captures video frames from a webcam, applies object detection using YOLOv8, and overlays bounding boxes and class labels on detected objects.

Dependencies
OpenCV (cv2) Ultralytics (yolov8) NumPy PyTorch (torch)

Install the required dependencies using the following:
bash Copy code pip install opencv-python ultralytics numpy torch Model and Class Names The YOLOv8 model is loaded using Ultralytics, and the COCO dataset class names are used for object detection. The class names include various common objects such as people, vehicles, animals, and household items.
