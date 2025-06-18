# YOLOv8 Real-Time Object Detection

This project uses the [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) model to perform real-time object detection on a webcam feed (or optional video file). It displays the bounding boxes, class names, and confidence scores on the live video stream using OpenCV and CVZone.

## 📸 Features

- Real-time detection from webcam or video file
- Bounding box visualization
- Object class name and confidence score display
- Lightweight YOLOv8n model for fast inference

## 🚀 Requirements

Install dependencies using the following command:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install ultralytics opencv-python cvzone
```

## 📂 File Structure

```bash
├── yolov8_object_detection.py   # Your main Python script
├── requirements.txt             # Required Python packages
├── README.md                    # This file
```

## 📹 Usage

### Using Webcam (default)

```bash
python yolov8_object_detection.py
```

### Using Video File

Uncomment the video path line and comment out the webcam line:

```python
# cap = cv2.VideoCapture(0)  # Webcam
cap = cv2.VideoCapture(r"C:\Users\gandh\Downloads\cars.mp4")  # Video file
```

## 🧠 Model Used

- YOLOv8n (nano version) for fast and efficient inference.
- Downloaded via Ultralytics package (`yolov8n.pt`).

## 📸 Example Output

![demo](https://github.com/ultralytics/assets/raw/main/yolov8/v8.gif)

## 📜 License

This project is licensed under the MIT License.

---

Made with ❤️ using Python and YOLOv8
