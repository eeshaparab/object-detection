## Object Detection using YOLO
YOLO (You Only Look Once) is a popular and fast object detection algorithm that uses a single convolutional neural network (CNN) to detect objects in images and videos. It's considered a valuable tool for real-time applications because it can process images very quickly. 

# Here's how YOLO works:
  1. Divide the image into a grid
  2. For each grid cell, predict multiple bounding boxes and class probabilities simultaneously
  3. Filter out low-confidence predictions
  4. Remove overlapping boxes using a technique called non-maximum suppression
  5. Output the remaining guesses as rectangles and object labels

# Features
  - 🚀 Real-time multi-class object detection  
  - 📸 Works on both images and webcam/video feeds  
  - 📊 Uses YOLOv5 pre-trained model  
  - 🤖 Detects common object categories (e.g., person, car, chair, etc.)  
  - 📦 Outputs bounding boxes with class labels and confidence scores

# Technology Stack
  | Technology | Purpose |
  | Python | Main programming language |
  | OpenCV | Image/video processing |
  | YOLOv5 | Object detection model |
  | PyTorch | Deep learning framework |



