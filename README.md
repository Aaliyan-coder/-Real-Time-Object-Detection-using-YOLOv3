# 🧠 Real-Time Object Detection using YOLOv3

This project demonstrates **Object Detection** using the **YOLOv3 (You Only Look Once)** deep learning model with OpenCV in Python. It processes an input image and detects multiple objects within it, highlighting them with bounding boxes and class labels.

---

## 📌 Project Overview

Object detection is a powerful computer vision technique used to identify and locate objects in an image or video. In this project, the **YOLOv3 model** is used to detect objects from the **COCO dataset** classes in a sample image (`men.jpg`). The model highlights detected objects by drawing bounding boxes and labeling them with confidence scores.

---

## 🖼️ Example Output

> Replace with an actual image once generated

![Object Detection Output](example_output.png)

---

## 📂 Project Structure

```
├── yolov3.cfg             # YOLOv3 model configuration file  
├── yolov3.weights         # Pre-trained YOLOv3 weights  
├── coco.names             # COCO dataset class labels  
├── men.jpg                # Input image  
├── object_detection.py    # Main detection script  
```

---

## 🚀 Features

- Detects **80+ object categories** from the COCO dataset  
- Draws bounding boxes and labels with **confidence scores**  
- Applies **Non-Maximum Suppression (NMS)** to reduce overlapping boxes  
- Uses **OpenCV DNN module** for inference  
- Output visualization using **matplotlib**

---

## 🛠️ Requirements

- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  

Install dependencies via pip:

```bash
pip install opencv-python numpy matplotlib
```

---

## ▶️ How to Run

Clone this repository:

```bash
git clone https://github.com/yourusername/object-detection-yolov3.git
cd object-detection-yolov3
```

Download YOLOv3 weights:

```bash
wget https://pjreddie.com/media/files/yolov3.weights
```

Ensure the following files are in your directory:

- `yolov3.cfg`: [Download here](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)  
- `coco.names`: [Download here](https://github.com/pjreddie/darknet/blob/master/data/coco.names)  
- `yolov3.weights`: [Download here](https://pjreddie.com/media/files/yolov3.weights)

Run the script:

```bash
python object_detection.py
```

---

## ✅ Output

The script will open and display the image with bounding boxes around detected objects.

Detected objects will also be printed in the terminal:

```yaml
Detected objects:
person: 0.98
backpack: 0.76
bottle: 0.67
```

---

## 📚 Acknowledgements

- [YOLOv3 - Original Paper](https://pjreddie.com/media/files/papers/YOLOv3.pdf)  
- [Darknet by Joseph Redmon](https://github.com/pjreddie/darknet)  
- [COCO Dataset](https://cocodataset.org/)

---

## 🧑‍💻 Author

**Aaliyan Arif**  
AI & Computer Vision Enthusiast  
[GitHub Profile](https://github.com/Aaliyan-coder)
