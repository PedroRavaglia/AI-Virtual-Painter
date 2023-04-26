# AI-Virtual-Painter

Final project for Applied Mathematics Topics in Image Processing (MAE353) at UFRJ. I utilized the [mediapipe](https://google.github.io/mediapipe/) and [OpenCV](https://opencv.org/) libraries to implement real-time hand tracking and enable drawing on the screen with the index finger.



# How to Use:

* Use your index and middle finger to activate Selection Mode and choose from various colors or the eraser at the top of the screen.

![Selecting3](https://user-images.githubusercontent.com/74989519/121432273-d7cc7700-c950-11eb-91af-21f270f7c8a7.gif)

* Adjust the thickness of the draw using the distance between your thumb and index finger, selecting the desired size when the pinky finger is up.

![Selecting Thickness](https://user-images.githubusercontent.com/74989519/121432960-bc15a080-c951-11eb-91fc-1bdb8b5d832c.gif)

* Clear the screen simply by closing your hand.

![Cleaning](https://user-images.githubusercontent.com/74989519/121432623-4b6e8400-c951-11eb-85ec-cd0612e797b2.gif)

* Enter in Stand by Mode using only your index and pinky finger (indicated by a line between these 2 fingers). This mode is useful when you want to draw separate things on the screen.

![Drawing](https://user-images.githubusercontent.com/74989519/121436537-22e98880-c957-11eb-9904-55d43fe346ef.gif)


# Dependencies

* [mediapipe](https://google.github.io/mediapipe/)
* [OpenCV](https://opencv.org/)
* numpy

`pip install opencv-python`

`pip install numpy`

`pip install mediapipe`

