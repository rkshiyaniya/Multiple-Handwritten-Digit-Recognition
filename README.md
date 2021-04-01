# Multiple Handwritten Digit Recognition using Deep Learning ( TensorFlow - Keras )

# Requirements

* TensorFlow (Keras)
* Python 3.5 +
* Numpy (+ mkl for Windows)
* PIL ( pillow )
* Opencv
* tkinter ( python GUI )

# About Project

* Trained model on MNIST dataset Using CNN (Convolutional Nueral Network)

* Save model as 'mnist.h5' ( train_digit_recognizer.py )

* Using tkinter GUI make a canvas and write digit on it

* Using PIL get a copy of Handwritten Digits on the canvas and saved into '/img' as 'img_{image_number}.png'

* Also with the help of OpenCV by recognizing contours it can handle multiple digits

* Use saved model 'mnist.h5' to predict saved Handwritten Digit image from canvas

# Screenshots

* Drawing canvas ...

<img src="gui/drawing_canvas_window.png?raw=true" width="1920" height="1080">

* Output Imgae ...

<img src="gui/predicted_image.png?raw=true" width="1920" height="1080">

* Saved Image using PIL-ImageGrab ...

<img src="img/img_0.png?raw=true" width="784" height="784">

