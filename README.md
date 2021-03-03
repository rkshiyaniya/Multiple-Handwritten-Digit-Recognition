# Multiple Handwritten Digit Recognition using Deep Learning ( Keras )

# Requirements

* Python 3.5 +
* Numpy (+ mkl for Windows)
* PIL ( pillow )
* Opencv
* Keras ( Tensorflow as backend )
* tkinter ( python GUI )

# About Project

* Trained model on MNIST dataset Using CNN (Convolutional Nueral Network)

* Save model as 'mnist.h5' ( train_digit_recognizer.py )

* Using tkinter GUI make a canvas and write digit on it

* Using PIL get a copy of Handwritten Digits on the canvas and saved into '/img' as 'img_{image_number}.png'

* Use saved model 'mnist.h5' to predict saved Handwritten Digit image from canvas

# Screenshots

* Drawing canvas ...


<img src="gui/drawing_canvas_window.jpg?raw=true" width="100" height="100">

* Output Imgae ...

![Output](gui/predicted_image.jpg?raw=true)

* Saved Image using PIL-ImageGrab ...

![Grabbed_Image](img/img_0.png?raw=true)

