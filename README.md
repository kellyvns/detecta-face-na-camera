# Face Detection with Python and OpenCV

A simple Python project that detects faces in real-time using the user's webcam.  

The program uses **OpenCV** and a pre-trained Haar Cascade classifier to identify faces in the video feed.

---

## 💻 Technologies and Libraries

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="30px"> **Python 3.x**  
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" width="30px"> **OpenCV**

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-project.git
```

2. Install OpenCV (if not already installed):

```bash
pip install opencv-python
```

3. Run the Python script:

```bash
python face_detection.py
```

4. To stop the detection, press the `q` key.

---

## 🔍 How It Works

1. The program opens the computer's webcam.  
2. Converts each captured frame to grayscale.  
3. Uses the **Haar Cascade** to detect faces.  
4. Draws blue rectangles around each detected face.  
5. Displays the video in real-time with the detections.  

---

## ⚠️ Notes

- Make sure your webcam is working properly.  
- Face detection works best under good lighting conditions.  
- You can adjust the `detectMultiScale` parameters to improve detection accuracy.
