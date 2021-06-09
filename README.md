# AI-Virtual-Painter

# About The Project

I've used [mediapipe](https://google.github.io/mediapipe/) and [OpenCV](https://opencv.org/) libraries to track our hand position in real-time and draw on the screen using the index finger.

Other features implemented:

* You can select the thickness of the draw using the distance between the thumb and the index finger, selecting the desired size when the pinky finger is up.

![Selecting Thickness](https://user-images.githubusercontent.com/74989519/121432960-bc15a080-c951-11eb-91fc-1bdb8b5d832c.gif)

* Using the index and the middle finger you enter in the Selection Mode, and you can select the different colors and the eraser at the top of the screen.

![Selecting3](https://user-images.githubusercontent.com/74989519/121432273-d7cc7700-c950-11eb-91af-21f270f7c8a7.gif)

* After Drawing on the screen you can clean it just by closing your hand.

![Cleaning](https://user-images.githubusercontent.com/74989519/121432623-4b6e8400-c951-11eb-85ec-cd0612e797b2.gif)

* You can enter in the stand by mode using only the index and the pinky finger (indicated by a line between these 2 fingers). This mode is useful when you want to draw separate things on the screen.

![Drawing](https://user-images.githubusercontent.com/74989519/121436537-22e98880-c957-11eb-9904-55d43fe346ef.gif)


# Dependencies

* [mediapipe](https://google.github.io/mediapipe/)
* [OpenCV](https://opencv.org/)
`pip install numpy opencv-python`

