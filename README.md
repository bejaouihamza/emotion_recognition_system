🎭 Real-Time Emotion Detection using DeepFace & OpenCV

This project uses DeepFace, TensorFlow, and OpenCV to perform real-time facial emotion detection from a webcam stream.
It detects a face, analyzes the dominant emotion, and displays the result with a colored bounding box representing each emotion.

📌 Features

✔ Real-time webcam emotion recognition
✔ Face detection + emotion classification
✔ Color-coded bounding boxes
✔ Supports all DeepFace emotions:

happy

sad

angry

fear

surprise

disgust

neutral

✔ Works even if the face is partially visible
✔ GPU-ready (if TensorFlow GPU is installed)
✔ No crash when the face is not detected (enforce_detection=False)

🧠 Emotion → Color Mapping
Emotion	Color (BGR)
happy	Green (0,255,0)
sad	Red (0,0,255)
surprise	Yellow (0,255,255)
neutral	White (255,255,255)
angry	Black (0,0,0)
fear	Purple (255,0,255)
disgust	Blue-ish (255,0,0)
