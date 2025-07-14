# gesture-and-sign-language-recognition
This project recognizes American Sign Language (ASL) letters and hand gestures (like , fist, hello, Peace,  Like,  Dislike) using real-time webcam input.
## Dependencies
- TensorFlow
- Keras
- OpenCV
- NumPy
- gTTS
- Pygame
- Pillow



## Dataset:-

 ASL dataset from:-https://www.kaggle.com/datasets/grassknoted/asl-alphabet
 
 Custom gesture using webcam:- https://www.kaggle.com/datasets/tanvi19005/hand-gesture-dataset


## How to Run the Project

-Download the following files and place them in the same folder:

finalcode.ipynb

asl_mobilenet_model.keras

mobilenetv2_gesture_model.keras

-Install dependencies

-Open Jupyter Notebook and run finalcode.ipynb

Note:
If you saved your .keras model files in a different location, make sure to update the model path in the notebook:

  gesture_model = load_model("path_to/mobilenetv2_gesture_model.keras")
  
  asl_model = load_model("path_to/asl_mobilenet_model.keras")

