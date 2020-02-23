# Donkey-Konvolutional
Donkey-Konvolutional is a project created by Landon Zweigle and Keegan Kochis.

The aim of this project is to train a convolutional neural network to play Donkey Kong Country. The model is intended to be converted to TensorFlow Lite and run on a Raspberry Pi. The game is going to be emulated on a separate machine and the game feed will be input to the Raspberry Pi via webcam. The Raspberry Pi will give inputs to the machine emulating the game via bluetooth.

## Dependencies
To use and work on this project you will need to install a couple python packages. This is under the assumption that you already have python3 installed.
##### OpenCV
Open your preferred shell and run the command "pip3 install opencv-python"
##### TensorFlow
1. Install Virtualenv by opening your preferred shell and running the command "pip3 install virtualenv"
2. Install TensorFlow by opening your preferred shell and running the command "pip3 install --user --upgrade tensorflow"
