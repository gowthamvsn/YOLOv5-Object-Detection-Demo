# YOLOv5 Object Detection Demo

This project demonstrates how to run object detection using a pretrained
YOLOv5 model with PyTorch.

The goal is to show:
- How to load a pretrained YOLOv5 model
- How to run inference on images
- How to visualize and inspect detection results

This is an inference-only demo and does not involve training or fine-tuning.

---

## Why This Project?

YOLO (You Only Look Once) is a widely used real-time object detection model.
This project serves as a minimal, clear example of how to:

- Use pretrained computer vision models
- Perform inference on custom images
- Interpret bounding box predictions

It is intended as a learning and demonstration project.

---

## Model Used

- **YOLOv5s**
- Pretrained on the COCO dataset
- Loaded via `torch.hub`

---

## Features

- Image inference from URLs and local files
- Bounding box visualization
- Detection outputs in tensor and pandas formats

---

## File Structure

```
src/
└── yolo_inference.py
```

---

## How to Run

```bash
pip install -r requirements.txt
python src/yolo_inference.py


## Author

Gowtham Vuppaladhadiam
