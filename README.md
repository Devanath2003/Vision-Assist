# Vision-Assist 🎯

This project demonstrates real-time object detection using the YOLOv5 model and OpenCV via a webcam feed. It identifies multiple objects in live video streams and draws bounding boxes with class labels and confidence scores.

## Overview

-  Captures live video from webcam
-  Uses a pre-trained YOLOv5 model (`yolov5s.pt`) for detection
-  Detects 80 object classes from the COCO dataset
-  Draws bounding boxes with class names and confidence
-  TTS is used to describe objects
-  Thermal depth verification
-  Built with Python, OpenCV, and PyTorch

## Technologies Used

- Python
- OpenCV
- PyTorch
- YOLOv5 (via Ultralytics)
- Jupyter Notebook

## How to Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/live-object-detection.git
   cd live-object-detection
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download YOLOv5 repository**
   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5
   pip install -r requirements.txt
   ```

4. **Place your notebook** inside the `yolov5` folder or adjust the paths accordingly.

5. **Run the notebook**
   Open `Live_Object_Detection.ipynb` and run all cells.

## 📝 Notes

- Ensure your webcam is accessible and enabled.
- For better performance, consider switching to a GPU runtime (e.g., using Google Colab).
- You can replace `yolov5s.pt` with other YOLOv5 model weights for higher accuracy (e.g., `yolov5m.pt`, `yolov5l.pt`).

## 📄 License

This project is open-source under the [MIT License](LICENSE).
