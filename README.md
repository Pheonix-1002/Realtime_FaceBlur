# 🎥 Real-Time Face Blur using OpenCV DNN

A real-time computer vision project that detects human faces from a live webcam feed and automatically blurs them using OpenCV's Deep Neural Network (DNN) module. This project demonstrates privacy-preserving video processing using a pre-trained SSD face detection model.

---

## ✨ Features

- 🎯 Real-time face detection
- 👤 Automatic Gaussian blur for detected faces
- 📹 Live webcam video processing
- ⚡ Fast inference using OpenCV DNN
- 🚫 Displays **"No Face Detected!"** when no faces are found
- 🧠 Uses a pre-trained SSD Caffe face detection model

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- OpenCV DNN Module
- Jupyter Notebook

---

## 📂 Project Structure

```text
Face_Blur_Realtime/
│
├── main1.ipynb
├── deploy.prototxt
├── res10_300x300_ssd_iter_140000_fp16.caffemodel
 README.md
requirements.txt
```

---

## 🧠 Pre-trained Model

The project uses OpenCV's pre-trained SSD face detector.

Model files:

- `deploy.prototxt`
- `res10_300x300_ssd_iter_140000_fp16.caffemodel`

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Pheonix-1002/Realtime_FaceBlur.git

cd Realtime_FaceBlur/Face_Blur_Realtime
```

### Install dependencies

```bash
pip install opencv-python numpy jupyter
```

---

## ▶️ Run the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
main1.ipynb
```

Run all cells to start the webcam.

Press **`q`** to exit the application.

---

## ⚙️ Workflow

1. Capture frames from the webcam.
2. Convert each frame into a blob.
3. Perform face detection using OpenCV's DNN model.
4. Extract the detected face region.
5. Apply Gaussian Blur.
6. Display the processed video stream.

---

## 📈 Future Improvements

- Face pixelation mode
- Blur intensity adjustment
- Video file support
- Face tracking
- YOLO-based face detection
- GPU acceleration using CUDA

---

## 👨‍💻 Author

**Deepanshu Sharma**

If you found this project useful, consider giving it a ⭐ on GitHub.
