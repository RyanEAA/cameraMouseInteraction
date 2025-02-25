- extension of kinivi's extension of kazuhito00

# VIDEO

Camera to Mouse Movement
https://github.com/user-attachments/assets/bfde221d-2122-4e39-b5a1-56773c656a23

Topper Up Recognizer
https://github.com/user-attachments/assets/238ac4d6-13a5-4d5d-818b-3c546c66671d





# Requirements
- python virtual environment 3.9.6
- make sure to install  python packages
  ```
  pip install opencv-python mediapipe tensorflow pyautogui
  ```
- will need to brew install python-tk
  ```
  brew install python-tk
  ```
- if you get the error saying "ValueError: Could not open 'model/keypoint_classifier/keypoint_classifier.tflite'." go to terminal and type 'cd hand-gesture-recognition-mediapipe' then 

1. move to media folder
```
cd hand-gesture-recognition-mediapipe
```
2. give correct file permission to load model
  ```
  chmod 644 model/keypoint_classifier/keypoint_classifier.tflite
  ```
  it will give access to the program to be able to read the model from the file
