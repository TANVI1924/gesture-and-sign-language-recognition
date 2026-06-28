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

Note:-Images were augmented using augmentation_script.ipynb before training



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


 REAL-TIME DETECTION:-
<img width="2000" height="1068" alt="image" src="https://github.com/user-attachments/assets/4745d0f6-0ace-4097-a6fb-f0184ddd6091" />

<img width="2000" height="1062" alt="image" src="https://github.com/user-attachments/assets/a7c221f3-cf7b-4c74-9d55-0399328462f0" />

<img width="2000" height="1063" alt="image" src="https://github.com/user-attachments/assets/cc5fed15-e146-4029-b310-6e6bd9e83bbd" />

<img width="2000" height="1062" alt="image" src="https://github.com/user-attachments/assets/a4bfb7a0-57e8-48f9-8525-1c61263fdc40" />


