- extension of kinivi's extension of kazuhito00

# VIDEO


https://github.com/user-attachments/assets/bfde221d-2122-4e39-b5a1-56773c656a23



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
- if you get the error saying "ValueError: Could not open 'model/keypoint_classifier/keypoint_classifier.tflite'." run
  ```
  chmod 644 hand-gesture-recognition-mediapipe/model/keypoint_classifier/keypoint_classifier.tflite
  ```
  it will give access to the program to be able to read the model from the file
