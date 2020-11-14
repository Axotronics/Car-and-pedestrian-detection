# HaarCascade Car and Pedestrian detector.

This is an app that differentiates between pedestrians and cars using a computer - vision algorithm known as a haarcascade.

# Pre Requisites

You will need to install a library of python known as opencv by running the following pip command in your terminal, powershell, shell or cmd.
$ pip install opencv-python.

You will need a python IDE such as pycharm, VS code or sublime text editor. You can install pycharm for windows  from:  https://www.jetbrains.com/pycharm/download/#section=windows

After installing these things. You're good to go!

# Concept of the Project

1. Python first reads both the haarcascade files.
2. Then it captures the video that you would've uploaded. Makes sure that there is continuity in the video
3. We then create a while loop so that the following process loops repeatedly.
4. The pixel data of the video is stored in two variables: successful_frame_read and frame
5. The video is then converted into grayscale.
6. We get the coordinates of the car and the pedestrian through a similar process and we draw a rectangle over the identified image in the video.
7. The video with the algorithm differentiating between cars and pedestrian is then displayed.

Hope my Idea was helpful. It is a very simple yet very useful project. For any queries kindly contact me on: akshayvr2@gmail.com


Happy Coding!
Akshay V.R.
