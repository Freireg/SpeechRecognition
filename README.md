# SpeechRecognition
Speech Recognition Model embedded in a Raspeberry Pi

This project is heavily inspired by Shawn Hymel youtube series "[Intro to TensorFlow Lite](https://www.youtube.com/watch?v=8-vl9bNY9aI&ab_channel=Digi-Key)"

This project consists in 3 phases:
* Creating the model features
>* Here the user should input the training datasets to make the speech recognition and select which word it wants to be the "wake-up" word
* Training the model and convert to tflite extension
>* In this phase the features created before need to be made into a TensorFlow model and trained
* Uploading the model into a RPI and run the script
>* Cloning this repo into the rasp should accelerate a lot the process
