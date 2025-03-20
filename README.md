# Facial-Emotion-Recognition-using-OpenCV-and-Deepface
This project implements real-time facial emotion detection using the `deepface` library and OpenCV. It captures video from the webcam, detects faces, and predicts the emotions associated with each face. The emotion labels are displayed on the frames in real-time.

## How to run code : 
1. **Import Libraries**: Import `cv2` for video processing and `deepface` for emotion detection.  
2. **Load Face Detector**: Initialize the Haar cascade classifier using `cv2.CascadeClassifier()`.  
3. **Start Video Capture**: Use `cv2.VideoCapture()` to capture video from the default webcam.  
4. **Process Frames Continuously**: Convert each frame to grayscale and detect faces using `face_cascade.detectMultiScale()`.  
5. **Detect and Analyze Emotion**: Extract the face ROI, preprocess it, and use `deepface` to predict the emotion.  
6. **Display Results**: Draw a rectangle around detected faces, label them with predicted emotions, and show the frame using `cv2.imshow()`.  
7. **Exit on Key Press**: Stop processing if the 'q' key is pressed.
14. Release the video capture and close all windows using `cap.release()` and `cv2.destroyAllWindows()`.

