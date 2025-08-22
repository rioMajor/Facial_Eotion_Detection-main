# **Facial Emotion Detection**

This project implements a real-time facial emotion detection system using OpenCV and a pre-trained deep learning model. It captures live video from a webcam, detects faces, and classifies emotions into categories such as happy, sad, angry, and more.

---

## **Features**
- Real-time face detection using Haar Cascade.
- Emotion prediction using a pre-trained deep learning model (`emotions.h5`).
- Displays the detected face with the predicted emotion label in a live video feed.
- Supports multiple emotion categories: angry, disgust, fear, happy, sad, surprise, and neutral.

---

## **Technologies Used**
- **Python**: Programming language for implementation.
- **OpenCV**: For real-time face detection and video processing.
- **NumPy**: For numerical and array operations.
- **Keras**: For loading and using the pre-trained emotion detection model.

---

## **Setup and Installation**

### **1. Clone the Repository**
Clone the repository to your local machine:
```bash
git clone https://github.com/Shashank452/Facial_Eotion_Detection.git
cd Facial_Eotion_Detection
```
### **2. Install Dependencies**
Install the required Python libraries using the requirements.txt file:
```bash
pip install -r requirements.txt
```
### **3. Required Files**
- Haar Cascade File: The haarcascade_frontalface_default.xml is required for face detection. It is included in OpenCV's default data files.
- Pre-trained Model: Download or provide the pre-trained model file (emotions.h5) and place it in the project directory.

---

## **How to Run**
1. Ensure that your webcam is connected and functional.
2. Execute the script:
```bash
python emotion_detection.py
```
3. The live video feed will display detected faces with the predicted emotion labels.
4. Press q to quit the application.

---

## **Project Structure**
```bash
facial-emotion-detection/
│
├── emotion_detection.py  # Main script for emotion detection
├── emotions.h5           # Pre-trained deep learning model
├── requirements.txt      # Required Python libraries
└── README.md             # Project documentation
```

---

## **Future Enhancements**
- Train a custom deep learning model for improved accuracy and more emotion categories.
- Optimize the system for detecting multiple faces simultaneously.
- Integrate a GUI for a more user-friendly interface.
- Add support for input images or video files.

---

## **Contact**
If you have any questions or suggestions, feel free to reach out:
- **Author**: [Shashanka C K](mailto:shashankcks2002@gmail.com)  
- **GitHub**: [Shashank452](https://github.com/Shashank452)  
- **LinkedIn**: [Shashanka C K](https://www.linkedin.com/in/shashanka-c-k)
