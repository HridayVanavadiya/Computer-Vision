# Computer Vision with OpenCV

This repository contains a collection of **Computer Vision experiments implemented using Python and OpenCV**.  
The notebooks focus on fundamental image processing and classical computer vision techniques commonly used in academic coursework and practical applications.

---

## 🛠️ Technologies Used

- Python 3.x  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 🔬 Experiments & Analysis

---

### **1️⃣ Morphological Operations**
**Notebook:** `unit_1_morphological_operations.ipynb`

#### Concepts Implemented
- Erosion  
- Dilation  
- Opening  
- Closing  
- Morphological Gradient  

#### Purpose
Morphological operations are used to:
- Remove noise from images  
- Enhance object boundaries  
- Fill gaps in binary images  

#### Observations
- Erosion removes small white noise  
- Dilation enhances object regions  
- Opening is effective for noise removal  
- Closing fills small holes inside objects  

---

### **2️⃣ Object Detection using Template Matching**
**Notebook:** `unit_2_Object detection by template matching.ipynb`

#### Algorithm Used
- Template Matching (`cv2.matchTemplate`)  
- Matching method:
  - `TM_CCOEFF_NORMED`  

#### Working Principle
The template image is slid over the source image, and similarity scores are computed at each location to determine the best match.

#### Limitations
- Sensitive to scale and rotation  
- Works best when template size closely matches the object size  

---

### **3️⃣ Feature Detection using FAST Algorithm**
**Notebook:** `feature_detector_by_using_FAST_detector.ipynb`

#### Algorithm Used
- FAST (Features from Accelerated Segment Test)

#### Advantages
- Extremely fast feature detection  
- Suitable for real-time applications  

#### Output
- Keypoints detected and visualized on the image  
- Corners and interest points highlighted  

---

### **4️⃣ Hough Transform**
**Notebook:** `unit_4_hough_transform.ipynb`

#### Techniques Implemented
- Hough Line Transform  
- Hough Circle Transform  

#### Use Cases
- Lane detection  
- Shape detection  
- Structural analysis in images  

#### Observations
- Sensitive to parameter tuning (`threshold`, `minRadius`, `maxRadius`)  
- Highly effective for detecting geometric shapes  

---

### **5️⃣ Face Detection using Haar Cascades**
**Notebook:** `unit_5_face_detection.ipynb`

#### Algorithm Used
- Haar Cascade Classifier  

#### Working
- Pre-trained Haar features are used to detect frontal faces  
- Implemented using `haarcascade_frontalface_default.xml`  

#### Key Parameters
- `scaleFactor`  
- `minNeighbors`  
- `minSize`  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/HridayVanavadiya/Computer-Vision.git
